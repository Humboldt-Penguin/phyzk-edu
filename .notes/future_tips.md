- If you have...
    - Local repo where website works.
    - (optional, but no reason not to have this) workflow to publish to GH pages.
- Then follow instructions below in order to...
    - Init a GH repo.
    - ^ Prep it for a custom domain.

```bash
## Ensure `gh` working
gh auth status

## Create repo & push existing main+develop
git switch main
gh repo create phyzk-edu --public --source=. --remote=origin --push
git push -u origin develop
gh repo edit --default-branch main  # I don't think this was necessary, but just in case...

## Create/configure the Pages site to be built by GitHub Actions workflow
gh api --method POST repos/{owner}/{repo}/pages -f build_type=workflow

## Set custom domain
gh api --method PUT repos/{owner}/{repo}/pages -f cname=edu.phyzk.net
```

---

1. After the steps above, in order to **configure Porkbun DNS for the subdomain...**
    1. Porkbun > DNS (for `phyzk.edu`) > ...
        - Type: `CNAME`
        - Host: `edu`
        - Answer/Value: `humboldt-penguin.github.io`
        - TTL: (whatever Porkbun default is fine)
    2. (Make sure to click "Add".)
    3. Delete the pre-existing record like `CNAME | *.phyzk.net | pixie.porkbun.com | 600` -- the other one (`ALIAS phyzk.net pixie.porkbun.com 600`) can stay.
2. Now, sit at command line and wait a little...
    1. Ensure that `dig +short CNAME edu.phyzk.net` outputs `humboldt-penguin.github.io.`.
    2. Run `gh api repos/{owner}/{repo}/pages` -- we're waiting for `status` or `protected_domain_state` to change from `null`/`false`, or HTTPS to become available. If in doubt, just feed to ChatGPT and ask if ready.
        - EDIT: not sure if true, but after navigating to `https://github.com/Humboldt-Penguin/phyzk-edu/settings/pages`, it seemed to work almost instantly...? Not sure if that prompts something special as opposed to just CLI, but worth trying.
    3. ^ Once GitHub finishes verifying DNS + issuing the cert, do:
        ```
        gh api --method PUT repos/Humboldt-Penguin/phyzk-edu/pages \
          --input - <<'JSON'
        {
          "https_enforced": true
        }
        JSON
        ```
        - If GitHub returns an error like "certificate not yet created" (common), just retry later after DNS has fully propagated and a deploy has run.


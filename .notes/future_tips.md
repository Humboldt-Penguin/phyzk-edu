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

- After the steps above, in order to **configure Porkbun DNS for the subdomain...**
    1. Porkbun > DNS (for `phyzk.edu`) > ...
        - Type: `CNAME`
        - Host: `edu`
        - Answer/Value: `humboldt-penguin.github.io`
        - TTL: (whatever Porkbun default is fine)
    2. "Add" -- now you're set!
    3. (optional...?) Delete the pre-existing record like `CNAME | *.phyzk.net | pixie.porkbun.com | 600`

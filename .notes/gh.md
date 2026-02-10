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

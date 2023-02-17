# root

## Branches

```mermaid
flowchart LR

Root["@langanng-temp/root"]-->develop-->master

```

### Sync to remote

```sh
# Add remote url
git remote set-url --add origin [url]
# Checkout the branch for sync
git checkout "@langnang-temp/root"

git pull
# Force push
git push -f
```

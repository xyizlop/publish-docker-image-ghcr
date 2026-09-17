## What is Github Container Registry

- a place to store container images within your org or personal account
- and that image can be access from your repo
- also allows to access public repo (anonymously)

## How to Authenticate?

- using Github personal access token (classic PATs) - CLI especially
- `GITHUB_TOKEN` - Github Actions

`write` permission to `packages` is required to publish package.
```yaml
permissions:
  packages: write
```

## IDK Why

Even though well documented connecting repository and packages via CLI (use of `LABEL`) is not working **Sept 17, 2026** however I can still link using Github UI. The behaviour is same for both public or private repo.
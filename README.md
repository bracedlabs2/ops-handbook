# Ops handbook

Internal runbooks for on-call and incident response. Edit on a branch. Merge to `main`.

**Publish handbook** runs on every push to `main` and uploads the site to the docs CDN with `HANDBOOK_PUBLISH_TOKEN`. Do not put that token in a workflow file. Rotate it under **Settings** → **Secrets and variables** → **Actions** if the CDN receipt looks wrong.

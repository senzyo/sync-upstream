This repo is used to auto sync forked repositories from upstream. 

1. Open [https://github.com/settings/tokens](https://github.com/settings/tokens) to generate a new personal access token (classic).
2. Note: Select the `repo` and `workflow` scopes.
3. Generate and copy the token.
4. Click **Settings** → **Secrets and variables** → **Actions** → **New repository secrets** in your `sync-upstream` repo.
5. Set `Name` to `PERSONAL_TOKEN` and paste the token as `Secret`.
6. Edit the [sync_upstream.yml](./.github/workflows/sync_upstream.yml) according to your needs.

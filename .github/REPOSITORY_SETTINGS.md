# Repository Settings Checklist

GitHub does not store every repository rule in the codebase. Apply the
following settings in the repository UI after merging this baseline.

## General

- Set the default branch to `main`.
- Enable squash merging.
- Disable merge commits if you want a linear history.
- Enable automatic branch deletion after merge.

## Branch Protection For `main`

Enable a branch protection rule for `main` with these settings:

- Require a pull request before merging.
- Require approvals before merging.
- Dismiss stale approvals when new commits are pushed.
- Require conversation resolution before merging.
- Require status checks to pass before merging.
- Require branches to be up to date before merging.
- Restrict force pushes.
- Prevent branch deletion.

## Suggested Required Checks

After the workflows run once, add these checks as required:

- `CI` workflow jobs: `Markdown`, `YAML`, `GitHub Workflows`
- `PR Title` workflow job: `Semantic PR Title`
- `Branch Name` workflow job: `Validate Branch Name`
- `Dependency Review` workflow job: `Dependency Review`

## Optional Hardening

- Enable signed commits if your team requires them.
- Enable secret scanning and push protection if available.
- Enable private vulnerability reporting.
- Require two approvals for sensitive infrastructure changes.

# Contributing Guide

## Branch Naming

Use short, descriptive branch names with one of these prefixes:

- `feature/<slug>`
- `fix/<slug>`
- `hotfix/<slug>`
- `chore/<slug>`
- `docs/<slug>`
- `refactor/<slug>`
- `test/<slug>`
- `ci/<slug>`
- `build/<slug>`
- `release/<slug>`

Examples:

- `feature/bootstrap-github-standards`
- `fix/ci-permission-scope`
- `chore/update-action-versions`

Dependabot branches are allowed as-is.

## Pull Request Titles

Pull request titles should follow a semantic format:

- `feat: add deployment workflow`
- `fix: correct branch name validation`
- `docs: improve contribution guide`
- `chore: update GitHub Actions pins`

Allowed types are `feat`, `fix`, `docs`, `chore`, `refactor`, `test`,
`ci`, `build`, `perf`, `revert`, and `security`.

## Pull Request Expectations

- Keep pull requests focused and reviewable.
- Link the issue or explain why the work is needed.
- Describe the user or platform impact.
- Include test or validation notes before requesting review.
- Wait for all required checks to pass before merging.

## Review And Merge Policy

- At least one approving review is recommended for all changes.
- Require at least two approvals for production-sensitive changes.
- Use squash merge to keep history clean.
- Do not merge directly to `main`.

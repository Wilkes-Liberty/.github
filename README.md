# `.github`: Wilkes & Liberty organization defaults

GitHub applies the files in this repository to every Wilkes & Liberty repository that does not carry its own copy. It must be public for that to work.

| Path | Purpose |
|---|---|
| `profile/README.md` | The organization profile page |
| `.github/ISSUE_TEMPLATE/` | Default issue templates and contact links |
| `.github/PULL_REQUEST_TEMPLATE.md` | Default pull request template |
| `CONTRIBUTING.md` | Baseline contributing guide |
| `CODE_OF_CONDUCT.md` | Code of conduct |
| `SECURITY.md` | Security policy and how to report a vulnerability |
| `.github/workflows/attribution.yml` | This repository's own pull request check |

A repository overrides any of these by adding its own file at the same path.

Two things do not propagate from here. `CODEOWNERS` is never inherited, so each repository needs its own. Reusable GitHub Actions workflows live in [`shared-ci`](https://github.com/Wilkes-Liberty/shared-ci).

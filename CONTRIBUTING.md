# Contributing (organization baseline)

This is the Wilkes & Liberty baseline contributing guide. A repository may add its own `CONTRIBUTING.md` for setup, tests and release mechanics; this one covers what they share.

## Where to report

- **Drupal modules.** Issues are tracked in each project's queue on drupal.org, for example `https://www.drupal.org/project/issues/file_gate`. Open bugs and feature requests there.
- **Everything else**, including `drupal-mcp-connector` and `shared-ci`, uses GitHub issues on its own repository.
- **Security problems** go to the address in [SECURITY.md](SECURITY.md), never to a public issue.

## Workflow

- **Trunk-based.** Each repository has one long-lived default branch: `1.x` for the Drupal modules, `master` elsewhere. Branch off it and open a pull request back to it.
- **No direct pushes to the default branch.** It is protected; changes land by pull request with passing CI.
- **Keep pull requests focused**, one feature or fix each.

## Before you push

Run the repository's lint and tests locally. Its own `CONTRIBUTING.md` or `README.md` has the commands. CI runs the same checks and must be green to merge.

## Changelog

We follow [Keep a Changelog](https://keepachangelog.com/) and [SemVer](https://semver.org/). Add an entry to `CHANGELOG.md` under `[Unreleased]` when a change is one a user of the project would want to know about.

The changelog check is opt-in. A pull request must update `CHANGELOG.md` only when it carries the `changelog` label; a maintainer applies the label to pull requests whose changes belong in the changelog. Unlabelled pull requests pass. `drupal-mcp-connector` is the exception and expects an entry by default.

## Commit messages

Follow [Conventional Commits](https://www.conventionalcommits.org/): `feat:`, `fix:`, `docs:`, `chore:`, `ci:` and so on.

## Releases

Releases are immutable semver tags cut from the default branch, with `-rc.N` for candidates. The Drupal modules are released on drupal.org.

## Security

Never commit secrets. Report vulnerabilities privately as [SECURITY.md](SECURITY.md) describes.

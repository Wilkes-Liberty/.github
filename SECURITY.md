# Security Policy

This policy applies to all Wilkes & Liberty repositories unless a repository overrides it with its own `SECURITY.md`.

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

Email **security@wilkesliberty.com** with:

- A description of the vulnerability
- Steps to reproduce
- Potential impact
- Any suggested mitigations

You will receive acknowledgement within **48 hours**. For critical issues we aim to ship a fix within **7 days**.

You may also use GitHub's [private vulnerability reporting](https://docs.github.com/en/code-security/security-advisories/working-with-repository-security-advisories) where enabled on a repository.

## Supported Versions

Each repository supports its latest released line (`0.x` or `1.x` as applicable). Fixes land on the default branch and ship in the next tagged release.

## Handling Credentials

- Never commit secrets. Use the repository's documented secret store, and keep local `.env` files out of version control.
- Prefer short-lived credentials (OIDC, GitHub App tokens) over long-lived tokens.
- Rotate any credential that may have been exposed, and report the exposure to the address above.

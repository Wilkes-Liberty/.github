<!-- This file renders on the Wilkes-Liberty organization profile page. -->

# Wilkes & Liberty

We build headless Drupal and Next.js platforms, and publish the modules and tools we make along the way.

## Drupal modules

Each module is published on drupal.org. Report bugs and request features in the project's issue queue there; the repositories here carry the code.

| Module | What it does |
|---|---|
| [`mcp_sentinel`](https://www.drupal.org/project/mcp_sentinel) | Governs AI-agent access to Drupal over MCP, JSON:API and GraphQL: policy profiles, field redaction, DLP and audit logging. |
| [`file_gate`](https://www.drupal.org/project/file_gate) | Gates access to private files with short-lived signed URLs or authenticated access, for decoupled front ends. |
| [`field_guard`](https://www.drupal.org/project/field_guard) | Per-field access control from configuration that fails closed. |
| [`audit_chain`](https://www.drupal.org/project/audit_chain) | Tamper-evident, hash-chained audit logging for any Drupal module. |
| [`menu_autopilot`](https://www.drupal.org/project/menu_autopilot) | Content-driven navigation: curate the top level, and children follow published content. |
| [`graphql_compose_codegen`](https://www.drupal.org/project/graphql_compose_codegen) | Generates TypeScript types, GraphQL fragments and React component stubs from a Drupal content model. |
| [`postmark_webhooks`](https://www.drupal.org/project/postmark_webhooks) | Receives Postmark bounce, spam and delivery webhooks and suppresses mail to those addresses. |

## Tools

| Repository | What it is |
|---|---|
| [`drupal-mcp-connector`](https://github.com/Wilkes-Liberty/drupal-mcp-connector) | MCP server for Drupal: JSON:API and GraphQL, governed writes, draft translations, audit reports and a Drush bridge. Issues are tracked on GitHub. |
| [`shared-ci`](https://github.com/Wilkes-Liberty/shared-ci) | Reusable GitHub Actions workflows our repositories call. |

## Contributing and security

The organization's default [contributing guide](https://github.com/Wilkes-Liberty/.github/blob/master/CONTRIBUTING.md), [code of conduct](https://github.com/Wilkes-Liberty/.github/blob/master/CODE_OF_CONDUCT.md) and [security policy](https://github.com/Wilkes-Liberty/.github/blob/master/SECURITY.md) apply to every repository that does not carry its own.

Report security issues to **security@wilkesliberty.com**, not in a public issue.

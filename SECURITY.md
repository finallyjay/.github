# Security Policy

These are the default security terms for repositories owned by
[@finallyjay](https://github.com/finallyjay). An individual repository may ship
its own `SECURITY.md`, which takes precedence over this one.

## Reporting a vulnerability

If you discover a security vulnerability, please report it **privately** via
GitHub's private vulnerability reporting on the affected repository
(**Security → Report a vulnerability**, or the repo's `/security/advisories/new`
page). **Do not open a public issue.**

Expect an initial acknowledgement within a few days. These are personal projects
maintained in spare time, so response times are best-effort — but credible
vulnerability reports are prioritised over feature work.

## Supported versions

Unless a repository states otherwise, only the latest commit on the default
branch is supported. There are no versioned releases.

## Scope

**In scope:** the application code in the repository, its server-side handling of
secrets and credentials, and dependency vulnerabilities surfaced by Dependabot.

**Out of scope:** vulnerabilities in third-party services or APIs (report those to
the respective vendor), social engineering against contributors, denial of
service against any deployed instance, and issues that require the reporter to
already hold admin access to a deployed instance.

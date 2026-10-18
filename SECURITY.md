# Security policy

stardelt is **pre-alpha** and not ready for production use. We still take security reports
seriously — the project's defaults are meant to be sovereign (no phone-home, permissive licenses
only), and a vulnerability in that promise matters.

## Reporting a vulnerability

**Do not open a public issue with exploit details.**

1. Open the repository the problem is in, go to **Security → Report a vulnerability**
   (GitHub private vulnerability reporting).
2. If that button is not available on the repository, open a public issue that says only
   *"I would like to report a security problem privately"* — no details — and a maintainer will
   arrange a private channel.

Please include the affected repo and version/commit, what an attacker can do, and the steps to
reproduce.

## What to expect

- Best-effort acknowledgement; there is no SLA at this stage.
- Fixes land through a normal pull request on `main`, with the advisory published once a fix is
  available.
- Upstream components (Trino, Lakekeeper, SeaweedFS, …) are not vendored: a vulnerability in one of
  them should also be reported to that project.

## Supported versions

Only `main`. No release has been cut yet.

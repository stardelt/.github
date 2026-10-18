# Contributing to stardelt

Thanks for helping. The full workflow — branching, commit style, review expectations, releases —
lives in the docs:

**<https://stardelt.io/developer/contributing>**

The short version:

- **PR-only.** `main` is protected; every change arrives as a pull request. Draft PRs are welcome.
- **Small and scoped.** One work package or one fix per PR; split rather than push a mega-change.
- **Branch names:** `feat/…`, `fix/…`, `docs/…`, `chore/…`, `wp/<id>-slug`.
- **Commits and PR titles:** `type(scope): what changed`.
- **Run the repo's check** and paste the result in the PR description:

  | Repo | Check |
  |---|---|
  | `stardelt-docs` | `npm run build` |
  | `stardelt-nova` | `cargo check`, then `npm --prefix frontend run build` |
  | `stardelt-operator` | `cargo fmt --check`, `cargo clippy -D warnings`, `cargo test` |
  | `stardelt-platform` | `helm lint`, `bash -n` on changed scripts |
  | `stardelt-demos` | `make up && make smoke` |

- **Licenses:** OSI-permissive dependencies only (see the license policy in the docs).
- **AI-assisted changes are welcome** — tag the model (`Model: <provider>/<model>`) and own the
  change.

By participating you agree to the [Code of Conduct](CODE_OF_CONDUCT.md). Security problems: see
[SECURITY.md](SECURITY.md).

---
name: Implementation ticket
about: A change precise enough that a small model or a new contributor can implement it without asking questions
title: "<repo>/<area>: <imperative outcome, e.g. 'reject self-overwrite transfers'>"
labels: ["ready-to-implement"]
---

<!--
Write this so the implementer needs NO other context. Name exact files, symbols and commands.
If you cannot fill a section, the ticket is not ready: say so under "Open questions" instead.
Guide with a worked example: https://stardelt.io/developer/contributing#writing-a-ticket
-->

## Why (2–3 sentences)
What is wrong or missing, and who notices. Link the spec section or work package if there is one (e.g. `master-spec §6`, `WP-12`).

## Current behavior
- Observed: exact output, status code or log line (paste it).
- Where: `path/to/file.rs:123` (permalink to the line on `main`).

## Required change
Numbered, in the order to do them. Each step names the file, the function/symbol and the edit; show before → after for anything under ~15 lines.

1. In `path/to/file.rs`, function `name()`: …
2. In `path/to/other.ts`: …
3. Add a test `test_name` in `path/to/test` that fails before this change and passes after.

## Do NOT
- Touch: files/areas that look related but are out of scope.
- Add dependencies, rename public items or change defaults unless listed above.
- Fix neighbouring problems here — open a separate ticket.

## How to verify
Exact commands, run from the repo root, with the expected result.

```bash
cargo test -p <crate> <test_name>     # expect: 1 passed
curl -si http://localhost:8080/api/…   # expect: HTTP/1.1 400 and {"error":"…"}
```

## Acceptance criteria
- [ ] Observable behavior 1 (testable)
- [ ] Observable behavior 2
- [ ] The repo's standard checks pass (see the table in the contributing guide)
- [ ] Docs updated in the same PR if a reader-visible behavior changed (name the page)

## Pitfalls
Known traps: ordering, generated files (e.g. `chart/crds/` is generated — run `cargo run --bin crdgen`), things that look like the fix but are not.

## Size and branch
- Size: S (≤ 30 lines changed) / M (≤ 150) / L (split it)
- Branch: `fix/<slug>` or `feat/<slug>`; PR title `type(scope): summary`; one PR per ticket.

## Open questions
Anything the implementer must NOT guess. If non-empty, remove the `ready-to-implement` label.

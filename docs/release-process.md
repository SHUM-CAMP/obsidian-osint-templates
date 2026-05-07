# Release process (docs-only)

This repository currently uses a docs-only release workflow.

## Scope

- Version source of truth: `VERSION`
- Change history: `CHANGELOG.md`
- Versioning style: pre-1.0 Semantic Versioning (`0.x.y`)

## Steps for each new release

1. Review `CHANGELOG.md` and move finalized items from `## [Unreleased]` into a new version section:
   - `## [<new_version>] - YYYY-MM-DD`
2. Keep changes grouped under:
   - `Added`
   - `Changed`
   - `Fixed`
   - `Removed`
3. Update `VERSION` to the same `<new_version>`.
4. Confirm `README.md` still points contributors to `VERSION` and `CHANGELOG.md`.

## Pre-1.0 bump guidance

- Use `0.x.0` for meaningful additions or structural changes.
- Use `0.0.x` for small, non-breaking fixes and editorial corrections.
- If a breaking reorganization happens before `1.0.0`, document it explicitly in `Changed` and/or `Removed`.

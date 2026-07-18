# Unified Obsidian OSINT Vault (WebBreacher + SHUM)

This repository is a single, clone-ready Obsidian vault that combines the full:
- WebBreacher original templates, SOP notes, and examples
- SHUM methodology and reporting templates in English and Ukrainian

The curation policy is side-by-side preservation: both sources remain intact and are surfaced through a unified navigation layer.

## Quick start

1. Clone the repository.
2. Open the repository root as an Obsidian vault.
3. Start with:
   - `00_Home.md`
   - `01_QuickStart.md`
   - `SHUM_Templates/_index.md`
   - `Methodology/_index.md`

Current development version: see `VERSION` (`0.1.2`).
Change history: see `CHANGELOG.md`.

## Versioning policy (pre-1.0)

This repository uses Semantic Versioning in the `0.x.y` phase while the vault is
still in active development before `1.0.0`.

- Minor (`0.x.0`): meaningful additions or reorganizations (new template packs,
  methodology sections, structure updates).
- Patch (`0.0.x`): small non-breaking improvements (typos, wording, metadata fixes).
- Breaking reorganizations can still happen before `1.0.0`; record them clearly in
  `CHANGELOG.md` under `Changed` and `Removed`.

## Unified structure

- `00_Home.md` - vault landing page
- `01_QuickStart.md` - onboarding and workflow
- `Methodology/` - SOP and methodology indexes
- `Operations/` - case lifecycle, handoffs, review queues, and metadata contract
- `Reports/` - report production pipeline (draft -> QA -> approved -> published)
- `SHUM_Templates/` - preserved SHUM ENG/UKR materials with parallel MD and DOCX folders
- `Training/` - onboarding and exercise tracks
- `Examples/` - links into WebBreacher example case materials
- `WebBreacher_originals/` - preserved upstream snapshot
- `.obsidian/` - portable default vault configuration

## SHUM reporting templates

Language-specific Markdown templates live under `MD/`; matching Word sources live under `RTF/` 

## What changed from upstream WebBreacher

- Added SHUM-specific methodology and reporting packs.
- Added bilingual ENG/UKR template organization.
- Added root-level navigation notes and section indexes for faster discovery.
- Added root `.obsidian` defaults focused on portability (avoids machine-specific workspace layout files).

## Prebuilt plugin bundle

The vault ships with a curated plugin set pre-enabled in `.obsidian/community-plugins.json`:
- `docx-viewer` (primary in-app DOCX rendering)
- `docxer` (fallback DOCX preview + markdown conversion)
- `open-with` (system-app fallback for Word/LibreOffice)
- `obsidian-tasks-plugin`
- `obsidian-map-view`
- `obsidian-leaflet-plugin`

DOCX workflow intent:
- author and iterate in markdown (`SHUM_Templates/*/MD/`)
- review/export and handoff in DOCX (`SHUM_Templates/*/DOCX/`)
- if in-app rendering fails for a file, use `open-with` as a one-click external fallback

## Obsidian template workflow

- Template folder is configured as `SHUM_Templates`/ `WebBreacher_Templates/` in `.obsidian/templates.json`.
- Insert with Obsidian command palette: `Templates: Insert template`.
- Use `WebBreacher_originals/WebBreacher_Templates/` and `SHUM_Templates/{ENG,UKR}/` as canonical insertion paths.
- Keep working case notes outside these folders to preserve the original templates.

## Expansion best practices

- Use a shared metadata schema from `Operations/Metadata_contract.md` for all operational notes.
- Keep evidence traceability strict: each report claim references source and evidence notes.
- Follow a review flow before publication: peer review -> QA -> signoff.
- Use role-based operational pages in `Operations/` and reporting pipeline docs in `Reports/`.

## How SHUM pack fits in

SHUM content is integrated as a first-class reporting and methodology layer while preserving WebBreacher originals for SOP and reference workflows. Teams can:
- use `WebBreacher_SOP` guidance for investigative process structure
- use `SHUM_Templates` for operational reporting output
- keep both systems in one linked, local Obsidian workspace

## About SHUM

[SHUM](https://shum-ng.org/) is a public organization founded by experts from the international OSINT community. The organization uses OSINT methods to investigate war crimes related to Russia’s war against Ukraine, support law enforcement and judicial actors, counter disinformation, and contribute to human rights work.

More:
- Website: https://shum-ng.org/
- LinkedIn: https://www.linkedin.com/company/ngoshumcamp/

## Attribution

This project is based on the original work of Micah Hoffman and the upstream repository [WebBreacher/obsidian-osint-templates](https://github.com/WebBreacher/obsidian-osint-templates).

Additional referenced authors in original materials include Claudia Tietze, Ervin Zubic, and Markus Malewski.

## License

Original materials in this project are licensed under the Creative Commons Attribution-ShareAlike 4.0 International License (CC BY-SA 4.0): http://creativecommons.org/licenses/by-sa/4.0/

If you reuse or adapt material from this repository, keep required attribution and preserve applicable license terms.

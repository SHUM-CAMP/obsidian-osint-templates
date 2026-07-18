# Quick Start

## 1) Clone and open
1. `git clone <repo-https://github.com/SHUM-CAMP/obsidian-osint-templates>`
2. Open the repository folder as an Obsidian vault

## 2) Recommended first notes
- `00_Home.md`
- `SHUM_Templates/_index.md`
- `Methodology/_index.md`
- `Examples/_index.md`
- `Operations/_index.md`
- `Reports/_index.md`
- `Training/_index.md`

## 3) Working model
- Use SHUM and WebBreacher content side-by-side
- Follow SOP/methodology from `Methodology/`
- Use ENG/UKR report packs from `SHUM_Templates/ENG/` and `SHUM_Templates/UKR/`
- Use original templates from `WebBreacher_originals/WebBreacher_Templates/`

## 4) Plugin posture
- Core Obsidian plugins are enabled by default in `.obsidian/core-plugins.json`
- Community plugins are prebuilt for reporting workflows:
  - `docx-viewer` (primary in-app DOCX reader)
  - `docxer` (fallback DOCX preview and conversion)
  - `open-with` (open DOCX in system Word/LibreOffice when needed)
  - `obsidian-tasks-plugin`
  - `obsidian-map-view`
  - `obsidian-leaflet-plugin`

## 5) DOCX in Obsidian
- Browse report artifacts in `SHUM_Templates/*/RTF/`.
- Open a `.docx` file directly in Obsidian; `docx-viewer` is the default reader.
- If rendering is imperfect for a specific file, use fallback options:
  1. Open with `docxer`.
  2. Use `open-with` to open in your system app (Word/LibreOffice).
- Author case content in markdown (`SHUM_Templates/*/MD/`) and use DOCX primarily for reporting review/export handoff.

## 6) Using this as an Obsidian template vault
1. Confirm the Templates core plugin is enabled in Obsidian.
2. Use command palette: `Templates: Insert template`.
3. Pick from:
   - `WebBreacher_originals/WebBreacher_Templates/...`
   - `SHUM_Templates/ENG/...`
   - `SHUM_Templates/UKR/...`

## 7) Suggested naming for generated notes
- Use case-based names, for example: `case-2026-05-targetname.md`
- Keep created investigation outputs outside `SHUM_Templates/` or `WebBreacher_originals/WebBreacher_Templates/` to preserve template originals

## 8) Operational metadata contract
- Use fields from `Operations/Metadata_contract.md` for new case/entity/source/evidence notes.

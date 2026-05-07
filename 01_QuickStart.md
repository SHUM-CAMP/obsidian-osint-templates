# Quick Start

## 1) Clone and open
1. `git clone <repo-url>`
2. Open the repository folder as an Obsidian vault

## 2) Recommended first notes
- `00_Home.md`
- `Templates/_coverage_checklist.md`
- `Templates/_index.md`
- `Methodology/_index.md`
- `ReportTemplates/_index.md`
- `ReportTemplates/_coverage_checklist.md`
- `Operations/_index.md`
- `Reports/_index.md`
- `Training/_index.md`

## 3) Working model
- Use SHUM and WebBreacher content side-by-side
- Reuse templates from `Templates/`
- Follow SOP/methodology from `Methodology/`
- Use ENG/UKR report packs from `ReportTemplates/`

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
- Browse report artifacts in `ReportTemplates/*/DOCX/`.
- Open a `.docx` file directly in Obsidian; `docx-viewer` is the default reader.
- If rendering is imperfect for a specific file, use fallback options:
  1. Open with `docxer`.
  2. Use `open-with` to open in your system app (Word/LibreOffice).
- Author case content in markdown (`ReportTemplates/*/MD/`) and use DOCX primarily for reporting review/export handoff.

## 6) Using this as an Obsidian template vault
1. Confirm the Templates core plugin is enabled in Obsidian.
2. Confirm template folder is `Templates` (`.obsidian/templates.json`).
3. Use command palette: `Templates: Insert template`.
4. Pick from:
   - `Templates/WebBreacherTemplates/...`
   - `Templates/SHUMTemplates/ENG/...`
   - `Templates/SHUMTemplates/UKR/...`

## 7) Suggested naming for generated notes
- Use case-based names, for example: `case-2026-05-targetname.md`
- Keep created investigation outputs outside `Templates/` to preserve template originals

## 8) Operational metadata contract
- Use fields from `Operations/Metadata_contract.md` for new case/entity/source/evidence notes.

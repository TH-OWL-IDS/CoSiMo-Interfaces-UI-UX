# CLAUDE.md — CoSiMo Interfaces & UI/UX

This is a design documentation repository. No production code lives here.

## What this repo is
A living workspace for designing and documenting the user interfaces of the CoSiMo system across all touchpoints: mobile app, web app, in-cabin display, and physical gadgets. See `README.md` for full context.

## Mandatory rules
- Always update `changelog.md` after making any change (format: `## YYYY-MM-DD`, most recent at top)
- All files in English
- File names: lowercase, hyphenated (e.g. `boarding-flow.md`)
- DDRs in `decisions/` follow the naming pattern `NNN-short-title.md`
- Each interface folder (except `cabin/`) keeps its shape: `overview.md`, `flows/`, `specs/`, `assets/`
- `cabin/` contains only `overview.md` — IDS @ TH OWL owns its internal structure

## What not to do
- Do not make or imply design decisions without explicit instruction
- Do not create files outside the established folder structure without asking
- Do not add production code of any kind
- Do not add subfolders to `interfaces/cabin/` — that is managed externally

## Key files
- `CONTRIBUTING.md` — conventions, folder guide, DDR template

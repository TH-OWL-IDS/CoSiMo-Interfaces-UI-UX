# Changelog

> **Note for AI assistants:** This file must be updated whenever changes are made to this repository. Add a new entry under the correct date (format: `## YYYY-MM-DD`) with a short description of what was added, changed, or removed. If the date already exists, append to it. Always keep the most recent date at the top.

---

## 2026-05-28

- Initialized repository structure
- Added `README.md` with project overview and navigation table
- Added `CONTRIBUTING.md` with folder guide, conventions, and DDR template
- Added `changelog.md` (this file)
- Added `CLAUDE.md` and `AGENTS.md` with project context and mandatory rules for AI assistants
- Created interface folder stubs: `app/`, `webapp/`, `cabin/`, `gadgets/` each with `overview.md`
- Removed direct subfolders from `gadgets/` — it is now a container with one subfolder per gadget type
- Created `interfaces/gadgets/nfc-card/` with `overview.md`, `flows/`, `specs/`, `assets/`
- Updated `README.md` and `CONTRIBUTING.md` to reflect gadgets container pattern
- Added `.gitignore` covering macOS, Windows, editors, design tools, and Claude Code
- Added example flow naming convention (`example_` prefix) to `CLAUDE.md`, `AGENTS.md`, and `CONTRIBUTING.md`
- Created `decisions/` and `assets/` folders at repo root

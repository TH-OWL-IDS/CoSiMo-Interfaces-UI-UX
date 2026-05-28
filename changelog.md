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
- Created `interfaces/app/flows/example_2friends_back-pain.md` — first example flow for the app interface
- Created `decisions/001-cosimo-character-visual-identity.md` — design decision fixing CoSiMo's minimal floating face character
- Created `decisions/002-cosimo-character-customisation.md` — design decision establishing character selectability for accessibility
- Created `decisions/003-cosimo-character-consistency.md` — design decision establishing CoSiMo as one consistent character across all interfaces
- Created `decisions/` and `assets/` folders at repo root

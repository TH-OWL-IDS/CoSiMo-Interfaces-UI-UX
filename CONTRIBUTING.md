# How to Work with this Repository

This guide explains how to navigate, add, change, and remove content in the CoSiMo Interfaces repository. It is intended for project contributors as well as AI assistants working in this repository.

---

## What Lives Where

| Path | What goes here |
|---|---|
| `README.md` | Project overview and repo orientation — keep it high-level |
| `changelog.md` | A running log of all changes made to this repository |
| `interfaces/app/` | Mobile app — flows, specs, and assets |
| `interfaces/webapp/` | Web app / operator dashboard — flows, specs, and assets |
| `interfaces/cabin/` | In-cabin display — overview and handoff context only |
| `interfaces/gadgets/` | Physical gadgets — overview and one subfolder per gadget type |
| `interfaces/gadgets/nfc-card/` | NFC boarding cards — flows, specs, and assets |
| `decisions/` | Design Decision Records (DDRs) |
| `assets/` | Shared visual exports spanning multiple interfaces |

---

## Folder Shape

Top-level interface folders (`app/`, `webapp/`) follow this structure directly:

```
interfaces/<name>/
  overview.md    ← purpose, scope, open questions
  flows/         ← user journeys, interaction flows
  specs/         ← screen-by-screen specs and annotations
  assets/        ← Figma exports, mockups, icons (any format)
```

`gadgets/` is a container — it holds only `overview.md` at its root, with one subfolder per gadget type (e.g. `nfc-card/`), each following the same shape above.

`cabin/` holds only `overview.md` — IDS @ TH OWL owns its internal structure.

---

## Adding a Document

1. Choose the correct folder based on the table above.
2. Create a new `.md` file with a clear, lowercase, hyphenated name (e.g. `boarding-flow.md`).
3. Start the file with a `# Title` and a short description of what it covers.
4. Update `changelog.md` with the date and what was added.

---

## Adding Assets

- Place exports inside the relevant `assets/` folder (per-interface or root-level shared).
- Any format is accepted: PNG, SVG, PDF, Figma exports, etc.
- Use descriptive, lowercase, hyphenated filenames (e.g. `home-screen-v2.png`).
- Update `changelog.md`.

---

## Changing a Document

1. Edit the file directly.
2. If the change reflects a significant design choice, consider whether a DDR is needed (see below).
3. Update `changelog.md`.

---

## Removing a Document

1. Before deleting, check whether anything else references the file (search for its filename).
2. If it captures a decision that was once active, consider moving it to an archive rather than deleting it.
3. Update `changelog.md`.

---

## Writing a Design Decision Record (DDR)

DDRs live in `decisions/`. They capture the context, options, and reasoning behind significant design choices — so future contributors understand *why* the interface works the way it does, not just *how*.

**File naming:** `NNN-short-title.md` (e.g. `001-onboarding-approach.md`)

**Template:**

```markdown
# NNN — Title

**Date:** YYYY-MM-DD  
**Status:** Proposed | Accepted | Deprecated

## Context
What situation or problem triggered this decision?

## Options Considered
- Option A — short description
- Option B — short description

## Decision
What was decided and why.

## Consequences
What does this decision enable or constrain going forward?
```

---

## General Conventions

- All files are written in **English**.
- File names are **lowercase and hyphenated** (no spaces, no camelCase).
- Every change to this repository should have a corresponding entry in `changelog.md`.
- Prefer editing existing documents over creating new ones unless the topic is genuinely distinct.

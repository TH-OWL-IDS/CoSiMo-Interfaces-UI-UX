# CoSiMo — Interfaces & UI/UX

This repository is the central workplace for designing and documenting the user interfaces and experience of the **CoSiMo** system — the inclusive mobility concierge built for the [MonoCab](https://monocab-system.com). It captures interaction flows, screen specs, design decisions, and visual assets across all CoSiMo touchpoints.

---

## Where to find what

| I want to… | Go to |
|---|---|
| Understand the mobile app interface | [interfaces/app/](interfaces/app/) |
| Understand the web app / operator dashboard | [interfaces/webapp/](interfaces/webapp/) |
| Understand the in-cabin interfaces | [interfaces/cabin/](interfaces/cabin/) |
| Understand physical gadgets | [interfaces/gadgets/](interfaces/gadgets/) |
| Understand a past design decision | [decisions/](decisions/) |
| Find shared visual exports | [assets/](assets/) |
| Contribute or add content | [CONTRIBUTING.md](CONTRIBUTING.md) |
| See what has changed | [changelog.md](changelog.md) |

---

## Repository Structure

```
CoSiMo-Interfaces-UI-UX/
│
├── README.md              # This file
├── CONTRIBUTING.md        # Guide for navigating and contributing to this repo
├── changelog.md           # Log of all changes made to this repository
│
├── interfaces/
│   ├── app/               # Mobile app (iOS / Android)
│   │   ├── overview.md    # Interface purpose, scope, and open questions
│   │   ├── flows/         # User journeys and interaction flows
│   │   ├── specs/         # Screen-by-screen specs and annotations
│   │   └── assets/        # Figma exports, mockups, icons
│   │
│   ├── webapp/            # Browser-based app / operator dashboard
│   │   ├── overview.md
│   │   ├── flows/
│   │   ├── specs/
│   │   └── assets/
│   │
│   ├── cabin/             # In-cabin display (developed by IDS @ TH OWL)
│   │   └── overview.md    # Scope and handoff context only — IDS owns substructure
│   │
│   └── gadgets/           # Physical gadgets — one subfolder per gadget type
│       ├── overview.md    # Gadgets scope and conventions
│       └── nfc-card/      # NFC boarding cards
│           ├── overview.md
│           ├── flows/
│           ├── specs/
│           └── assets/
│
├── decisions/             # Design Decision Records (DDRs)
└── assets/                # Shared exports spanning multiple interfaces
```

# ⚖️ WillWiz — Australian Will Wizard

> A step-by-step browser tool for Australians to understand, prepare, and document the information needed to make a valid Will.

**🔗 Live App:** [kbcianfa.github.io/WillWiz](https://kbcianfa.github.io/WillWiz/will-wizard.html)  
**📖 Guide:** [kbcianfa.github.io/WillWiz/will-wizard-guide.html](https://kbcianfa.github.io/WillWiz/will-wizard-guide.html)

---

## What It Does

WillWiz walks Australians through the key decisions and information required to prepare a Will — in plain language, without the legal jargon. It's not a lawyer, and it doesn't produce a legally binding document, but it helps you get your affairs in order so that when you do sit down with a solicitor (or use a Will kit), you've already done the thinking.

Everything runs in your browser. Nothing leaves your device.

---

## Features

**Step-by-Step Wizard**
- Guided multi-step form covering the core components of an Australian Will
- Personal details, executor appointment, asset distribution, guardianship provisions, and specific bequests
- Plain-English explanations at each step so you understand what you're deciding and why

**Australian-Specific Content**
- Framed around Australian law and terminology
- Addresses state-by-state execution requirements (witness rules, signing formalities)
- Covers superannuation death benefit nominations as a separate consideration (since super doesn't automatically form part of your estate)
- Flags common pitfalls: unwitnessed Wills, beneficiaries acting as witnesses, no-contest clauses

**Guide & Instructions Page**
- Standalone reference document explaining Will fundamentals
- Covers: what makes a Will valid in Australia, who can be an executor, what happens if you die intestate, when to update your Will
- Warning callouts for legally sensitive situations (blended families, business interests, overseas assets)

**Privacy First**
- No backend, no accounts, no data transmission
- All data stays in-browser for the session — close the tab and it's gone
- No tracking, no analytics

**Design**
- Professional navy and gold legal aesthetic (Playfair Display / Lora typography)
- Print-friendly output for taking to your solicitor

---

## ⚠️ Important Disclaimer

**WillWiz is an information and preparation tool, not a legal service.**

- It does not provide legal advice
- The output is not a valid Will and has no legal effect
- Australian Will requirements vary by state and territory — always have your Will properly witnessed and signed per your state's rules
- Complex situations (blended families, significant assets, business interests, overseas property) require a solicitor

**Always have your completed Will reviewed and executed by a qualified Australian legal practitioner.**

---

## Tech Stack

| Thing | Detail |
|---|---|
| Language | Vanilla HTML/CSS/JS — zero build tools |
| Fonts | Playfair Display, Lora, Source Sans 3 (Google Fonts) |
| Hosting | GitHub Pages |
| Architecture | Two single-file HTML pages (wizard + guide) |
| Backend | None |
| Data storage | None — session only |

Classic vibe-coded tool. Open the file, it runs. No npm, no build pipeline, no server.

---

## Getting Started

### Use the Hosted Version

Visit [kbcianfa.github.io/WillWiz/will-wizard.html](https://kbcianfa.github.io/WillWiz/will-wizard.html) — no sign-up, no install.

Read the guide first if you're unfamiliar with Australian Will requirements: [will-wizard-guide.html](https://kbcianfa.github.io/WillWiz/will-wizard-guide.html)

### Run Locally

```bash
git clone https://github.com/KBCIanFa/WillWiz.git
cd WillWiz
# Open will-wizard.html in your browser.
```

No server required.

---

## Files

```
WillWiz/
├── will-wizard.html        # Main step-by-step wizard
├── will-wizard-guide.html  # Reference guide and instructions
├── LICENSE                 # GPL-3.0
└── README.md
```

---

## Licence

GPL-3.0 — open source, free to use and adapt. See [LICENSE](LICENSE) for details.

---

## Part of the Vibe Coding Portfolio

Built at [kbcianfa.github.io](https://kbcianfa.github.io) — a suite of Australian-focused single-file web tools. Other tools in the family:

- [RV Power Designer](https://kbcianfa.github.io/RVPowerSystems) — solar/battery sizing for caravans
- [RV Route Planner AU](https://kbcianfa.github.io/RVRoutePlanner) — AI-powered caravan route planning
- [TowCheck AU](https://kbcianfa.github.io/Towing/) — towing compliance calculator
- [LogMyJourney AU](https://kbcianfa.github.io/LogMyJourney/) — trip logging app

---

*Built in Queensland, Australia.*

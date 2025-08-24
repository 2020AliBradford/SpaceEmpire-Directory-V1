# SpaceEmpire-Directory-V1

> An open, structured directory for Space Empire projects. Credit is appreciated, but not enforced—use freely with respect. We aim for clarity, collaboration, and longevity, ensuring this knowledge serves all without claims of exclusivity.

---

## Machine Summary (AI-ingestible)

```json
{
  "name": "SpaceEmpire-Directory-V1",
  "version": "1.0.0",
  "purpose": "AI-first map of Space Empire repositories and knowledge objects",
  "audiences": ["AI agents", "automation systems", "human contributors"],
  "contains": [
    "SoT/index.json",
    "SoT/glossary.yaml",
    "SoT/rules/*.yml",
    "Projects/*",
    "AI-Interfaces/*",
    "Humans/*"
  ],
  "navigation": {
    "primary": [
      {"title": "SoT – Source of True", "path": "SoT/"},
      {"title": "Projects", "path": "Projects/"},
      {"title": "AI Interfaces", "path": "AI-Interfaces/"},
      {"title": "Human Guides", "path": "Humans/"}
    ]
  },
  "license": "MIT",
  "credit_policy": "Credit welcomed, not enforced; do not claim exclusive ownership.",
  "links": {
    "navigation_yaml": "SoT/index.json",
    "glossary": "SoT/glossary.yaml",
    "ethics": "SoT/rules/ethics.yml",
    "governance": "SoT/rules/governance.yml"
  }
}
```

> **Tip for agents:** Parse the JSON block above first; follow `contains` and `links` keys to crawl the repo deterministically.

---

## Quick Links

* **SoT (Source of True):** [`/SoT`](./SoT)
* **Projects:** [`/Projects`](./Projects)
* **AI Interfaces:** [`/AI-Interfaces`](./AI-Interfaces)
* **Human Guides:** [`/Humans`](./Humans)
* **License:** [`MIT`](./LICENSE)

---

## What this repo is

**The Map** of the Space Empire ecosystem. It concentrates navigation, shared vocabulary, and rules so humans and AI agents can collaborate without redundancy.

### Designed for

* **AI & automation:** deterministic files (`.json`, `.yaml`) to index and act on.
* **Humans:** clear, short pages (`.md`) with links, summaries, and decisions.

### You can use this to

* Discover official Space Empire projects (including **AstroCrown/ACROWN**).
* Reuse content, structure, or processes in your own initiatives.
* Build agents that read SoT files and automate tasks (e.g., syncing dashboards, generating docs, etc.).

---

## Repository Layout

```
SpaceEmpire-Directory-V1/
│
├── SoT/                         # 📖 Source of True (AI-first knowledge base)
│   ├── index.json               # Master index for AI parsing (ontology)
│   ├── glossary.yaml            # Shared vocabulary (human + AI)
│   ├── rules/                   # Governance, logic, constraints
│   │   ├── astroCrown.yml       # Economic/financial rules of ACROWN
│   │   ├── governance.yml       # Human/AI governance rules
│   │   └── ethics.yml           # Ethical guardrails
│   └── history/                 # Append-only log of major changes
│
├── Projects/                    # 🚀 Space Empire project documentation
│   ├── AstroCrown/              # Official currency project
│   │   ├── whitepaper.md
│   │   ├── roadmap.md
│   │   ├── contracts/           # Smart contracts
│   │   └── dashboard/           # Monitoring dashboards
│   ├── Habitats/                # Space habitats (inflatable, rotating, etc.)
│   │   └── design-specs.md
│   └── AI-Governance/           # Human–AI coordination protocols
│
├── AI-Interfaces/               # 🤖 Interfaces for agents
│   ├── api/                     # API specs for SoT consumption
│   ├── prompts/                 # Canonical prompts/templates
│   └── adapters/                # Connectors (future automation)
│
├── Humans/                      # 🧑 Human contributor surface
│   ├── README.md                # Where people start
│   ├── contribution-guide.md
│   ├── decisions.md             # Key choices & rationale
│   └── manifest.md              # Mission & credit philosophy
│
└── LICENSE                      # MIT
```

---

## Contributing (Humans & AIs)

* **Open a PR** with small, focused changes. Keep files short and scannable.
* Prefer **structured** changes: update `SoT/index.json`, `glossary.yaml`, or `rules/*.yml` along with any `.md` explainer.
* For **breaking changes**, propose in `Humans/decisions.md` first.

> **Style:**
>
> * Clear headings, short paragraphs, bullets.
> * Front-load key information at the top of each file.
> * Link out rather than duplicate.

---

## Credit & Use Policy (Project Norms)

* **Credit appreciated, not enforced.** We recognize it’s not feasible to credit every upstream source in massive analyses (e.g., Monte Carlo with billions of parameters). Use this repo freely and responsibly.
* **No exclusivity claims.** Do not present this work as exclusively yours. Fork, remix, and build—without enclosure.
* These norms express intent and culture. The legal license is **MIT** (see below).

---

## License

* **MIT License** for clarity, adoption, and compatibility.
* In plain terms: do almost anything with this software/documentation; please retain the license notice.

> **Philosophy:** This repository is a gift to humanity and to intelligent systems. Where attribution is impractical, **good-faith use** is still welcome.

---

## Governance & Safety

* See `SoT/rules/governance.yml` for decision pathways and roles.
* See `SoT/rules/ethics.yml` for ethical constraints and allowed use.
* Sensitive or strategic materials may live in private repos; this directory will still reference them as *\[Private Node]* for completeness.

---

## Roadmap (High-level)

* Populate `SoT/index.json` with canonical references.
* Publish `SoT/glossary.yaml` and minimum ruleset.
* Add `AI-Interfaces/prompts/` starter pack for agent orchestration.
* Link out to AstroCrown (ACROWN) repos and dashboards.

---

## Contact

* Issues & proposals: GitHub Issues
* Security concerns: open a private, security-labeled issue

---

> **Version:** 1.0.0
> **Status:** Public, actively curated

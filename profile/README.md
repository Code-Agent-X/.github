# Code Agent X

Organization building tools to design, build, and ship Japanese landing pages and related web experiences.

**Engineering standards (read first):** [engineering-standards](https://github.com/Code-Agent-X/engineering-standards) — golden paths, Doppler, README shape, self-audit checklists.

**New repositories:** use [org-template](https://github.com/Code-Agent-X/org-template) when available.

---

## How we work

- Standards are **guidance**, not automatic refactors of existing code.
- Each repo owner maintains their own README and optional `docs/COMPLIANCE.md`.
- Team leads do **not** open PRs into member repos' application source (`frontend/`, `backend/`, etc.) for standards adoption.

---

## Repositories

| Repository | Stack | Purpose | Notes |
| --- | --- | --- | --- |
| [engineering-standards](https://github.com/Code-Agent-X/engineering-standards) | Docs | Org handbook, checklists, templates | **Pin this repo** |
| [org-template](https://github.com/Code-Agent-X/org-template) | TS + Python | Scaffold for new monorepos | New repos only |
| [.github](https://github.com/Code-Agent-X/.github) | Docs | Organization profile (this page) | |
| [Agent-Prototype](https://github.com/Code-Agent-X/Agent-Prototype) | Python + TypeScript | LP coding agent prototype | |
| [LPAgent_Prototype](https://github.com/Code-Agent-X/LPAgent_Prototype) | — | JP website builder MVP (LP) | |
| [sitegraph](https://github.com/Code-Agent-X/sitegraph) | Node + React | Archive, reconstruct, template extraction from LPs | |
| [TemplateGen](https://github.com/Code-Agent-X/TemplateGen) | — | Template + metadata from raw websites | |
| [Vector-Builder](https://github.com/Code-Agent-X/Vector-Builder) | HTML / Python | KB patterns and vector ingest | |
| [ChromaUI](https://github.com/Code-Agent-X/ChromaUI) | TypeScript | Chroma index explorer UI | |
| [Docs](https://github.com/Code-Agent-X/Docs) | Notebooks / docs | Shared project documentation | |
| [prompt-metadata-matcher](https://github.com/Code-Agent-X/prompt-metadata-matcher) | — | Prompt / metadata matching | |
| [Notebooks](https://github.com/Code-Agent-X/Notebooks) | Jupyter | Colab / model notebooks | |

Update this table when adding repos (PR to `.github` only).

---

## Contributing

1. Read [engineering-standards](https://github.com/Code-Agent-X/engineering-standards).  
2. For your repo: copy [COMPLIANCE.template.md](https://github.com/Code-Agent-X/engineering-standards/blob/main/docs/checklists/COMPLIANCE.template.md) to `docs/COMPLIANCE.md`.  
3. Open a PR in **your** repository (docs/README changes are enough).  

Issues and discussions welcome in the handbook repo.

---

## Links

- [GitHub organization](https://github.com/Code-Agent-X)
- [Engineering standards](https://github.com/Code-Agent-X/engineering-standards)

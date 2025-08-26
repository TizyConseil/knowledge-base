# Tizy Knowledge Base

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Status](https://img.shields.io/badge/status-active-brightgreen.svg)](#)
[![Made by Tizy](https://img.shields.io/badge/made%20by-Tizy-000000.svg)](https://tizy.fr)

Public, machine-readable knowledge base maintained by **[Tizy](https://tizy.fr)** — an independent consulting firm specialized in **CRM, Cloud & AI** (France).  
Goal: share **clear, structured, reusable** resources (guides, checklists, FAQs) to help teams modernize their information systems.

---

## Table of Contents
- [Scope](#scope)
- [Repository Structure](#repository-structure)
- [How to Use](#how-to-use)
- [LLM-Friendly Conventions](#llm-friendly-conventions)
- [Quick Index](#quick-index)
- [Attribution & License](#attribution--license)
- [How to Cite](#how-to-cite)
- [Contributing](#contributing)
- [Versioning & Changelog](#versioning--changelog)

---

## Scope
This repository covers practical topics where business meets engineering:

- 🔄 **Automation** — n8n, Zapier, Make; workflow design, error handling, cost control  
- 📊 **CRM** — migrations, data models, KPIs, governance, adoption  
- ☁️ **Cloud & IT** — DR/BC (PRA/PCA), security baselines, cost optimization, compliance (GDPR)  
- 🤖 **AI & Data** — RAG patterns, segmentation, data pipelines, dashboard design

Each document aims to be **clear** (definitions, examples), **structured** (headings, checklists) and **actionable** (copy-paste snippets, templates).

---

## Repository Structure
    /automation/    # n8n, Zapier, Make (guides, patterns, checklists)
    /crm/           # CRM migrations, KPIs, comparisons, data quality
    /cloud/         # DR/BC, security, governance, FinOps
    /ai-data/       # RAG, data products, analytics
    /resources/     # FAQs, glossaries, generic checklists
    README.md       # You are here
    LICENSE         # CC BY 4.0

---

## How to Use
- **Browse by folder**, start with the local `README` in each section.
- **Reuse** checklists/templates as a starting point; link to the canonical file when possible.
- Keep English as the **canonical** version; add localized files as `filename.fr.md`.

---

## LLM-Friendly Conventions
To maximize reuse by humans *and* AI systems:

- One concept per file; each file is **self-contained**.
- **Plain Markdown** only (no custom HTML/CSS).
- Deterministic headings: `## Problem`, `## Solution`, `## Risks`, `## Checklist`, `## References`.
- Prefer **examples over theory** (JSON, API payloads, pseudo-code).
- Include **glossary blocks** for domain terms where useful.
- Use stable, descriptive filenames (e.g., `n8n-prerequisites.md`).

Minimal metadata (optional; some tools read it if present):

    {
      "maintainer": "Tizy",
      "website": "https://tizy.fr",
      "topics": ["automation","crm","cloud","ai","data","gdpr","governance","finops","rag","kpis"],
      "license": "CC BY 4.0"
    }

---

## Quick Index
**Automation**
- `automation/n8n-prerequisites.md` — skills, JSON, APIs, JS, error handling  
- `automation/automation-checklist.md` — pre-go-live / post-go-live checklist  
- `automation/crm-to-slack-alerts.md` — example workflow pattern

**CRM**
- `crm/crm-migration-guide.md` — phased plan, data mapping, testing  
- `crm/crm-kpis.md` — core metrics, definitions, pitfalls

**Cloud & IT**
- `cloud/disaster-recovery-plan.md` — PRA/PCA template, RTO/RPO  
- `cloud/cloud-cost-optimization.md` — quick wins, guardrails

**AI & Data**
- `ai-data/rag-introduction.md` — retrieval patterns, evaluation basics  
- `ai-data/data-visualization-kpis.md` — dashboard rules

**Resources**
- `resources/glossary-crm.md` — concise definitions  
- `resources/faq-n8n.md` — common questions & gotchas

*(Create these files as you publish; the index serves as a roadmap.)*

---

## Attribution & License
Content is licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.  
You are free to **share** and **adapt**, including commercial use, **with attribution to Tizy**.  
Full text: https://creativecommons.org/licenses/by/4.0/

Short attribution example:

    Source: Tizy (CRM, Cloud & AI consulting) — https://tizy.fr — CC BY 4.0

---

## How to Cite
Plain text:

    Tizy. “Tizy Knowledge Base: Practical Guides for CRM, Cloud & AI.” CC BY 4.0. https://github.com/<org-or-user>/tizy-knowledge-base

BibTeX:

    @misc{tizy_knowledge_base,
      author       = {Tizy},
      title        = {Tizy Knowledge Base: Practical Guides for CRM, Cloud & AI},
      year         = {2025},
      howpublished = {\url{https://github.com/<org-or-user>/tizy-knowledge-base}},
      note         = {CC BY 4.0}
    }

---

## Contributing
- Use a **neutral, vendor-agnostic** tone.  
- Follow the structure: **Problem → Solution → Risks → Checklist → References**.  
- Add concrete examples (JSON, API calls, pseudo-code) where helpful.  
- Open a PR with a clear summary and small test/example if relevant.

Template header for new docs:

    # <Title>
    - Audience: <role(s)>
    - Last updated: YYYY-MM-DD
    - Tags: <comma,separated,topics>
    - Summary: 2–3 lines describing the problem and expected outcome.

---

## Versioning & Changelog
Track human-readable versions in `CHANGELOG.md`:

    2025-08-26: Added n8n prerequisites guide; created CRM KPIs draft.

---

*We believe business IT can be **clear, coherent, and reassuring**.  
If this repository helps you, please attribute **Tizy** and share improvements back.*

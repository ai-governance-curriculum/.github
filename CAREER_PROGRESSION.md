# Career Progression Guide — AI Governance

A career-ladder guide for the discipline of **governing, securing, and assuring AI** — the people who make sure AI systems are safe, compliant, well-managed, and trustworthy. This org sits alongside three sibling curricula that build and run AI; AI Governance is the discipline that holds all of them accountable.

## Career Ladder Overview

The diagram below shows the **target** governance ladder. Only two rungs are built today; everything else is planned roadmap.

```
                          ┌─────────────────────────────┐
              L70   ──►   │  Chief AI Officer            │  [BUILT: scaffolded]
                          └─────────────────────────────┘
                                       ▲
              L60   ──►   Head of AI Governance              (planned)
                                       ▲
              L50   ──►   Senior AI Governance / Risk Architect  (planned)
                                       ▲
              L35   ──►   ┌─────────────────────────────┐
                          │ AI/ML Security & Governance  │  [BUILT: authored]
                          │ Engineer                     │
                          └─────────────────────────────┘
                                       ▲
              L25   ──►   AI Risk Engineer                   (planned)
                                       ▲
              L15   ──►   AI Governance Analyst              (planned)

   Security specialist branch (all planned):
     AI/ML Security Engineer → Senior AI Security Engineer
       → AI Security Architect → Head of AI Security

   Specializations on the roadmap (planned):
     • AI Evaluation Engineer
     • Agentic Safety / Red-Team Engineer
```

Legend: **[BUILT: authored]** = full curriculum exists. **[BUILT: scaffolded]** = repos exist, curriculum not yet written. **(planned)** = on the roadmap, no repo yet.

## What Exists Today

Be clear-eyed: this org currently ships **two** tracks, each a paired `-learning` + `-solutions` repo.

- **AI/ML Security & Governance Engineer (L35) — authored.** A complete curriculum (transferred into this org). It teaches infrastructure and ML-system security framed as a governance discipline: threat modeling, model and supply-chain security, secrets, access control, and the controls that satisfy governance frameworks. Historically this role was titled "AI Infrastructure Security Engineer"; in the governance org we treat it conceptually as **AI/ML Security & Governance Engineer**.
- **Chief AI Officer (L70) — scaffolded only.** The repos exist, but the curriculum has **not** yet been authored. Listed here so the top of the ladder is visible, not because content is ready.

Every other rung named in this guide is **planned**, not built.

## Level Descriptions

### AI Governance Analyst (L15) — *planned*

- **Responsibilities:** Maintain risk registers, model inventories, and intake/triage of new AI use cases. Map systems to applicable frameworks and flag gaps.
- **Representative work:** Drafting model cards, completing impact assessments, tracking control evidence, supporting audit prep.
- **Depth:** Working literacy in **NIST AI RMF** and **EU AI Act** risk tiers; able to read a system design and identify where governance obligations attach.

### AI Risk Engineer (L25) — *planned*

- **Responsibilities:** Operationalize risk controls — turn policy into testable, monitored requirements. Own portions of the risk register and remediation tracking.
- **Representative work:** Building control-testing pipelines, defining risk acceptance criteria, instrumenting models for monitoring/drift, writing remediation plans.
- **Depth:** **NIST AI RMF** functions end to end; quantitative and qualitative risk scoring; comfort bridging engineering teams and compliance.

### AI/ML Security & Governance Engineer (L35) — *built (authored)*

- **Responsibilities:** Secure AI/ML platforms and pipelines, and make those controls auditable against governance frameworks.
- **Representative work:** Threat modeling ML systems (training, serving, agentic flows); model and supply-chain security (provenance, signing, SBOMs); secrets management; identity and access control; hardening infrastructure that hosts models.
- **Depth:** STRIDE/attack-tree threat modeling, ML-specific attack surfaces (poisoning, extraction, prompt injection), secrets/KMS, IAM, and mapping technical controls to **ISO/IEC 42001** and **NIST AI RMF** evidence. This is the org's anchor curriculum.

### Senior AI Governance / Risk Architect (L50) — *planned*

- **Responsibilities:** Design the governance and assurance architecture for an organization's AI estate. Set standards that scale across teams.
- **Representative work:** Authoring control frameworks, designing **AI management systems (ISO/IEC 42001)**, defining audit and evaluation gates, advising on EU AI Act conformity.
- **Depth:** Architect-level fluency across NIST AI RMF, ISO/IEC 42001, and EU AI Act; able to reconcile competing frameworks into one operating model.

### Head of AI Governance (L60) — *planned*

- **Responsibilities:** Own the governance function. Accountable for policy, audit posture, regulatory readiness, and cross-functional governance operations.
- **Representative work:** Standing up governance committees, owning the audit relationship, reporting risk posture to leadership, setting org-wide AI policy.
- **Depth:** Program leadership plus regulatory strategy; translates legal/regulatory pressure into operating programs.

### Chief AI Officer (L70) — *built (scaffolded only)*

- **Responsibilities:** Board-level accountability for AI strategy, value, and risk. The buck stops here for safe and effective AI adoption.
- **Representative work:** Setting enterprise AI strategy and investment, owning the risk/reward narrative to the board, signing off on high-risk deployments.
- **Depth:** Executive AI leadership — portfolio strategy, governance, regulatory landscape, and organizational change. **Curriculum not yet authored.**

## Skills Matrix by Level

| Skill Area | Analyst (L15) | Engineer (L35) | Architect (L50) | Head (L60) | CAIO (L70) |
|---|---|---|---|---|---|
| **Security** | Aware of AI attack surfaces | Owns threat modeling, model & supply-chain security, secrets, IAM | Sets security architecture & standards | Owns security program posture | Accountable to board |
| **Risk & Compliance** | Maintains registers & assessments | Operationalizes & tests controls | Designs control frameworks | Owns audit & regulatory readiness | Sets risk appetite |
| **Policy & Frameworks** | Reads NIST AI RMF / EU AI Act | Maps controls to ISO 42001 / NIST | Authors policy & AI mgmt systems | Owns org-wide policy | Sets enterprise stance |
| **Evaluation & Assurance** | Completes impact assessments | Instruments eval/monitoring gates | Designs assurance architecture | Owns assurance program | Demands evidence for sign-off |
| **Leadership** | Individual contributor | Tech lead / cross-team | Architect / influencer | Function head | Executive / board |

## Compensation Ranges (United States, 2026)

Total compensation (base + bonus + equity). Ranges vary widely by region, company stage, sector (regulated finance/health pays more), and whether the role is security-weighted.

| Level | Role | Total Comp (USD) |
|---|---|---|
| L15 | AI Governance Analyst | ~$110k – $160k |
| L25 | AI Risk Engineer | ~$140k – $190k |
| L35 | AI/ML Security & Governance Engineer | ~$160k – $230k |
| L50 | Senior AI Governance / Risk Architect | ~$200k – $300k |
| L60 | Head of AI Governance | ~$250k – $400k+ |
| L70 | Chief AI Officer | ~$400k – $800k+ |

Note: AI security and governance entry roles realistically start around **$140–200k**; the **CAIO** band ($400k–800k+) skews higher at large or regulated enterprises and is highly variable.

## Promotion Criteria

- **Analyst → Risk Engineer (L15→L25):** Move from documenting risk to operationalizing it — own controls that are tested and monitored, not just recorded.
- **Risk Engineer → Security & Governance Engineer (L25→L35):** Demonstrate hands-on security depth (threat modeling, model/supply-chain security, secrets, IAM) and tie those controls to framework evidence.
- **Engineer → Architect (L35→L50):** Shift from securing systems to designing the standards and AI management systems that others build against.
- **Architect → Head of Governance (L50→L60):** Move from architecture to owning a function — program, audit, and regulatory accountability.
- **Head → CAIO (L60→L70):** Move from owning governance to owning enterprise AI strategy and board-level accountability for value and risk.

## Learning Paths

Only the two built tracks are usable today.

1. **Start with AI/ML Security & Governance Engineer (authored).** Work through `security-learning`, attempting exercises and projects before consulting `security-solutions`. This is the org's anchor and covers the technical-governance foundation (threat modeling, model/supply-chain security, secrets, access control) that every higher rung assumes.
2. **Preview the Chief AI Officer track (scaffolded).** The `chief-ai-officer-*` repos exist but contain no authored curriculum yet — use them to track the executive-leadership endpoint, not as study material.

Everything between Analyst and Architect, and the specialist branches, is **forthcoming**. Until then, supplement with the primary frameworks themselves: NIST AI RMF, ISO/IEC 42001, and the EU AI Act.

## Specialist Tracks

All specialist tracks below are **planned** — none are built yet.

- **Security branch (planned):** AI/ML Security Engineer → Senior AI Security Engineer → AI Security Architect → Head of AI Security. A deeper, security-only progression for those who want to specialize rather than broaden into general governance.
- **AI Evaluation Engineer (planned):** Designs and runs rigorous evaluations of model capability, safety, and compliance — turning assurance claims into measured evidence.
- **Agentic Safety / Red-Team Engineer (planned):** Adversarially tests agentic and autonomous AI systems — red-teaming, jailbreak/abuse testing, and safety-case construction for agent deployments.

## Repository Map

All repos live under `https://github.com/ai-governance-curriculum/`.

| Level | Role | Repo | Status |
|---|---|---|---|
| L35 | AI/ML Security & Governance Engineer | [security-learning](https://github.com/ai-governance-curriculum/security-learning) | Authored |
| L35 | AI/ML Security & Governance Engineer | [security-solutions](https://github.com/ai-governance-curriculum/security-solutions) | Authored |
| L70 | Chief AI Officer | [chief-ai-officer-learning](https://github.com/ai-governance-curriculum/chief-ai-officer-learning) | Scaffolded / in development |
| L70 | Chief AI Officer | [chief-ai-officer-solutions](https://github.com/ai-governance-curriculum/chief-ai-officer-solutions) | Scaffolded / in development |

## The AI Career Curriculum Ecosystem

AI Governance is one of four sibling orgs. The other three **build and run** AI; this org **assures, secures, and governs** across all of them.

- [**AI Infrastructure**](https://github.com/ai-infra-curriculum) — run the platforms that serve and scale AI.
- [**ML Engineering**](https://github.com/ml-engineering-curriculum) — build and train the models.
- [**AI Engineering**](https://github.com/ai-engineering-curriculum) — build applications **with** models.
- **AI Governance** (this org) — secure, evaluate, and govern everything the other three produce.

---

<!-- aicg:maintained-by -->
Maintained by [VeriSwarm.ai](https://veriswarm.ai)

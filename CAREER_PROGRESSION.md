# Career Progression Guide — AI Governance

A career-ladder guide for the discipline of **governing, securing, and assuring AI** — the people who make sure AI systems are safe, compliant, well-managed, and trustworthy. This org sits alongside four sibling curricula that build, run, and commercialize AI; AI Governance is the discipline that holds all of them accountable.

## Career Ladder Overview

All eight rungs of the governance ladder have authored learning content. Reference solutions are complete for two tracks and in progress for the rest.

```
              L70   ──►   Chief AI Officer                       [learning + solutions]
                                       ▲
              L60   ──►   Head of AI Governance                  [learning]
                                       ▲
              L50   ──►   Senior AI Governance / Risk Architect  [learning]
                                       ▲
              L40   ──►   Agentic Safety & Red-Team Engineer     [learning]
                                       ▲
              L35   ──►   AI/ML Security & Governance Engineer   [learning + solutions]
                          AI Evaluation Engineer                 [learning]
                                       ▲
              L25   ──►   AI Risk Engineer                       [learning]
                                       ▲
              L15   ──►   AI Governance Analyst                  [learning]

   Security specialist branch (planned):
     AI/ML Security Engineer → Senior AI Security Engineer
       → AI Security Architect → Head of AI Security
```

Legend: **[learning + solutions]** = authored curriculum and complete reference solutions. **[learning]** = authored curriculum; reference solutions in progress. **(planned)** = on the roadmap, no repo yet.

## What Exists Today

This org ships **eight** role tracks, each a paired `-learning` + `-solutions` repo.

- **Complete (learning + solutions):** AI/ML Security & Governance Engineer (L35) and Chief AI Officer (L70). The security track was transferred into this org; historically it was titled "AI Infrastructure Security Engineer", and here it is framed as **AI/ML Security & Governance Engineer**.
- **Learning authored, solutions in progress:** AI Governance Analyst (L15), AI Risk Engineer (L25), AI Evaluation Engineer (L35), Agentic Safety & Red-Team Engineer (L40), Senior AI Governance / Risk Architect (L50), and Head of AI Governance (L60). Each has 10–13 authored modules; the paired solutions repos are filled in by the curriculum pipeline over time.

Only the security specialist branch is still **planned**.

## Level Descriptions

### AI Governance Analyst (L15) — *learning authored*

- **Responsibilities:** Maintain risk registers, model inventories, and intake/triage of new AI use cases. Map systems to applicable frameworks and flag gaps.
- **Representative work:** Drafting model cards, completing impact assessments, tracking control evidence, supporting audit prep.
- **Depth:** Working literacy in **NIST AI RMF** and **EU AI Act** risk tiers; able to read a system design and identify where governance obligations attach.

### AI Risk Engineer (L25) — *learning authored*

- **Responsibilities:** Operationalize risk controls — turn policy into testable, monitored requirements. Own portions of the risk register and remediation tracking.
- **Representative work:** Building control-testing pipelines, defining risk acceptance criteria, instrumenting models for monitoring/drift, writing remediation plans.
- **Depth:** **NIST AI RMF** functions end to end; quantitative and qualitative risk scoring; comfort bridging engineering teams and compliance.

### AI/ML Security & Governance Engineer (L35) — *complete*

- **Responsibilities:** Secure AI/ML platforms and pipelines, and make those controls auditable against governance frameworks.
- **Representative work:** Threat modeling ML systems (training, serving, agentic flows); model and supply-chain security (provenance, signing, SBOMs); secrets management; identity and access control; hardening infrastructure that hosts models.
- **Depth:** STRIDE/attack-tree threat modeling, ML-specific attack surfaces (poisoning, extraction, prompt injection), secrets/KMS, IAM, and mapping technical controls to **ISO/IEC 42001** and **NIST AI RMF** evidence. This is the org's anchor curriculum.

### AI Evaluation Engineer (L35) — *learning authored*

- **Responsibilities:** Turn assurance claims into evidence a regulator, auditor, or customer will accept, and gate releases on it.
- **Representative work:** Building assurance cases, designing release-gate architecture, running evaluation evidence pipelines, writing model and system cards for external audiences, mapping obligations across jurisdictions and regulated sectors.
- **Depth:** Evaluation as an assurance discipline — evidence quality, deployment-tier gating, and sector-specific assurance expectations.

### Agentic Safety & Red-Team Engineer (L40) — *learning authored*

- **Responsibilities:** Adversarially test agentic and autonomous AI systems and contain what they can do.
- **Representative work:** Agent threat modeling, prompt-injection and jailbreak engineering, mapping the agent attack surface, dangerous-capability evaluations, containing excessive agency, and frontier guardrails.
- **Depth:** Frontier safety frameworks and red-team practice applied to tool-using, autonomous agents.

### Senior AI Governance / Risk Architect (L50) — *learning authored*

- **Responsibilities:** Design the governance and assurance architecture for an organization's AI estate. Set standards that scale across teams.
- **Representative work:** Authoring control frameworks, designing **AI management systems (ISO/IEC 42001)**, defining audit and evaluation gates, advising on EU AI Act conformity.
- **Depth:** Architect-level fluency across NIST AI RMF, ISO/IEC 42001, and EU AI Act; able to reconcile competing frameworks into one operating model.

### Head of AI Governance (L60) — *learning authored*

- **Responsibilities:** Own the governance function. Accountable for policy, audit posture, regulatory readiness, and cross-functional governance operations.
- **Representative work:** Standing up governance committees, owning the audit relationship, reporting risk posture to leadership, setting org-wide AI policy.
- **Depth:** Program leadership plus regulatory strategy; translates legal/regulatory pressure into operating programs.

### Chief AI Officer (L70) — *complete*

- **Responsibilities:** Board-level accountability for AI strategy, value, and risk. The buck stops here for safe and effective AI adoption.
- **Representative work:** Setting enterprise AI strategy and investment, owning the risk/reward narrative to the board, signing off on high-risk deployments.
- **Depth:** Executive AI leadership — regulatory landscape, AI risk frameworks, model risk management, responsible AI, trust architecture, AI security, audit evidence, compliance operations, incident response, and board reporting.

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

AI Evaluation Engineer and Agentic Safety & Red-Team Engineer are not yet benchmarked here.

Note: AI security and governance entry roles realistically start around **$140–200k**; the **CAIO** band ($400k–800k+) skews higher at large or regulated enterprises and is highly variable.

## Promotion Criteria

- **Analyst → Risk Engineer (L15→L25):** Move from documenting risk to operationalizing it — own controls that are tested and monitored, not just recorded.
- **Risk Engineer → Security & Governance Engineer (L25→L35):** Demonstrate hands-on security depth (threat modeling, model/supply-chain security, secrets, IAM) and tie those controls to framework evidence.
- **Engineer → Architect (L35→L50):** Shift from securing systems to designing the standards and AI management systems that others build against.
- **Architect → Head of Governance (L50→L60):** Move from architecture to owning a function — program, audit, and regulatory accountability.
- **Head → CAIO (L60→L70):** Move from owning governance to owning enterprise AI strategy and board-level accountability for value and risk.

## Learning Paths

1. **Start at your level.** New to governance: **AI Governance Analyst** → **AI Risk Engineer**. Coming from security or infrastructure: start with **AI/ML Security & Governance Engineer**, the org's most complete track.
2. **Pick an assurance specialty at L35–L40.** **AI Evaluation Engineer** for release assurance and evidence; **Agentic Safety & Red-Team Engineer** for adversarial testing of agents.
3. **Move into architecture and leadership.** **Senior AI Governance / Risk Architect** → **Head of AI Governance** → **Chief AI Officer**.

In each track, attempt the exercises in the `-learning` repo before consulting the paired `-solutions` repo. Where solutions are still in progress, check your work against the primary frameworks: NIST AI RMF, ISO/IEC 42001, and the EU AI Act.

## Specialist Tracks

- **AI Evaluation Engineer (L35) — available.** See the level description above.
- **Agentic Safety & Red-Team Engineer (L40) — available.** See the level description above.
- **Security branch (planned):** AI/ML Security Engineer → Senior AI Security Engineer → AI Security Architect → Head of AI Security. A deeper, security-only progression for those who want to specialize rather than broaden into general governance.

## Repository Map

All repos live under `https://github.com/ai-governance-curriculum/`.

| Level | Role | Learning | Solutions | Status |
|---|---|---|---|---|
| L15 | AI Governance Analyst | [ai-governance-analyst-learning](https://github.com/ai-governance-curriculum/ai-governance-analyst-learning) | [ai-governance-analyst-solutions](https://github.com/ai-governance-curriculum/ai-governance-analyst-solutions) | Learning authored · solutions in progress |
| L25 | AI Risk Engineer | [ai-risk-engineer-learning](https://github.com/ai-governance-curriculum/ai-risk-engineer-learning) | [ai-risk-engineer-solutions](https://github.com/ai-governance-curriculum/ai-risk-engineer-solutions) | Learning authored · solutions in progress |
| L35 | AI Evaluation Engineer | [ai-evaluation-engineer-learning](https://github.com/ai-governance-curriculum/ai-evaluation-engineer-learning) | [ai-evaluation-engineer-solutions](https://github.com/ai-governance-curriculum/ai-evaluation-engineer-solutions) | Learning authored · solutions in progress |
| L35 | AI/ML Security & Governance Engineer | [security-learning](https://github.com/ai-governance-curriculum/security-learning) | [security-solutions](https://github.com/ai-governance-curriculum/security-solutions) | Complete |
| L40 | Agentic Safety & Red-Team Engineer | [agentic-safety-engineer-learning](https://github.com/ai-governance-curriculum/agentic-safety-engineer-learning) | [agentic-safety-engineer-solutions](https://github.com/ai-governance-curriculum/agentic-safety-engineer-solutions) | Learning authored · solutions in progress |
| L50 | Senior AI Governance / Risk Architect | [senior-ai-governance-architect-learning](https://github.com/ai-governance-curriculum/senior-ai-governance-architect-learning) | [senior-ai-governance-architect-solutions](https://github.com/ai-governance-curriculum/senior-ai-governance-architect-solutions) | Learning authored · solutions in progress |
| L60 | Head of AI Governance | [head-of-ai-governance-learning](https://github.com/ai-governance-curriculum/head-of-ai-governance-learning) | [head-of-ai-governance-solutions](https://github.com/ai-governance-curriculum/head-of-ai-governance-solutions) | Learning authored · solutions in progress |
| L70 | Chief AI Officer | [chief-ai-officer-learning](https://github.com/ai-governance-curriculum/chief-ai-officer-learning) | [chief-ai-officer-solutions](https://github.com/ai-governance-curriculum/chief-ai-officer-solutions) | Complete |

## The AI Career Curriculum Ecosystem

AI Governance is one of five sibling orgs. Three **build and run** AI, one turns it into a company, and this org **assures, secures, and governs** across all of them.

- [**AI Infrastructure**](https://github.com/ai-infra-curriculum) — run the platforms that serve and scale AI.
- [**ML Engineering**](https://github.com/ml-engineering-curriculum) — build and train the models.
- [**AI Engineering**](https://github.com/ai-engineering-curriculum) — build applications **with** models.
- [**AI Startup**](https://github.com/ai-startup-curriculum) — turn it into a company.
- **AI Governance** (this org) — secure, evaluate, and govern everything the others produce.

---

<!-- aicg:maintained-by -->
Maintained by [VeriSwarm.ai](https://veriswarm.ai)

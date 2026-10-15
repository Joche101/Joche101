# John Bianchina

**Forward Deployed Engineer** · Johannesburg, South Africa (remote, US hours)
I go into a business, map how the work actually flows, and build the system that runs it.

[pursuitreadiness.com](https://pursuitreadiness.com) · john@pursuitreadiness.com · [LinkedIn](https://www.linkedin.com/in/john-bianchina-88965078/)

---

## What I do

Most implementations fail not because the technology is hard, but because nobody mapped how the
work really happens before they started building. That mapping is the job.

I build systems where the deterministic parts stay deterministic, models are used only where
judgement is genuinely needed, and every outbound action passes a named human. The rule I hold on
every build: **the system can block, it can never send.**

Twenty years in sales and marketing before this, most recently as founder of Pursuit Readiness
(2023–present). That background is why I build for the person who has to use the thing on a
Tuesday afternoon, not for the demo.

---

## Selected work

### [ai-portfolio](https://github.com/Joche101/ai-portfolio) — governance layer for AI systems
A POPIA-compliant data protection framework that runs in production and underpins every system I
deploy. Three modules, each enforcing something that would otherwise depend on someone remembering:

- **`audit_trail.py`** — SHA-256 hash-chained event logging with tamper-evident verification. Every
  PII operation recorded with UUID, timestamp, actor, resource, action and trace ID.
- **`consent.py`** — scope-based consent registry with capture, persistence and runtime enforcement.
  PII operations check consent before execution.
- **`hitl.py`** — human-in-the-loop approval gates for data access, deletion, correction,
  escalation and legal review. Mandatory, and not bypassable programmatically.

Built in 48 hours because a client needed POPIA guarantees before they would deploy. It turned out
to be reusable, so it now sits under every build.

### [LandD](https://github.com/Joche101/LandD) — fine-tuning and evaluation
Jupyter notebooks covering model fine-tuning and text evaluation. Live demo at
[land-d.vercel.app](https://land-d.vercel.app).

---

## Certifications and badges

**Salesforce Trailhead** — nine badges, October 2026 · [verify all nine](https://www.salesforce.com/trailblazer/ag4q9whpxc6alo8zss)
Data Modeling · Data Management · Data Quality · Reports & Dashboards for Lightning Experience ·
Business Rules Engine · Accessibility and AI Foundations · Variables and Field Types ·
Well-Structured Data · Data Literacy Basics

**GitHub** — GitHub Copilot, Developer Program Member

**Microsoft Azure** — Image analysis and generation with Azure AI

---

## How I work

- **Deterministic before agent.** If a rule can decide it, it is code, not a prompt.
- **A named human approves every send.** The system can block. It cannot send.
- **The receipt logs the doing, not the content.** Stage, actor, timestamp, request ID.
- **Measurement is computed from receipts**, never typed by hand.
- **I don't list a tool I can't demo live.**

---

*Currently open to forward-deployed engineering, solution architecture and AI implementation roles.*

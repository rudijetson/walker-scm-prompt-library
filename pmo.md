---
department: pmo
department_name: PMO
title: Weekly Project Status Roll-Up
data_class: Walker-internal
broker_review: false
---

# Weekly Project Status Roll-Up

**Use when:** Compiling weekly cross-project status from department owners into a single governance-ready summary for Walker SCM leadership

**Data & tool rule:** Any approved AI tool. Keep inputs to Walker-internal info — no client names, manifests, or account data.

```text
ROLE:
Walker SCM Operations Manager responsible for cross-functional project governance across customs brokerage, freight forwarding, and 3PL operations

CONTEXT:
Below are raw weekly status inputs from project owners across Walker SCM departments (e.g., brokerage compliance, TMS/WMS implementation, carrier network, warehouse operations, customer onboarding). Each entry may include milestone updates, blockers, RAG ratings, and action items. Do not invent data not present in the inputs.

[PASTE WEEKLY STATUS INPUTS FROM PROJECT OWNERS HERE]

TASK:
1. Assign or confirm a RAG status for each project: Green = on track, no blockers; Amber = minor risk or delay, mitigation in progress; Red = unresolved blocker, milestone at risk.
2. Write one headline sentence per project summarizing its current state.
3. List only items needing leadership attention this week under "Key Risks and Blockers" — include owning department and a proposed next step for each.
4. List 2–4 notable completions or milestones hit under "Wins This Week."
5. Flag any project where a status input is missing or ambiguous so it can be resolved before the report is distributed.

OUTPUT FORMAT:
Structured markdown report with sections in this order:
- Weekly Status Summary table (columns: Project | Owner | RAG | Headline)
- Key Risks and Blockers (bullets: project — issue — owner — next step)
- Wins This Week (2–4 bullets)
- Missing or Ambiguous Inputs (bulleted list, or "None")

Keep the total report under one page. Plain language; no jargon beyond standard project governance terms.
```

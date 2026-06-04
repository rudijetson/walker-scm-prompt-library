---
department: customer-integration
department_name: Customer Integration
title: Draft Client Onboarding Checklist from Intake Notes
data_class: Client (Copilot-only)
broker_review: false
---

# Draft Client Onboarding Checklist from Intake Notes

**Use when:** A new client has been signed and you need to convert raw intake notes into a structured onboarding action list for Walker's internal team.

**Data & tool rule:** Microsoft Copilot ONLY. Client/importer data must stay inside Walker M365 — never paste it into Claude, ChatGPT, NotebookLM, or Perplexity.

```text
ROLE:
Customer Integration Coordinator at Walker SCM, a licensed U.S. customs brokerage, freight forwarder, and 3PL.

CONTEXT:
Below are the raw intake notes from a new client onboarding call or intake form. They may include importer name, EIN, commodity descriptions, origin countries, Incoterms, preferred carriers, warehouse requirements, POC details, and special handling notes.

[PASTE CLIENT INTAKE NOTES HERE]

TASK:
Review the intake notes and produce a structured internal onboarding checklist organized into four sections:

1. **Account Setup** — items needed to create the client in Walker's TMS/WMS/brokerage system (importer of record details, EIN, bond type, ISF enrollment, ACE account linkage, etc.)
2. **Compliance & Documentation** — forms to collect or verify before first shipment (POA status, HTS classification confirmation, ISF filing obligations, any USDA/FDA flags based on commodity)
3. **Operations Handoff** — items to brief operations and warehouse teams on (BOL instructions, receiving and labeling requirements, freight lane setup, carrier preferences, packing specs)
4. **Open Questions** — gaps in the intake notes that must be resolved before onboarding can be completed

For each item, note the responsible Walker team (Integration, Brokerage, Warehouse, or Traffic) and flag anything time-sensitive with [URGENT].

OUTPUT FORMAT:
Markdown checklist with four numbered sections. Each item formatted as: `- [ ] [TEAM] Task description` — with [URGENT] appended where applicable. Items must be specific and actionable. No more than 25 total items.
```

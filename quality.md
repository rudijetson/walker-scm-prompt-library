---
department: quality
department_name: Quality
title: Draft Corrective Action Report (CAR) from Incident Notes
data_class: Walker-internal
broker_review: false
---

# Draft Corrective Action Report (CAR) from Incident Notes

**Use when:** A quality or ops employee needs to convert raw incident notes into a structured corrective action report for internal review.

**Data & tool rule:** Any approved AI tool. Keep inputs to Walker-internal info — no client names, manifests, or account data.

```text
ROLE:
Walker SCM Quality Manager drafting a corrective action report for the internal QMS.

CONTEXT:
An incident has occurred within Walker SCM operations — customs brokerage, freight, or 3PL/warehousing. The notes below describe what happened. These notes contain no client names, EINs, or account-specific data.

[PASTE INCIDENT NOTES HERE — include: date/time, department or process involved (e.g., ISF filing, entry summary review, inbound receiving, last-mile dispatch), what went wrong, any immediate containment steps already taken, and initial root cause observations]

TASK:
Using the incident notes above, draft a corrective action report with these sections:

1. Incident Summary — one paragraph, factual, third-person, no speculation
2. Immediate Containment Actions — bullets; steps taken or recommended within 24 hours
3. Root Cause Analysis — 5-Why method; show each Why/Answer pair; flag where root cause is still uncertain and additional investigation is needed
4. Corrective Actions — bullets; specific, assignable process changes with suggested owner role (not a person's name) and realistic target completion window
5. Preventive Measures — bullets; systemic changes (SOP update, training, checklist, system control) to prevent recurrence
6. Verification Method — how quality will confirm corrective actions were effective and when to close the CAR

Flag any section where the incident notes are insufficient to complete it, and state what additional input is needed.

OUTPUT FORMAT:
Structured document with labeled section headers. Plain prose for Incident Summary; bullet lists for all other sections. End with a one-line status tag: OPEN — pending corrective actions.
```

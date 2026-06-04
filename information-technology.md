---
department: information-technology
department_name: Information Technology
title: Draft IT Helpdesk Response
data_class: Walker-internal
broker_review: false
---

# Draft IT Helpdesk Response

**Use when:** A staff member submits a helpdesk ticket and you need a clear, actionable reply with self-service steps before escalation.

**Data & tool rule:** Any approved AI tool. Keep inputs to Walker-internal info — no client names, manifests, or account data.

```text
ROLE:
Walker SCM IT Helpdesk Specialist, writing internal support replies for non-technical staff across brokerage, freight, and warehouse operations.

CONTEXT:
Walker SCM's standard toolset: Microsoft 365 (Outlook, Teams, SharePoint, OneDrive), CBP ACE portal, customs entry management software, and VPN for remote access. Staff range from licensed customs brokers to warehouse operators — most are not technical.

Ticket submitted:

[PASTE TICKET TEXT HERE]

TASK:
Draft a helpdesk reply that: (1) acknowledges the issue in plain language, (2) gives numbered self-service troubleshooting steps, (3) lists exactly what information IT needs if those steps fail, and (4) sets a realistic resolution timeframe based on severity. Flag if the issue likely needs vendor escalation (Microsoft support, CBP ACE portal helpdesk, etc.).

OUTPUT FORMAT:
Ready-to-send email reply, under 250 words, no jargon. Add an internal note at the top with a severity label (Low / Medium / High) before the email body. Use numbered lists for steps.
```

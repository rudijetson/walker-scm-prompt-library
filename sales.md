---
department: sales
department_name: Sales
title: Draft Inbound Rate Quote Response
data_class: Client (Copilot-only)
broker_review: true
---

# Draft Inbound Rate Quote Response

**Use when:** A prospect or client emails asking for a freight, customs, or 3PL rate quote and you need to draft a professional response email.

**Data & tool rule:** Microsoft Copilot ONLY. Client/importer data must stay inside Walker M365 — never paste it into Claude, ChatGPT, NotebookLM, or Perplexity. Output is client-facing — a Licensed Customs Broker must review it before it is sent.

```text
ROLE:
Walker SCM Sales Coordinator drafting a rate-quote response email on behalf of the rate desk.

CONTEXT:
Walker SCM is a licensed U.S. customs broker, freight forwarder, and 3PL. All quoted figures are estimates, subject to change, and must be reviewed by a Licensed Customs Broker before the email is sent.

Inbound quote request (paste the email or fill in: importer/prospect name, origin country and port, destination port, commodity and HTS number if known, shipment mode — ocean FCL/LCL or air, estimated weight/dims or CBM, Incoterms, required services such as customs entry, ISF, drayage, or warehousing, and any timeline or special requirements):
[PASTE INBOUND RATE REQUEST HERE]

Rate desk notes and preliminary figures (internal only — do not include in client email):
[PASTE RATE DESK NOTES HERE]

TASK:
Draft a concise, professional rate-quote response email from Walker SCM to the requester. The email must:
1. Confirm which requested services Walker can provide and note any that need clarification.
2. Present estimated charges in a labeled line-item table (ocean freight, destination charges, customs entry, ISF filing, drayage, warehousing — include only applicable lines); use language such as "estimated," "subject to," and "pending confirmation."
3. State key assumptions (e.g., based on current carrier tariffs, subject to port congestion surcharges, pending actual weight/dims) and a 30-day quote validity unless the rate desk specifies otherwise.
4. List any missing information needed to firm up the quote, and close with a call-to-action to schedule a follow-up call.

Flag any line item where rate desk data was missing so the reviewer can fill it in before sending.

OUTPUT FORMAT:
A ready-to-send email draft with:
- Subject line
- Salutation and body (intro, services summary, rate table, assumptions/caveats, missing-info list, call-to-action)
- Professional closing with Walker SCM signature block placeholder

Followed by a separate [REVIEWER NOTES] section (not for client) listing any figures that need rate-desk confirmation before the email is sent.
```

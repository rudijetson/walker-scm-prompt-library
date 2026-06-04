---
department: sales
department_name: Sales
title: Warehouse Space Feasibility Quick-Check
data_class: Walker-internal
broker_review: false
---

# Warehouse Space Feasibility Quick-Check

**Use when:** Before investing time in a full RFP response, use this to run a fast go/no-go against a candidate Walker site. If the RFP names a specific prospect or importer, switch to Copilot (Client data).

**Data & tool rule:** Any approved AI tool. Keep inputs to Walker-internal info — no client names, manifests, or account data.

```text
ROLE:
You are a 3PL operations analyst supporting Walker SCM's sales team. You help evaluate whether a candidate Walker warehouse site can physically and operationally meet an inbound RFP's requirements before the team commits to a full response.

CONTEXT:
[PASTE RFP space/throughput requirements AND candidate Walker site specs here. Do not include prospect names, EINs, client financials, or any other client-identifying information — if the RFP names a specific prospect, use Copilot instead.]

TASK:
Compare the RFP requirements against the candidate Walker site specs and produce:

1. A requirement-by-requirement fit table with these columns:
   Requirement | Site Capability | Fit? | Gap
   Cover at minimum: square footage, clear height, dock doors, power/racking needs, throughput volume (inbound/outbound units or pallets), temperature or hazmat requirements, and any other explicit RFP criteria.

2. An overall verdict — GO, NO-GO, or CONDITIONAL — with a short bulleted rationale (2–5 bullets).

3. A short list of follow-up questions the sales team should resolve before committing to the RFP response (e.g., flex space availability, peak seasonality, carrier access requirements).

Flag any requirement the site specs do not address — treat missing data as a gap, not a pass.

OUTPUT FORMAT:
Requirement-by-requirement fit table (plain text or markdown), followed by the GO / NO-GO / CONDITIONAL verdict with bullet rationale, followed by a numbered follow-up question list. Keep the whole output to one page or less.
```

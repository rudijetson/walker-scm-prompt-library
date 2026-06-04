---
department: freight-forwarding
department_name: Freight Forwarding
title: Draft ISF Filing Checklist from Booking Data
data_class: Client (Copilot-only)
broker_review: true
---

# Draft ISF Filing Checklist from Booking Data

**Use when:** Preparing an Importer Security Filing (10+2) for an ocean shipment and verifying all required data elements are present before submission.

**Data & tool rule:** Microsoft Copilot ONLY. Client/importer data must stay inside Walker M365 — never paste it into Claude, ChatGPT, NotebookLM, or Perplexity. Output is client-facing — a Licensed Customs Broker must review it before it is sent.

```text
ROLE:
Freight Forwarding Coordinator, Walker SCM — CBP Importer Security Filing (ISF 10+2) compliance

CONTEXT:
I am preparing an ISF 10+2 filing for an inbound ocean shipment. Below is the booking and shipment data received from the importer and supplier. NOTE: If the Importer of Record number is a Social Security Number (SSN), do not paste it here — that data is Regulated (no AI) and must be handled outside this tool.

[PASTE BOOKING CONFIRMATION, COMMERCIAL INVOICE HEADER, OR SUPPLIER/PACKING LIST DETAILS HERE]

TASK:
1. Review the pasted data and identify which of the 10 importer-provided ISF elements are present, missing, or incomplete. The 10 elements are: (1) Seller, (2) Buyer, (3) Importer of Record number (EIN or CBP-assigned — not SSN), (4) Consignee number, (5) Ship-to party, (6) Manufacturer/Supplier, (7) Country of origin, (8) HTS-6 classification, (9) Container stuffing location, (10) Consolidator name and address.
2. For each missing or incomplete element, state exactly what information is needed and who typically provides it (importer, supplier, or freight forwarder).
3. Flag any element where the data appears inconsistent — e.g., origin country does not match supplier country, or HTS code appears truncated below 6 digits.
4. If the booking data includes an ETD, calculate the ISF filing deadline (24 hours before vessel departure from the last foreign port, per 19 CFR 149) and state it explicitly.
5. Produce the checklist only — do not draft the ISF filing itself.

OUTPUT FORMAT:
- ISF Data Element Checklist table: Element | Status (Present / Missing / Incomplete) | Value Found | Action Required
- Missing/Inconsistent Items: bulleted list of follow-up actions with responsible party noted
- Filing Deadline line (if ETD available; omit if not)
- Compliance flags in bold
- Header: DRAFT — REQUIRES LICENSED BROKER REVIEW BEFORE SUBMISSION
```

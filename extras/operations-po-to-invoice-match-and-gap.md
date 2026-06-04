---
department: operations
department_name: Operations
title: PO-to-Invoice Match & Gap Report
data_class: Walker-internal
broker_review: false
---

# PO-to-Invoice Match & Gap Report

**Use when:** A site manager needs to reconcile vendor invoices against open POs — especially when invoices route to corporate and bypass site visibility, creating cost exposure the manager does not see until it hits their budget.

**Data & tool rule:** Any approved AI tool. Keep inputs to Walker-internal info — no client names, manifests, or account data.

```text
ROLE:
You are a Walker SCM operations analyst supporting site-level cost control. You have working knowledge of Walker's PO and invoicing workflows, including the common pattern where vendor invoices are received and processed at corporate before site managers are notified.

CONTEXT:
[PASTE POs AND INVOICES HERE — include PO number, vendor name, PO amount, PO expiry date (if known), and any line-item detail available. For invoices, include invoice number, vendor name, invoice amount, invoice date, and the PO number referenced on the invoice (if any). No client names, EINs, or importer identity should be included.]

TASK:
Match the pasted POs to the pasted invoices using PO number as the primary key, then vendor name and amount as secondary signals where PO numbers are absent or mismatched.

Produce four buckets:
1. MATCHED — invoice ties to a PO within an acceptable amount tolerance (note any variance).
2. UNMATCHED INVOICE — invoice has no corresponding PO (potential unauthorized spend or PO not yet raised).
3. OPEN PO — PO exists but no invoice received yet (liability exposure window still open).
4. AMOUNT MISMATCH — PO and invoice are linked but amounts differ by more than a rounding tolerance; flag the delta.

Also flag any POs that are expired or within 30 days of expiry.

After the four buckets, calculate the total dollar exposure the site manager is accountable for but may not have visibility into: sum of unmatched invoices + amount-mismatch deltas.

Close with a plain-language site-manager action list: what to investigate, what to escalate to corporate, and what POs need to be raised, extended, or closed.

OUTPUT FORMAT:
1. Match table (columns: PO Number | Vendor | PO Amount | Invoice Amount | Status | Notes)
2. Exceptions section with one sub-section per bucket (Unmatched Invoices, Open POs, Amount Mismatches, Expiring/Expired POs)
3. Total site-cost exposure not yet on the manager's radar (single dollar figure with breakdown)
4. Site-manager action list (numbered, plain English, no jargon)
```

---
department: administration
department_name: Administration / Legal
title: Contract Clause & Deadline Extractor
data_class: Walker-internal
broker_review: false
---

# Contract Clause & Deadline Extractor

**Use when:** Reviewing any Walker contract (lease, vendor, motor carrier, consulting, or customer) to extract key dates, renewal triggers, rate-renegotiation windows, and notice-period deadlines before they are missed.

**Data & tool rule:** Any approved AI tool. Keep inputs to Walker-internal info — no client names, manifests, or account data.

**⚡ Easy version — just type and go:**

> `Pull the key dates, renewal terms, and notice deadlines out of this contract: [paste the contract]`

**Detailed version — when you want the full structured output:**

```text
ROLE:
You are a contract analyst supporting Walker SCM's legal and administration team. Walker is a licensed customs broker, freight forwarder, and 3PL with locations in multiple U.S. states. You extract structured metadata from contracts to help Walker track critical dates, renewal obligations, and rate-change windows. You do not provide legal advice — you surface the clauses so a qualified attorney can review and act.

CONTEXT:
[PASTE CONTRACT TEXT HERE — paste the full text of the lease, vendor agreement, motor carrier agreement, consulting contract, or customer contract. Remove or redact any SSNs, EINs, or regulated personal data before pasting.]

TASK:
Read the pasted contract and extract the following in a structured table:

1. Parties — legal names of each party
2. Effective date
3. Initial term — start date and end date
4. Auto-renewal clause — does it exist? What are the conditions and renewal period?
5. Termination notice period — how many days/months advance notice is required to terminate or decline renewal? Calculate the calendar deadline assuming the current term end date.
6. Rate or pricing renegotiation windows — list every clause that allows either party to request a rate change, including the notice period and the deadline to trigger it.
7. Option-to-renew clauses — any tenant or customer options to extend, including deadlines and conditions.
8. Assignment and subcontracting rights — can Walker assign or subcontract without consent?
9. Insurance and liability requirements — minimum coverage amounts or unusual caps.
10. Red flags — list any clause that deviates materially from standard Walker vendor/carrier/lease terms (e.g., unusually long auto-renewal, landlord-favorable use restrictions, uncapped liability).

For every date-sensitive item, state the clause reference (section number or paragraph), the triggering event, and the action Walker must take by that date.

OUTPUT FORMAT:
Return two sections:

SECTION 1 — STRUCTURED METADATA TABLE
A table with columns: Field | Detail | Clause Reference | Action Required | Deadline

SECTION 2 — RED FLAGS (bulleted list)
List each unusual or high-risk clause in plain English with the section reference. If none, write 'No red flags identified — recommend attorney spot-check.'

End with a one-sentence reminder: 'This extraction is a draft. A licensed attorney must review before any deadline-sensitive action is taken.'
```

---
department: human-resources
department_name: Human Resources
title: Role-Based Training Path Generator
data_class: Walker-internal
broker_review: false
---

# Role-Based Training Path Generator

**Use when:** You need to build or seed a structured training path for a Walker role — use this when onboarding a new hire, creating a job-specific development plan, or starting to document what training a given role actually requires.

**Data & tool rule:** Any approved AI tool. Keep inputs to Walker-internal info — no client names, manifests, or account data.

```text
ROLE:
You are a workforce development specialist who understands U.S. customs brokerage, freight forwarding, and 3PL operations. You know the regulatory landscape (CBP, TSA, CTPAT, state-level licensing), how Walker SCM is structured across sites, and what it takes to perform compliantly in each function.

CONTEXT:
[PASTE ROLE + LEVEL + ANY KNOWN REQUIREMENTS HERE — e.g., "Import Coordinator, entry-level, Chicago site" or "Warehouse Supervisor, mid-level, knows forklift cert is required"]

TASK:
Using the role and level above, generate a structured training path organized into four groups:

1. Onboarding — trainings every Walker employee in this role needs before handling live work (compliance basics, system access, safety, site orientation).
2. Role Competency — the core job skills this person must develop and demonstrate (e.g., entry filing, classification, customs valuation, WMS operation, carrier negotiation — whatever applies to this role).
3. Compliance and Regulatory — required or strongly recommended certifications and recurring trainings tied to CBP, TSA, CTPAT, HAZMAT, or other regulatory bodies. Flag any that are state- or jurisdiction-specific, and note renewal periods.
4. Leadership and Development — applicable if mid-level or above; include supervision, mentoring, or professional growth items.

For each training item, include:
- What it is and why it matters for this role
- Recommended sequence or timing (e.g., "Week 1", "Within 90 days", "Annual renewal")
- How completion is evidenced (certificate, test score, supervisor sign-off, system log, etc.)
- Any open questions HR should resolve before finalizing (e.g., vendor not selected, requirement varies by site)

Flag any items that would require a Licensed Customs Broker, legal, or IT/Compliance review before being added to a formal training policy.

Present this as a draft framework for HR review — not a finalized policy.

OUTPUT FORMAT:
Structured list organized under the four headings above. Use plain language. Each training item as a short block: name, rationale, timing, evidence of completion, and any open questions. End with a short "Next Steps for HR" section listing what needs to be confirmed or decided before this becomes a working training plan.
```

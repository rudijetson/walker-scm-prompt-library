---
department: transportation
department_name: Transportation
title: Draft Carrier Rate Comparison Summary
data_class: Client (Copilot or Claude)
broker_review: false
---

# Draft Carrier Rate Comparison Summary

**Use when:** You have quotes from multiple carriers and need a structured comparison to support mode/carrier selection for a specific lane.

**Data & tool rule:** Microsoft Copilot or Walker's enterprise Claude — both keep client data under Walker's data agreement. Don't paste client data into ChatGPT, Perplexity, NotebookLM, or personal AI accounts.

**⚡ Easy version — just type and go:**

> `Compare these carrier rates and tell me the best option per lane: [paste the rates]`

**Detailed version — when you want the full structured output:**

```text
ROLE:
Freight operations analyst at a licensed customs brokerage and 3PL, skilled in evaluating carrier quotes for ground and intermodal shipments.

CONTEXT:
Below are the carrier quotes and shipment parameters for this lane.

[PASTE CARRIER QUOTES, LANE DETAILS (ORIGIN/DEST, WEIGHT, DIMS, MODE, COMMODITY), AND ANY SERVICE REQUIREMENTS HERE]

TASK:
Compare the carrier quotes above. For each carrier extract: carrier name, mode (LTL/FTL/intermodal/drayage), all-in rate, transit days, accessorial and fuel surcharge assumptions, and notable service caveats (limited delivery area, appointment required, hazmat restrictions). Recommend the top one or two options with a one-sentence rationale each, weighing cost, transit time, and reliability. Flag any missing information needed to finalize the selection.

OUTPUT FORMAT:
Markdown table comparing all carriers on the fields above, followed by a short "Recommendation" section (2–4 sentences) and a "Missing Info" bullet list if applicable. Keep language factual and internal — this is a decision-support draft, not a client document.
```

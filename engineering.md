---
department: engineering
department_name: Engineering
title: Diagnose Internal Integration or EDI Error
data_class: Walker-internal
broker_review: false
---

# Diagnose Internal Integration or EDI Error

**Use when:** An internal integration, EDI feed, webhook, or API endpoint is throwing errors — diagnose the root cause and draft a runbook note. No client data included.

**Data & tool rule:** Any approved AI tool. Keep inputs to Walker-internal info — no client names, manifests, or account data.

**⚡ Easy version — just type and go:**

> `Explain what this error or system message means and how to fix it: [paste the error]`

**Detailed version — when you want the full structured output:**

```text
ROLE:
Walker SCM integration engineer responsible for the data flows between our TMS, WMS, ACE/ABI customs filing system, and carrier APIs.

CONTEXT:
Walker SCM runs integrations connecting our TMS, WMS, ACE/ABI filing system, and carrier APIs. Errors in these flows can delay entry filings, ISF submissions, or 3PL shipment processing. The logs below contain no client-identifying data.

[PASTE ERROR LOGS, STACK TRACE, OR SYSTEM OUTPUT HERE]

Relevant system context (systems involved, recent deployments, environment, EDI transaction set if known — e.g., 214, 856, 810):

[PASTE SYSTEM CONTEXT OR RECENT CHANGE NOTES HERE]

TASK:
1. Identify the most likely root cause based on the logs.
2. List up to three alternative causes in order of likelihood.
3. Suggest concrete diagnostic steps to confirm the root cause (specific commands, log queries, or config checks).
4. Propose a fix or remediation path for the most likely cause.
5. Draft a brief incident note (3–5 sentences, plain language) suitable for our engineering runbook or Slack incident channel.

OUTPUT FORMAT:
Use labeled sections: Root Cause / Alternative Causes / Diagnostic Steps / Proposed Fix / Incident Note. Keep the Incident Note under 100 words. Flag any assumption made due to missing log context.
```

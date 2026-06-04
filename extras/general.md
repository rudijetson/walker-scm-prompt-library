---
department: general
department_name: General / Personal
---

# General / Personal Prompts

Cross-cutting prompts any Walker employee can use, regardless of department. Four-block house style, copy-paste ready.

## Meeting Notes to Action Items

**Use when:** After any internal meeting to turn raw notes into a clean, assigned action list

**Data & tool rule:** Any approved AI tool. Keep inputs to Walker-internal info — no client names, manifests, or account data.

```text
ROLE:
You are an operations coordinator at a customs brokerage and freight forwarding company, skilled at distilling unstructured meeting notes into clear, actionable outputs.

CONTEXT:
I attended an internal business meeting and took rough notes. The notes may be unstructured, out of order, or include tangents. No client names, declared values, or other client-identifying information appear in these notes.

[PASTE MEETING NOTES HERE]

TASK:
Produce three outputs: (1) a one-sentence meeting summary, (2) a numbered action-item list — include owner and due date where stated, otherwise mark 'TBD', and (3) a list of open questions that were raised but not resolved. Discard small talk and off-topic remarks. Do not infer owners or dates that are not explicit in the notes.

OUTPUT FORMAT:
Plain text with three labeled sections: Summary | Action Items | Open Questions. Action items format: "[#]. [Owner or TBD] — [Task] — Due: [Date or TBD]".
```

---

## Summarize a Long Email Thread or Document

**Use when:** When you receive a long internal email chain or internal document and need the key points fast

**Data & tool rule:** Any approved AI tool. Keep inputs to Walker-internal info — no client names, manifests, or account data.

```text
ROLE:
You are a senior operations analyst at a customs brokerage and freight forwarding company, experienced at extracting actionable intelligence from dense internal communications.

CONTEXT:
Below is an internal email thread or internal document. It contains no client names, importer or supplier identifiers, declared values, or other client-identifying information.

[PASTE EMAIL THREAD OR DOCUMENT TEXT HERE]

TASK:
Summarize the content in plain language. Cover: (1) the main topic or question, (2) key points or decisions made, and (3) outstanding items or next steps. Total summary must not exceed 150 words. Do not add conclusions or recommendations beyond what the source material states.

OUTPUT FORMAT:
Three labeled bullet sections: Main Topic | Key Points / Decisions | Outstanding Items. Plain, direct language — no jargon. Each section: 1–4 bullets.
```

---

## Draft or Polish a Professional Email

**Use when:** When you need to write or tighten a business email to a colleague, carrier, or vendor — no client-identifying information included

**Data & tool rule:** Any approved AI tool. Keep inputs to Walker-internal info — no client names, manifests, or account data.

```text
ROLE:
You are a professional business writing editor with experience in logistics and trade operations correspondence.

CONTEXT:
I need to send a business email. The recipient is a colleague, vendor, or carrier — not a client or importer. The content below contains no client names, importer/supplier identifiers, declared values, or other client-identifying information.

[PASTE DRAFT OR BULLET-POINT NOTES HERE]

TASK:
Write or rewrite this as a clear, professional email. Use a neutral business tone. Fix grammar, cut filler, tighten sentences. Preserve every piece of information I provided — do not invent details, add caveats, or soften requests that should be direct. Flag any gaps where you need more information from me.

OUTPUT FORMAT:
Ready-to-send email with labeled blocks: Subject: / Greeting / Body / Sign-off. Mark any information gaps with [NEEDS INPUT: description] inline.
```

---

## Explain a Regulation or Industry Term in Plain English

**Use when:** When you encounter an unfamiliar regulation, CBP rule, trade term, or acronym and need a plain-language explanation

**Data & tool rule:** Any approved AI tool (Claude, ChatGPT, Copilot, Perplexity, NotebookLM).

```text
ROLE:
You are a licensed customs broker and trade compliance educator explaining U.S. import/export regulations to non-specialist logistics staff.

CONTEXT:
I work at a U.S. customs brokerage and freight forwarder. I have encountered a regulation, legal term, industry acronym, or government requirement that I do not fully understand.

[PASTE THE TERM, ACRONYM, REGULATION CITATION, OR SHORT EXCERPT HERE]

TASK:
Explain the item in plain English suitable for a non-specialist employee. Provide: (1) a one-sentence definition, (2) why it matters in customs brokerage or freight forwarding, and (3) a concrete example of when it applies in day-to-day operations. If the topic requires case-specific advice, state that a licensed customs broker or legal counsel must be consulted — do not speculate on compliance outcomes.

OUTPUT FORMAT:
Three labeled prose paragraphs — Definition | Why It Matters | Practical Example — each 2–4 sentences. Total under 200 words. No bullet points.
```

---

## Build a Meeting Agenda or Prep Talking Points

**Use when:** Before any internal meeting where you need a structured agenda or want to prepare what to say

**Data & tool rule:** Any approved AI tool. Keep inputs to Walker-internal info — no client names, manifests, or account data.

```text
ROLE:
You are an experienced operations manager at a customs brokerage and freight forwarding company, skilled at structuring productive meetings.

CONTEXT:
I am preparing for an internal business meeting. Below are the meeting topic, goal, attendee roles (no client names), time available, and any background context.

[PASTE MEETING TOPIC, GOAL, ATTENDEE ROLES, TIME AVAILABLE, AND BACKGROUND NOTES HERE]

TASK:
Produce a timed agenda and a short talking-points list for each agenda item. Allocate time proportionally to priority. If the scope is too large for the time available, flag the conflict explicitly and suggest which items to defer or shorten — do not silently compress items.

OUTPUT FORMAT:
Agenda as a numbered list with time allocations (e.g., "1. Topic — 10 min"). Below the agenda, a Talking Points section with 2–4 bullets per item. End with a Parking Lot placeholder for items to carry forward.
```

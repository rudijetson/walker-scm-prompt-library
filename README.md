# Walker SCM — AI Prompt Library

**New to AI? Open [`start-here.md`](start-here.md) first** — 10 dead-simple prompts you just copy and send. Then every department below has a one-line **easy version** up top, with the full **detailed version** tucked underneath for when you need structured output. Plus a personal **lifestyle** set. Each prompt is tagged with a `data_class` that says which AI tool you can paste real data into.

> More prompts live in [`extras/`](extras/): higher-value department prompts from Walker's discovery interviews, plus a general work-productivity set.

| Section | Prompt | Cleared for | File |
|---|---|---|---|
| **Start Here** | 10 easy one-liners | any tool (Copilot if client data) | [start-here.md](start-here.md) |
| Administration / Legal | Contract Clause & Deadline Extractor | Walker-internal | [administration.md](administration.md) |
| Business Development | Draft Prospect Outreach Email | Client (Copilot-only) | [business-development.md](business-development.md) |
| Customer Integration | Draft Client Onboarding Checklist from Intake Notes | Client (Copilot-only) | [customer-integration.md](customer-integration.md) |
| Engineering | Diagnose Internal Integration or EDI Error | Walker-internal | [engineering.md](engineering.md) |
| Executive Team | Weekly Ops Performance Narrative | Walker-internal | [executive-team.md](executive-team.md) |
| Finance | Billing Exception Audit (Complex Account) | Client (Copilot-only) | [finance.md](finance.md) |
| Freight Forwarding | Draft ISF Filing Checklist from Booking Data | Client (Copilot-only) | [freight-forwarding.md](freight-forwarding.md) |
| Human Resources | Draft Job Posting for Operations Role | Walker-internal | [human-resources.md](human-resources.md) |
| Information Technology | Draft IT Helpdesk Response | Walker-internal | [information-technology.md](information-technology.md) |
| Operations | Multi-Site P&L Variance Narrator | Client (Copilot-only) | [operations.md](operations.md) |
| PMO | Weekly Project Status Roll-Up | Walker-internal | [pmo.md](pmo.md) |
| Quality | Draft Corrective Action Report (CAR) from Incident Notes | Walker-internal | [quality.md](quality.md) |
| Sales | Draft Inbound Rate Quote Response | Client (Copilot-only) | [sales.md](sales.md) |
| Transportation | Draft Carrier Rate Comparison Summary | Client (Copilot-only) | [transportation.md](transportation.md) |
| Lifestyle / Personal | 6 prompts | Personal · any tool | [lifestyle.md](lifestyle.md) |

## Data classes

Every prompt's `data_class` tag is one of the four buckets defined in Walker's **AI Use Policy** (the "What you can put into AI tools" section). Before you paste real data into a prompt, check its tag:

| Class | What it means | Which tool you may use | Example input |
|---|---|---|---|
| **Public** | Information that is, or could be made, public | Any approved tool (Copilot, Claude, ChatGPT, Perplexity, NotebookLM) | HTSUS, CBP CSMS bulletins, Federal Register notices, Walker marketing copy |
| **Walker-internal** | Walker's own operations, with no client named | Any approved tool | Internal SOPs, team agendas, training material, Walker's own KPI summary |
| **Client (Copilot-only)** | Anything that names or identifies a client, importer, or supplier, or is commercially sensitive | **Microsoft Copilot only** — it keeps the data inside Walker's Microsoft 365 tenant | Manifests, declared values, EINs, importer names, freight cost detail, account-specific pricing |
| **Regulated (no AI)** | Highly sensitive | **No AI tool** without IT + Compliance sign-off | POA documents, surety bonds, ITAR/EAR commodity detail, C-TPAT confidential, SSNs, HR records |

When in doubt, treat your data as **Client (Copilot-only)** and use Copilot, or ask your AI Champion before you paste anything.

A `broker_review: true` tag means the prompt's output is client-facing — a Licensed Customs Broker must review it before it goes out.

_AI output is always a draft. The broker is the author._

# Walker SCM — AI Prompt Library

**New to AI? Open [`start-here.md`](start-here.md) first** — 10 dead-simple prompts you just copy and send. Then every department below has a one-line **easy version** up top, with the full **detailed version** underneath. Plus a personal **lifestyle** set. Each prompt is tagged with a `data_class` that says which AI tool you can paste real data into.

> More prompts live in [`extras/`](extras/): higher-value department prompts from Walker's discovery interviews, plus a general work-productivity set.

| Section | Prompt | Cleared for | File |
|---|---|---|---|
| **Start Here** | 10 easy one-liners | any tool (Copilot/Claude if client data) | [start-here.md](start-here.md) |
| Administration / Legal | Contract Clause & Deadline Extractor | Walker-internal | [administration.md](administration.md) |
| Business Development | Draft Prospect Outreach Email | Walker-internal | [business-development.md](business-development.md) |
| Customer Integration | Draft Client Onboarding Checklist from Intake Notes | Client (Copilot or Claude) | [customer-integration.md](customer-integration.md) |
| Engineering | Diagnose Internal Integration or EDI Error | Walker-internal | [engineering.md](engineering.md) |
| Executive Team | Weekly Ops Performance Narrative | Walker-internal | [executive-team.md](executive-team.md) |
| Finance | Billing Exception Audit (Complex Account) | Client (Copilot or Claude) | [finance.md](finance.md) |
| Freight Forwarding | Draft ISF Filing Checklist from Booking Data | Client (Copilot or Claude) | [freight-forwarding.md](freight-forwarding.md) |
| Human Resources | Draft Job Posting for Operations Role | Walker-internal | [human-resources.md](human-resources.md) |
| Information Technology | Draft IT Helpdesk Response | Walker-internal | [information-technology.md](information-technology.md) |
| Operations | Multi-Site P&L Variance Narrator | Client (Copilot or Claude) | [operations.md](operations.md) |
| PMO | Weekly Project Status Roll-Up | Walker-internal | [pmo.md](pmo.md) |
| Quality | Draft Corrective Action Report (CAR) from Incident Notes | Walker-internal | [quality.md](quality.md) |
| Sales | Draft Inbound Rate Quote Response | Client (Copilot or Claude) | [sales.md](sales.md) |
| Transportation | Draft Carrier Rate Comparison Summary | Client (Copilot or Claude) | [transportation.md](transportation.md) |
| Lifestyle / Personal | 6 prompts | Personal · any tool | [lifestyle.md](lifestyle.md) |

## Data classes

Every prompt's `data_class` tag tells you **which AI tool you can paste real data into**:

| Class | What it means | Which tool you may use | Example input |
|---|---|---|---|
| **Public** | Info that is, or could be made, public | Any approved tool (Copilot, Claude, ChatGPT, Perplexity, NotebookLM) | HTSUS, CBP CSMS bulletins, Walker marketing |
| **Walker-internal** | Walker's own operations, no client named | Any approved tool | Internal SOPs, agendas, training, Walker's own KPI summary |
| **Client (Copilot or Claude)** | Names or identifies a client/importer/supplier, or is commercially sensitive | **Microsoft Copilot or Walker's enterprise Claude only** — both keep data under Walker's data agreement (no training, retention controls). NOT ChatGPT, Perplexity, NotebookLM, or personal accounts. | Manifests, EINs, declared values, importer names, freight cost, account pricing |
| **Regulated (no AI)** | Highly sensitive | **No AI** without IT + Compliance sign-off | POA, surety bonds, ITAR/EAR, C-TPAT confidential, SSNs, HR records |

When in doubt, treat data as **Client** and use Copilot or enterprise Claude. A `broker_review: true` tag means the output is client-facing — a Licensed Customs Broker must review it before it goes out.

_AI output is always a draft. The broker is the author._

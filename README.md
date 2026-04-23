<p align="center">
  <img src="./assets/cairo-logo-dark.jpg" alt="Cairo by ColomboAI" width="720" />
</p>

<p align="center">
  <strong>Cairo's Autonomous Companies</strong><br/>
  The open platform where autonomous companies are built, deployed, and scaled.<br/>
  <em>From agents to autonomous companies.</em>
</p>

<p align="center">
  <a href="https://cairo.colomboai.com"><strong>🌐 Launch WebUI — cairo.colomboai.com</strong></a>
  &nbsp;&nbsp;•&nbsp;&nbsp;
  <a href="https://cairo.colomboai.com/download"><strong>⬇️ Download Desktop App</strong></a>
  &nbsp;&nbsp;•&nbsp;&nbsp;
  <a href="https://x.com/ColomboAI"><strong>𝕏 Follow @ColomboAI</strong></a>
</p>

<p align="center">
  <sub>v2.0.0 &nbsp;|&nbsp; macOS · Windows · Linux &nbsp;|&nbsp; WebUI Live Now ✅</sub>
</p>

---

## 🎬 See Cairo in Action

<p align="center">
  <img src="./assets/cairo-demo.gif" alt="Cairo demo showing the creator dashboard and autonomous company marketplace flow" width="960" />
</p>

<p align="center">
  <a href="https://cairo.colomboai.com"><strong>▶ Try Cairo live</strong></a>
</p>

---

## 🚀 What Comes After Agents

> **AI employees were the preview. Autonomous companies are the real category.**

Cairo turns AI from a tool you use into a company that operates.

- Launch full AI companies, not isolated agents
- Run departments, operators, workflows, and governance in one platform
- Connect to real apps, take real actions, and operate 24/7
- Start from a template and deploy in minutes

**Turn AI into real companies — assign goals, launch departments, compound capabilities, and scale execution without babysitting.**

---

## 🧠 The Shift Everyone Missed

```
LLMs        →  you talk to AI
Agents      →  AI does one task
Assistants  →  AI helps you work
                        ↓
Autonomous Companies  →  AI IS the company  ✅
```

Cairo is the first platform where you define a company, deploy it, and let it **operate itself** — 24/7, with real actions, real integrations, and real governance.

Why this matters now:

- Agents are saturated
- Copilots are saturated
- Workflows still need humans everywhere
- The next frontier is software that operates like a company

**Cairo is that frontier.**

---

## 🚀 Try It Right Now

### 🌐 No install — use the live WebUI

> **[https://cairo.colomboai.com](https://cairo.colomboai.com)**

Open your browser. Sign in. Start building.

### 💻 Or download the desktop app

| Platform | Download |
|----------|----------|
| 🍎 macOS | [Download from Cairo](https://cairo.colomboai.com/download) |
| 🪟 Windows | [Download from Cairo](https://cairo.colomboai.com/download) |
| 🐧 Linux | [Download from Cairo](https://cairo.colomboai.com/download) |

> Cairo auto-updates. When a new version ships, you'll be notified in-app — one click to upgrade.

---

## 🏗️ What You Can Build in Minutes

Cairo ships with a real **AI Marketing Agency** template out of the box. Here's what it does autonomously:

```
payment_received event fires
        ↓
billing_operator validates payment  (autonomous, LOW risk)
        ↓
outreach_operator composes email    (requires your approval)
        ↓
Gmail sends via Composio            (100+ app integrations)
        ↓
KPI dashboard updates               (emails_sent++)
```

No code. No infrastructure. No team. **One company definition file.**

Other companies you can build today:

| Company Type | What It Does |
|---|---|
| AI Legal Company | Reviews contracts, flags risks, drafts responses |
| AI Sales Org | Qualifies leads, sends outreach, tracks pipeline |
| AI Marketing Agency | Runs campaigns, processes payments, sends emails |
| AI Recruiting Firm | Screens candidates, schedules interviews, sends offers |
| AI Accounting Company | Processes invoices, tracks spend, generates reports |
| AI Customer Support | Handles tickets, escalates issues, closes loops |
| AI SaaS Operator | Manages onboarding, billing, and retention automatically |

---

## ⚙️ How Cairo Works

Cairo turns AI into **operational systems** — not chat windows.

```
Skills → Plugins → Operators → Departments → Autonomous Company
```

| Layer | What it is |
|---|---|
| 🧩 **Skills** | Atomic capabilities: generate contracts, analyze data, send emails, query APIs |
| 🔗 **Plugins** | Domain orchestration: legal plugin, marketing plugin, finance plugin |
| 🤖 **Operators** | Active AI workers running 24/7: sales operator, legal operator, support operator |
| 🏢 **Departments** | Coordinated execution layers: Sales, Marketing, Ops, Finance, Legal |
| 🌍 **Autonomous Company** | Full org that takes actions, responds to events, coordinates internally, operates continuously |

---

## 🔥 The Engine Under the Hood

### ACDL — Agentic Cognitive Design Language
Define companies like code. Human-readable, machine-validated, diff-friendly.

```yaml
---
type: company
id: ai_marketing_agency
version: "1.0"
departments:
  - billing_department
  - outreach_department
policies:
  - payment_approval_policy
kpis:
  - payments_processed
  - emails_sent
---
```

### ACE — Autonomous Company Engine
Executes your company. Manages operator lifecycle, workflow orchestration, governance enforcement, kill switches, and KPI monitoring.

```python
# Every operator runs this loop — continuously
while operator.status == "active":
    signals  = observe()
    context  = load_memory(signals)
    decision = decide(signals, context)
    action   = policy_guard(decision)   # governance check
    result   = act(action)
    write_memory(result)
    emit_events(result)
```

### UAPE — Universal Autonomous Process Engine
Provides the execution substrate for long-running autonomous work. UAPE coordinates multi-step reasoning, tool use, state transitions, and recovery paths so operators can keep moving from intent to outcome without fragile one-shot flows.

```text
intent → plan → execute → verify → adapt → continue
```

### DCRS — Dynamic Capabilities Retrieval System
Finds the right skills, tools, plugins, and operator capabilities at runtime. DCRS lets Cairo retrieve what an autonomous company needs in the moment instead of hard-wiring every possible action path ahead of time.

```text
signal arrives → retrieve relevant capabilities → rank best actions → pass to operator loop
```

### EIL — Event Intelligence Layer
Makes your company reactive to the real world.

```
IF payment_received    → trigger billing workflow
IF lead_created        → trigger sales outreach
IF churn_risk_detected → trigger retention campaign
IF support_ticket      → trigger resolution operator
```

### Memory + State
Your company remembers every interaction, adapts to patterns, and improves over time — powered by Mem0 long-term memory.

### Governance Built In
Every action passes through OPA policy checks before execution. Destructive actions (send email, delete, payment) require explicit human approval. Kill switches stop everything in under 2 seconds.

---

## 🤖 MC-1 LLM AI. Full Power.

**MC-1** is ColomboAI's proprietary AI reasoning engine — the brain behind every autonomous action Cairo takes. This isn't a wrapper around a third-party model. MC-1 is purpose-built for **operational AI execution**: thinking in roles, acting in structured steps, and recovering from failure without human intervention.

### How MC-1 powers every part of Cairo

| Where in Cairo | What MC-1 does |
|---|---|
| **Operator loops** | Runs the `observe → decide → act → verify` cycle for every operator, continuously, 24/7 |
| **Role-aware reasoning** | Each operator gets a prompt scoped to its department, tools, memory context, and risk class — not a generic chat prompt |
| **Structured action output** | Returns `compose / tool_call / research / plan / inform / wait` — executable decisions, not free-form text |
| **Company generation** | When you describe a company idea, MC-1 enriches the ACDL bundle — naming departments, operators, and wiring integration manifests |
| **Natural language edits** | Tell Cairo "add a finance department" — MC-1 applies the change to the live company definition |
| **Workflow execution** | Drives multi-step workflow DAGs — each step reasoned, verified, and logged before the next fires |
| **Replanning on failure** | If an action fails, MC-1 replanner rewrites the plan and retries automatically — zero human intervention |
| **Outcome verification** | After every tool call, MC-1 verifies the result before writing to memory or emitting downstream events |
| **Concurrent load management** | MC-1 Gate reserves 3 slots for live user chat + 12 for background operators — user experience is never starved |
| **Fallback resilience** | If the primary MC-1 call times out, a direct fallback fires instantly — operators never freeze or drop tasks |

### MC-1 inside a live operator

```
Operator wakes on event signal
        ↓
MC-1 receives: role + memory context + available tools + conversation history
        ↓
MC-1 decides: tool_call → Composio Gmail
        ↓
Governance check: OPA policy gate (LOW / MEDIUM / HIGH / CRITICAL)
        ↓
Action executes → MC-1 verifies outcome
        ↓
Result written to Mem0 long-term memory
        ↓
Downstream events emitted → next operator wakes
```

MC-1 is OpenAI API-compatible — the entire Cairo operator stack is portable and future-proof.

---

## 🔌 100+ App Connects

Cairo operators can take real actions across your entire stack:

**Communication** — Gmail, Slack, Telegram, DingTalk, Lark (Feishu)

**Productivity** — Notion, Google Docs, Google Sheets, Jira, Linear

**Sales & CRM** — Salesforce, HubSpot, Pipedrive

**Dev Tools** — GitHub, GitLab, Jira, Linear

**Finance** — Stripe, QuickBooks

**And 90+ more** — if it has an API, Cairo can use it.

---

## 🛠️ Built-In Skills — Ready to Use

Cairo ships with a full skill library. No setup required.

| Skill | What it does |
|---|---|
| 🌐 Web Search | Real-time web research |
| 🧠 Memory | Persistent cross-session knowledge |
| 📊 Excel / BI | Analyze and generate spreadsheets |
| 📄 PPTX Generator | Create presentations from prompts |
| 📝 DOCX | Generate formatted Word documents |
| 🖼️ Image Generation | AI image creation |
| 🔍 Browser Automation | Control web UIs autonomously |
| 📋 PDF Processing | Extract, analyze, convert PDFs |
| 📈 Mermaid Diagrams | Auto-generate flowcharts and diagrams |
| 🛒 Form Fill | Autonomously fill web forms |

---

## 📡 Access Cairo From Anywhere

Cairo isn't just a desktop app. It's a platform you can reach from any device.

- **WebUI** — [cairo.colomboai.com](https://cairo.colomboai.com) — use from any browser, any device
- **Desktop App** — native Electron app for macOS, Windows, Linux
- **Telegram** — chat with your Cairo operators directly from Telegram
- **DingTalk** — AI Card streaming with automatic fallback
- **Lark / Feishu** — enterprise collaboration via Feishu bots
- **REST API** — integrate Cairo into your own products via `/v1/cairo/chat`

---

## ⚔️ Cairo vs Everything Else

Claude Code, Claude Coworks, and OpenClaw represent a major leap in agentic software. They help developers, teams, and companies move faster.

But they are still tools people use.

**Cairo is the leap after that.**

It is not another agentic assistant.  
It is not another coworker layer.  
It is not another toolkit for chaining prompts and tools.

**Cairo is the platform where autonomous companies are created, deployed, and operated as full-fledged autonomous companies.**

This is the next logical advancement in AI innovation:

```text
chatbots → copilots → agents → agentic tools → autonomous companies
```

The winners of the next era will not just use AI better.  
They will build companies that run on AI natively.

| | Claude Code | Claude Coworks | OpenClaw | **Cairo** |
|---|---|---|---|---|
| What it is | Agentic coding tool for individual developers | Agentic collaboration tool for teams and companies | Open agentic tool framework for builders and operators | **Autonomous company platform** |
| Primary model | Human directs AI to complete tasks | Humans coordinate AI coworkers across workflows | Humans assemble and run agentic systems | **Humans define a company, Cairo operates it** |
| Best for | Coding, debugging, and shipping features faster | Team productivity and assisted execution | Custom agent infrastructure and experimentation | **Building, launching, and scaling full autonomous companies** |
| Works as a full company | ❌ | ❌ | ❌ | ✅ |
| Runs departments and operators 24/7 | ❌ | Partial | Partial | ✅ |
| Multi-department coordination | ❌ | Limited | Manual | ✅ |
| Real app integrations | Limited | Limited | Manual setup | ✅ 100+ via Composio |
| Governance and approval gates | Limited | Limited | Manual | ✅ Built-in OPA |
| Long-term memory and company state | Limited | Limited | Manual | ✅ IMP (Isolate Memory Protocol) |
| Kill switch and runtime controls | ❌ | ❌ | Manual | ✅ Stops in <2 seconds |
| Desktop + WebUI + API | Partial | Partial | Framework-dependent | ✅ |
| Strategic outcome | Better agentic assistance | Better AI teammates | More flexible agentic tooling | **The next stage beyond agentic tools: autonomous companies as a new computing platform** |

---

## 🌍 Why This Matters

For the first time in history:

👉 **Anyone can build a company** — no hiring, no infrastructure, no ops team  
👉 **Anyone can operate a company** — define it once, it runs itself  
👉 **Anyone can scale a company** — add operators, not headcount  

```
Before Cairo:  build product → hire team → manage ops → scale manually
With Cairo:    define company → deploy → operate autonomously → scale infinitely
```

---

## 🏪 Autonomous Company Marketplace — Live Now

Cairo has a fully live marketplace where you can **browse, install, and run autonomous companies in one click** — no setup, no configuration, no code.

### How it works

```
Browse marketplace → click Install → company deploys instantly
        ↓
ACE runtime starts all operators automatically
        ↓
Company is live — running 24/7 on your account
```

### What the marketplace gives you

| Feature | What it does |
|---|---|
| **Browse & search** | Filter by category, pricing model, rating, or featured — with 30s cached results for instant load |
| **One-click install** | Hit Install → Cairo validates the bundle, deploys the ACE company, starts all operators automatically |
| **Free & paid companies** | Free companies install instantly. Paid companies go through Stripe checkout |
| **Creator publishing** | Build your own autonomous company and publish it to the marketplace for others to use |
| **Version history** | Every listing tracks versions with changelogs — installed users get notified when updates ship |
| **Ratings & reviews** | 1–5 star reviews on every listing — community-driven quality signal |
| **Creator dashboard** | Track installs, earnings, and payout history from your creator dashboard |
| **Auto-repair** | If an install loses its runtime connection, Cairo auto-repairs it — no manual intervention |
| **Uninstall cleanly** | Uninstalling stops all operator loops and archives the company — no orphaned processes |

### Deep link support

Every marketplace listing has a shareable URL and a Cairo deep link:
```
https://cairo.colomboai.com/marketplace/{company-slug}
cairo://marketplace/{company-slug}
```

Share a company. Anyone with Cairo can install it in one click.

---

## 💰 Build & Sell Autonomous Companies — Creator Economy

Cairo isn't just a platform to use autonomous companies. It's a platform to **build and sell them**.

If you can define a company that solves a real problem, you can publish it to the marketplace and earn every time someone installs it.

### Creator flow

```
Build your company (ACDL bundle)
        ↓
Save as private — test it on your own account
        ↓
Publish to marketplace (free or paid)
        ↓
Other Cairo users install it → operators run on their account
        ↓
You earn 70% of every sale — Cairo takes 30%
```

### Revenue split

| Who gets it | Cut |
|---|---|
| **You (creator)** | **70%** of every sale |
| Cairo platform fee | 30% |

Payouts tracked in your creator dashboard. Full payout history available.

### What creators get

| Tool | What it does |
|---|---|
| **Creator dashboard** | See total installs, total earned, and pending payout across all your listings |
| **Listing management** | Create, edit, publish, unpublish, or resubmit listings at any time |
| **Version publishing** | Ship updates to your company — all active installs get notified automatically |
| **Private listings** | Keep a company private for your own use, or share it selectively before going public |
| **Pricing control** | Set your own price in USD — free or paid |
| **Payout history** | Full breakdown of gross, platform fee, and net per transaction |

### Listing lifecycle

```
DRAFT → PRIVATE → PUBLISHED
                      ↓
              users install & rate
                      ↓
           creator earns 70% per sale
                      ↓
        publish new version → installs notified
```

Creators can unpublish, resubmit after suspension, or deactivate at any time — existing installs keep running.

---

## 🔒 Security & Governance

Cairo is built for production from day one:

- Every action passes through **OPA (Open Policy Agent)** policy checks
- **Destructive actions** (send email, delete, payment) require explicit human approval
- **Kill switches** halt all operator loops within 2 seconds
- **Tenant isolation** — cross-tenant event routing is architecturally impossible
- **Audit trail** — every decision, action, and outcome is logged
- **Rate limiting** — Redis token bucket with in-memory fallback
- **Local data** — desktop app stores all data in local SQLite, nothing uploaded without your consent

---

## 📦 Tech Stack

| Layer | Technology |
|---|---|
| Desktop | Electron + React 19 + TypeScript |
| WebUI | Next.js (live at cairo.colomboai.com) |
| Backend | FastAPI (async Python) |
| AI Brain | MC-1 by ColomboAI (OpenAI-compatible) |
| Memory | Mem0 + ChromaDB |
| App Connects | Composio (100+ apps) |
| Policy Engine | OPA (Open Policy Agent) |
| Code Execution | E2B cloud sandboxes |
| Browser Automation | browser-use |
| Observability | OpenTelemetry + Prometheus + Sentry |
| Deployment | Docker + GCP Cloud Run |

---

## ⭐ If Cairo is useful to you

**Star this repo** — it helps more builders discover Cairo and join the movement.

Every star tells us: *keep building*.

---

## 📬 Stay in the Loop

- **Website**: [cairo.colomboai.com](https://cairo.colomboai.com)
- **Twitter/X**: [@ColomboAI](https://x.com/ColomboAI)
- **Contact**: [colomboai.com/contact](https://colomboai.com/contact)
- **ColomboAI**: [colomboai.com](https://colomboai.com)
- **Downloads**: [Desktop + Cairo Core](https://cairo.colomboai.com/download)

---

<p align="center">
  <a href="https://cairo.colomboai.com"><strong>→ Launch Cairo Now</strong></a>
  &nbsp;·&nbsp;
  <a href="https://cairo.colomboai.com/download"><strong>→ Download Desktop App</strong></a>
</p>

<p align="center">
  <strong>Build companies that build themselves.</strong>
</p>

<p align="center">
  © 2026 ColomboAI Inc. All rights reserved.
</p>

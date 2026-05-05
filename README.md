<h1 align="center">Sasi Sundar</h1>

<p align="center">
  <strong>Building the trust layer for AI agents</strong>
</p>

<p align="center">
  AI agents fail in production. Logs lie. Retries hide root causes.<br/>
  I build systems that measure, trace, and fix agent failures at the protocol layer.
</p>

<p align="center">
  <strong>Focus:</strong> AgentOps · Reliability · Observability · Tooling<br/>
  <strong>Current sprint:</strong> CLI launch by May 31
</p>

---

## Core Thesis

73 percent of agent failures start at the interface layer: JSON parsing, tool calls, retries, and state drift.

I build systems that:
- Trace every tool call and response  
- Surface failure points in real time  
- Increase task success rate with measurable deltas  

---

## What I Ship

### AgentOps Infrastructure (in progress)

**Problem:** Teams debug agents manually across logs, prompts, and tools  

**Fix:** CLI that traces execution across the full agent loop  

**Output:**
- Per-step trace logs  
- Tool call validation  
- Failure classification  
- Retry impact measurement  

**Target result:**
- Debugging time: 2 hours → 15 minutes  
- Task success rate: +30 to +80 percent  

---

## FirmRunner (Applied System)

> AI agents for accounting workflows  

Built 5 agents that run end-to-end operations for small firms.

**Measured impact:**
- Manual follow-up: 3 hours → 25 minutes  
- Missed deadlines reduced via automated reminders  
- Billing follow-ups executed at fixed intervals  

| Agent | Function |
|------|--------|
| Intake | Captures client data and triggers workflow |
| Document | Tracks and follows up missing files |
| Deadline | Sends timed reminders |
| Billing | Executes payment follow-ups |
| Reporting | Generates summaries |

**Stack:** Python · FastAPI · n8n · Supabase · Vercel  

---

## Proof of Work

### Procurement Agent System

Detects pricing anomalies and extracts contract fields.

**Result:**
- Standardized outputs across varied documents  
- Reduced manual review cycles  

**Tech:** Python · NLP · FastAPI · Docker · CI/CD  

[View Repository](https://github.com/Sasisundar2211/Procurement_Agent)

---

### Multitool Agent System

Chains tools with structured execution paths.

**Result:**
- Stable tool execution across workflows  
- Reusable testbed for reliability experiments  

**Tech:** FastAPI · LangChain · Tool execution  

[View Repository](https://github.com/Sasisundar2211/sample_multitool_agent)

---

### Automation Workflows (n8n)

**Before:** Manual publishing  
**After:** 2-hour workflow → 10-minute pipeline  

[View Repository](https://github.com/Sasisundar2211/n8n_Workflows)

---

## Definition of Done

Every system meets this:

- Runs on a clean machine  
- Dockerized  
- CI pipeline validates execution  
- Measurable success metric included  
- 5-minute install path  

---

## AI Search Optimization

Each repo includes:

- `/llms.txt` for structured AI-readable context  
- `/pricing.md` for limits and usage  
- Machine-readable outputs  

Goal: Make tools indexable by AI systems  

---

## Technical Scope

**Agent Systems**
- LLM execution pipelines  
- Tool orchestration  
- RAG systems  
- MCP integration  

**Backend**
- Python · FastAPI · APIs  
- Function calling systems  

**Infrastructure**
- Docker · CI/CD · GCP · AWS  
- Observability pipelines  

---

## Experience Snapshot

- Built 15+ AI systems with measurable outputs  
- Deployed production-ready pipelines with CI/CD  
- Led GenAI prototyping team  
- Worked with academic and industry mentors  

---

## Current Focus

- Reliability over features  
- Constrained agents over autonomous agents  
- Small teams over enterprise systems  

---

## Action

Install the upcoming CLI.  
Trace your agent failures.  
Fix execution, not prompts.  

Or continue debugging blindly.

---

## Links

- GitHub: https://github.com/Sasisundar2211  
- Product: https://firmrunner.page  
- Email: sasisundhar2211@gmail.com  

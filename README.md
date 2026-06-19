# Sasi Sundar

Building reliability infrastructure for AI agents.

Founder @ Giant · **[Vouqis](https://vouqis.tech)**, a reliability gateway for MCP servers · Final-year B.Tech AI & ML

[vouqis.tech](https://vouqis.tech) &nbsp;·&nbsp; [sasisundar.me](https://www.sasisundar.me) &nbsp;·&nbsp; [linkedin](https://www.linkedin.com/in/sasi-sundar) &nbsp;·&nbsp; [x.com](https://x.com/SasiSundar09) &nbsp;·&nbsp; [sasisundhar2211@gmail.com](mailto:sasisundhar2211@gmail.com)

---

## The Problem

MCP agents fail silently.

The server returns `HTTP 200`. Your monitoring stays green. Your agent executes on null data. A customer finds the broken result three days later.

I killed my previous company — FirmRunner, an AI onboarding system for CPA firms — when task success never crossed 85%. The failure mode wasn't bad models. It was the gap at the protocol boundary: what the tool returned and what the agent assumed were different. I built Vouqis to close that gap.

---

## Currently Building

### [Vouqis](https://vouqis.tech) — Reliability Gateway for MCP Servers

```
Agent → Vouqis → MCP Server
```

Sits between your agent and every MCP server. Validates every request. Blocks null and malformed responses before they reach your agent. Enforces timeouts. Retries transient failures. Logs every decision as a structured audit event.

```bash
npx @vouqis/cli proxy \
  --upstream https://your-mcp-server.com \
  --timeout 5000 \
  --retry 2
```

One command. No SDK changes. No server modifications.

**Live test against Exa's production MCP endpoint:**

```
malformed request  →  blocked in 4ms   (before any network call)
invalid request    →  blocked in 0ms   (before any network call)
valid request      →  passed through, real results returned
```

**1,839 npm downloads** &nbsp;·&nbsp; Open source → [Sasisundar2211/Vouqis](https://github.com/Sasisundar2211/Vouqis)

---

## Engineering Principles

- Reliability over features
- Evidence over opinions
- No silent failures
- Work is done when verified, not when shipped
- Customer pain before founder excitement

---

## Selected Projects

| Project | What | Stack |
|---|---|---|
| **[Vouqis](https://github.com/Sasisundar2211/Vouqis)** | MCP Reliability Gateway | TypeScript · Node.js · oclif · Vercel · GitHub Actions |
| **[Procurement AI](https://github.com/Sasisundar2211/Autonomous-Procurement-AI-System)** | Multi-agent procurement integrity | Python · FastAPI · Gemini |
| **[Multi-Tool Agent](https://github.com/Sasisundar2211/sample_multitool_agent)** | Tool orchestration & reliability experiments | FastAPI · Google ADK · LangChain |
| **[n8n Workflows](https://github.com/Sasisundar2211/n8n_Workflows)** | Workflow automation | n8n |

---

## Technical Focus

**Languages** — TypeScript · Python · JavaScript · SQL  
**AI & Agents** — MCP Protocol · Gemini Flash · LangChain · Google ADK · Agent Systems  
**Infrastructure** — Node.js · Next.js · Supabase · Vercel · GitHub Actions  
**Observability** — Audit Logging · Protocol Validation · Request Tracing · Timeout Enforcement

---

## Experience

**Giant** — Founder *(May 2026 – Present)*  
Vouqis: protocol design, reliability instrumentation, eval pipeline architecture, technical sales to early customers.  
Stack: TypeScript · Node.js · Next.js · oclif · Supabase · Vercel · GitHub Actions

**FirmRunner** — Founder *(Dec 2025 – Apr 2026, killed)*  
AI client onboarding for CPA firms. 5 AI agents, Supabase, Gemini Flash. Full PRD, pitch deck, discovery calls with firm owners. Killed when task success never hit 85% — compliance workflows too variable for the pipeline design. That gap became Vouqis.

**BITS Pilani, Hyderabad** — AI/ML Intern *(May–Jul 2025)*  
Production ML pipelines, classification and regression models. Improved model accuracy 18% via hyperparameter tuning. Co-authored academic research.

**Edunet Foundation / TechSaksham** — AI Intern *(Feb–Mar 2025)*  
Nationally selected (Microsoft & SAP via AICTE). Built and presented a functional AI prototype to domain experts.

**BITS Pilani** — Research Intern *(Jun–Aug 2024)*  
ML models on IoT data streams. Co-authored research paper.

**MentorKart** — Fullstack Trainee *(Jun–Dec 2023)*  
Node.js · Express · MongoDB · React — foundational stack, now used in production.

---

## Education

**Potti Sreeramulu Engineering College** — B.Tech, Artificial Intelligence & Machine Learning *(2023–2027)*

---

## Certifications

5-Day AI Agents Intensive · Google &nbsp;·&nbsp; AI: Transformative Learning · TechSaksham (Microsoft & SAP) &nbsp;·&nbsp; Google Cloud Security Summit (Asia Pacific) &nbsp;·&nbsp; Introduction to MongoDB &nbsp;·&nbsp; Python Programming Training

---

## Open To

AI Infrastructure · Agent Reliability · Forward Deployed Engineer roles · Remote-first

---

*Intelligence gets attention. Reliability earns trust.*

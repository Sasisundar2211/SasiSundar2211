<h1 align="center">Sasi Sundar</h1>

<p align="center">
  <strong>Building the trust layer for AI agents</strong>
</p>

<p align="center">
  AI agents fail in production. Logs lie. Retries hide root causes.<br/>
  I build systems that measure, trace, and fix agent failures at the protocol layer.
</p>

<p align="center">
  <strong>Focus:</strong> MCP Reliability · AgentOps · Observability · Tooling<br/>
  <strong>Founder:</strong> <a href="https://github.com/Vou-qis/vouqis">Vouqis</a> · GIant
</p>

---

## Current Build: Vouqis

MCP server reliability auditing via protocol-layer probes.

**What it does:** Sends 10 probe types across malformed RPC envelopes, timeout boundaries, and schema edge cases to any MCP server. Returns a Trust Score from 0 to 100.

**Real result:** Exa MCP endpoint scored 92/100. Failed on a malformed JSON-RPC envelope missing `id` and `params`. The null-check probes passed.

**CI/CD gate:**
```bash
vouqis audit --url https://your-mcp-server.com --fail-below 80
# Returns non-zero exit code if Trust Score < 80
# Wire into your pipeline. Block bad deployments.
```

**Run it:** [github.com/Sasisundar2211/Vouqis26](https://github.com/Sasisundar2211/Vouqis26)

---

## Core Thesis

In every production AI system I have built, the majority of failures traced back to the interface layer: malformed tool calls, JSON parsing failures, unhandled retries, and state drift. Not the model. Not the prompt. The protocol.

I build systems that:
- Probe the protocol layer before failures reach production
- Surface exactly which tool call, envelope, or schema edge case broke
- Produce a measurable Trust Score your CI/CD pipeline can gate on

---

## Proof of Work

### Procurement Integrity Agent
Multi-agent system that detects price drift and enforces contract compliance across vendor documents.

**Verified results:**
- Standardized extraction outputs across varied document formats
- Reduced manual review cycles per procurement batch

**Tech:** Python · Gemini 1.5 Flash · NLP · FastAPI · Docker · CI/CD

[View Repository](https://github.com/Sasisundar2211/Autonomous-Procurement-AI-System)

---

### Multitool Agent System
Chains tools with deterministic execution paths. Built as a reliability testbed for tool call validation and retry behavior.

**Verified results:**
- Stable tool execution across multi-step workflows
- Reusable harness for reliability experiments across agent architectures

**Tech:** FastAPI · Google ADK · LangChain · Tool execution

[View Repository](https://github.com/Sasisundar2211/sample_multitool_agent)

---

### Automation Workflows (n8n)
**Before:** Manual publishing pipeline, ~2 hours per run
**After:** Automated pipeline, ~10 minutes per run

[View Repository](https://github.com/Sasisundar2211/n8n_Workflows)

---

## Definition of Done

Every system I ship meets this before it is called done:

- Runs on a clean machine
- Dockerized
- CI pipeline validates execution
- Measurable success metric included
- 5-minute install path

---

## Technical Scope

**Agent Systems**
- LLM execution pipelines
- MCP server integration and reliability testing
- Tool orchestration and validation
- RAG systems

**Backend**
- Python · FastAPI · Function calling systems
- Protocol-layer instrumentation

**Infrastructure**
- Docker · CI/CD · GCP · AWS
- Observability pipelines

---

## Experience

- Built 15+ AI systems with production CI/CD and measurable outputs
- Internship at BITS Pilani Hyderabad
- Nationally selected: Microsoft and SAP TechSaksham program
- Co-authored applied IoT research paper
- Led GenAI prototyping team

---

## Principles

- Reliability over features
- Constrained agents over autonomous agents
- Measurable outcomes over claimed improvements
- Kill what does not work rather than ship it

---

## Action

Run Vouqis against your MCP server.

```bash
git clone https://github.com/Sasisundar2211/Vouqis26
cd Vouqis26
npm install
vouqis audit --url https://your-mcp-server.com
```

Get your Trust Score. Find out what your logs are not showing you.

Or keep debugging blindly.

---

## Contact

- LinkedIn: [linkedin.com/in/sasi-sundar](https://www.linkedin.com/in/sasi-sundar)
- Email: sasisundhar2211@gmail.com
- Vouqis: [github.com/Sasisundar2211/Vouqis26](https://github.com/Sasisundar2211/Vouqis26)

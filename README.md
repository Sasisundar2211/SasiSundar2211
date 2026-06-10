<h1 align="center">Sasi Sundar</h1>

<p align="center">
  <strong>Building reliability infrastructure for AI agents</strong>
</p>

<p align="center">
  Founder of Vouqis, a reliability gateway for MCP servers.<br/>
  Focused on AI agent reliability, MCP infrastructure, observability, and protocol-level failures.
</p>

<p align="center">
  <strong>Current Focus:</strong> MCP Reliability · Agent Infrastructure · Observability · AI Systems
</p>

---

# Current Build: Vouqis

Vouqis is a reliability gateway for MCP servers.

AI agents often receive successful responses even when tool outputs are empty, malformed, incomplete, or unusable.

Traditional monitoring sees:

```text
HTTP 200 OK
```

Users experience:

```text
Task failed
```

Vouqis sits between the agent and MCP server and catches these failures before they reach production.

```text
Agent
  ↓
Vouqis Gateway
  ↓
MCP Server
```

Current capabilities:

* Request validation
* Response validation
* Timeout detection
* Retry logic
* Structured audit logs

The goal is simple:

Detect failures that appear successful.

Repository:

https://github.com/Sasisundar2211/Vouqis

---

# Why I'm Working On This

While building AI agents and automation systems, I repeatedly encountered failures that looked successful.

The tool call succeeded.

Logs showed success.

The agent continued execution.

The user still received a bad result.

The hardest failures were not crashes.

They were failures hidden behind successful responses.

After seeing this pattern repeatedly, I started building tools focused on reliability instead of capability.

---

# Core Thesis

Most AI infrastructure focuses on:

* Better models
* Better prompts
* Better orchestration

A large percentage of production failures happen somewhere else:

* Tool calls
* Protocol boundaries
* Invalid responses
* State mismatches
* Silent failures

Reliability becomes the bottleneck before intelligence does.

---

# Projects

## Vouqis

Reliability gateway for MCP servers.

Focus:

* Response validation
* Failure detection
* Reliability enforcement
* Production observability

Repository:

https://github.com/Vou-qis/vouqis

---

## Procurement Integrity Agent

Multi-agent system designed to detect procurement inconsistencies and support contract compliance workflows.

Highlights:

* Structured document extraction
* Workflow automation
* Agent orchestration
* Reliability-focused execution

Tech:

Python · FastAPI · Gemini · Docker

Repository:

https://github.com/Sasisundar2211/Autonomous-Procurement-AI-System

---

## Multi-Tool Agent System

Experimental environment for studying tool orchestration, retries, execution flow, and agent reliability.

Focus:

* Tool chaining
* Deterministic execution
* Agent evaluation
* Reliability testing

Tech:

FastAPI · Google ADK · LangChain

Repository:

https://github.com/Sasisundar2211/sample_multitool_agent

---

## Automation Workflows

Workflow automation experiments using n8n.

Focus:

* Process automation
* Operational efficiency
* Workflow orchestration

Repository:

https://github.com/Sasisundar2211/n8n_Workflows

---

# Technical Interests

## AI Systems

* AI Agents
* MCP Infrastructure
* Agent Reliability
* Tool Orchestration
* RAG Systems
* Evaluation Systems

## Backend

* Python
* FastAPI
* TypeScript
* API Systems
* Reliability Engineering

## Infrastructure

* Docker
* CI/CD
* Observability
* Cloud Deployment
* Production Monitoring

---

# Operating Principles

* Reliability over features
* Evidence over assumptions
* Production reality over local success
* Customer problems over technical novelty
* Deterministic systems over hidden behavior
* Measure outcomes, not activity

---

# Current Mission

Understand why AI agents fail in production and build infrastructure that prevents those failures before they reach users.

---

# Experience

* Founder, Vouqis
* Final-year B.Tech AIML student
* Internship at BITS Pilani Hyderabad
* Microsoft & SAP TechSaksham participant
* Co-authored applied IoT research paper
* Built multiple AI systems across automation, agents, and infrastructure

---

# Connect

LinkedIn:
https://www.linkedin.com/in/sasi-sundar

Email:
[sasisundhar2211@gmail.com](mailto:sasisundhar2211@gmail.com)

GitHub:
https://github.com/Sasisundar2211

Vouqis:
https://github.com/Vou-qis/vouqis

## Mallika Nayak

Senior backend and distributed systems engineer (ex-Microsoft, Walmart Labs, Morgan Stanley) now building production-grade AI systems.

I work at the intersection of **distributed systems and applied AI** — focusing on making LLM-based systems reliable enough for real-world use. That includes evaluation, observability, failure handling, and system design beyond prototypes.

---

## What I bring

* 10+ years building **high-reliability backend systems** at scale (99.99% uptime, event-driven architectures, low-latency systems)
* Strong focus on **production concerns** — not just building features, but ensuring they behave predictably under failure
* Experience bridging **backend systems and AI workflows** — making LLMs measurable, debuggable, and safe to deploy

---

## Selected Work

### AI system with risk-gated decision workflows

→ [`portfolio_agenticAI`](https://github.com/nayakmallikaai/portfolio_agenticAI)

Built a multi-agent system for financial research with **human-in-the-loop approval and risk controls**.

* Designed agent orchestration with clear separation between **decision and execution layers**
* Implemented **approval gates** to prevent unsafe actions before execution
* Added **observability (LangSmith tracing)** to debug non-deterministic behavior
* Ensured reliability via **idempotency, retries, and atomic state transitions**

**Why it matters:** Most agent systems fail silently or behave unpredictably. This system introduces control layers required for real-world usage.

---

### LLM evaluation pipeline (LLM-as-a-Judge)

Built an evaluation system combining **deterministic test execution + model-based scoring**.

* Detects **bias and inconsistency** in LLM outputs
* Surfaces **low-confidence evaluations** instead of blindly trusting scores
* Uses controlled execution environments for reproducibility

**Why it matters:** Most teams rely on unreliable evaluation signals. This system helps determine when LLM outputs can actually be trusted.

---

### Retrieval system (RAG with reranking + failure analysis)

Built an end-to-end retrieval pipeline focused on **relevance and failure modes**.

* Two-stage retrieval: **ANN search + cross-encoder reranking**
* Query transformation to improve recall
* Instrumentation to analyze **where retrieval breaks down**

**Why it matters:** Naive RAG pipelines degrade quickly in real use. This system focuses on improving both quality and debuggability.

---

## Writing

I document systems as I build them — including what fails and why.

* LLM evaluation write-up:
  https://www.linkedin.com/pulse/i-built-llm-judge-evaluate-code-first-version-wrong-mallika-nayak-zshvc

* HashNode : https://portfolioagenticai.hashnode.dev/

---

## Tech Stack

Python · Java ·C# . Distributed Systems · Event-driven Architecture
LangGraph · LangChain · LLM APIs · AWS · PostgreSQL · Vector DBs
Observability · Evaluation Systems · Backend Infrastructure Azure

---

## Background

* Microsoft — Distributed systems, routing platforms, backend infrastructure
* Walmart Labs — Search relevance, ML pipelines, experimentation
* Morgan Stanley — Event-driven platforms, compliance systems

M.Tech — IIIT Bangalore

---
Open to roles

Senior / Staff roles in:

Backend Engineering
Distributed Systems
AI / ML Platform Engineering

I’m particularly interested in teams working on real-world AI systems where reliability and system design matter.






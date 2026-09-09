# 👋 Rohith Kumar Reddy

🎓 Master's in Computer Science @ UMass Amherst (Sep 2025 – Dec 2026)
💻 Software Engineer | Distributed Systems • Applied AI Platforms • Backend

I build **distributed backend platforms**, **LLM agent infrastructure**, and **cloud-native services**, most recently an internal AI gateway routing **1.8B+ tokens/day** and a federated knowledge platform across five product units.

Currently:
- **Software Engineer Intern** at *SS&C Technologies* — ACE Lab & QE CoE Labs (Boston, MA): AI gateway, MCP tool platform, KG + RAG knowledge layer

Previously:
- **Software Development Engineer** at *Publicis Sapient (Lloyds Banking Group, UK)* — cloud-native pricing platform serving 1M+ merchants; £450K annual revenue
- **Founding Software Engineer** at *CREW (SKDIV Industries)* — event-driven backend and ML recommendation pipeline for a 10K+ user social platform

I enjoy working at the intersection of **distributed systems, LLM platforms, and real-world impact**.

---

## ⚙️ What I Work On
- **Distributed Backend Systems** — microservices, Kafka, REST/gRPC, event-driven architecture, partitioned Postgres, scalability
- **🤖 LLM Platforms & Agent Infrastructure** — MCP tool servers, LangGraph / LangChain workflows, LiteLLM gateways, hybrid retrieval (BM25 + vector + RRF)
- **🧠 RAG & Knowledge Systems** — knowledge graphs, hybrid dense + lexical retrieval, LLM-as-judge evaluation, golden-set quality gates
- **☁️ Cloud & Infrastructure** — AWS (EKS, RDS, S3, Lambda), Docker, Kubernetes, Helm, CI/CD, observability
- **🔐 Privacy & Security** — web privacy measurement, tracking ecosystems, consent-modification research (ESORICS 2023)

---

## 🔐 Privacy & Security Work

I'm interested in how **large-scale systems and AI applications handle user data**.

- 📊 Analyzed 100K+ websites for cookie consent behavior and UI dark patterns, published as *Is Initial Consent, Final? Studying the Effect of Consent Modification in Websites* at **ESORICS 2023**.
- 🕵️ Studied **tracking behaviors and data flows** across the Indian web privacy ecosystem.
- 📐 Explored how **AI-driven personalization** intersects with transparency and compliance.
- 🔍 Built Python multi-threaded pipelines to **measure privacy signals at scale**.

This work informs how I design backend and AI systems that prioritize **user trust, compliance, and responsible data use**.

---

## 🏗️ Featured Projects

### 🛰️ SS&C AI Gateway & Knowledge Platform *(current work)*
**Internal LLM platform routing 1.8B+ tokens/day for 10K+ users**

- 🚦 **LiteLLM**-based gateway unifying self-hosted (Llama / Qwen / DeepSeek) and cloud LLMs behind per-request guardrails and audit logging
- 🧠 Distributed **KG + RAG** knowledge layer across **5 product units** (ingest, dedup, hybrid index + retrieval, eval) on Kubernetes microservices
- 🔧 **MCP servers** wrapping internal libraries as schema-validated tools for LLM agents across **4 engineering teams**

---

### 🧩 Sage — Federated Knowledge Retrieval Layer
**Making team docs AI-queryable in place, with citations**

- 🔎 Citation-preserving hybrid retrieval resolver (**BM25 + vector + RRF fusion**) over a 191-page corpus
- 🛡️ Governed rails gate plus **MCP and CLI** surfaces
- 📊 Validated by a **golden-set eval** so every answer clears a measurable quality bar

---

### 🗄️ DBMS Storage Engine (C++)
**File-aware buffer pool, LRU, B+Tree, page-level concurrency**

- 🧱 **4KB heap-file pages** with LRU eviction, pin/unpin, and dirty-page flushing
- 🌲 **B+Tree indexing** and page-level concurrency primitives for recovery-friendly write paths
- ⚙️ Inspired by PostgreSQL storage internals

🔗 https://github.com/rohithkumar27/COMPSCI-645-DB-Design

---

### ⚡ DistServe — Disaggregated LLM Serving
**Separating prefill and decode across GPUs**

- 🧩 Disaggregated inference so long prefills stop starving decode
- 📈 **TTFT / TPOT improved ~25%** under latency SLOs
- 🚦 Multi-stage scheduler with **bandwidth-aware KV-cache transfer**

🔗 https://github.com/rohithkumar27/DistServeSystem

---

### 🎙️ Slide Scribe — *HackUMass XIII Winner*
**Accessibility-focused classroom agent for visually impaired students**

- 📱 **Flutter** cross-platform mobile client over an **AWS Lambda / S3** OCR + LLM backend
- 🗣️ Real-time voice-driven Q&A on live lecture slides via ElevenLabs (~500ms latency, 95% OCR accuracy)
- 🏆 Won **MLH Best Use of ElevenLabs** from 300+ teams

🔗 https://github.com/SuyashManiyar/HackUMass_codebase

---

### ⚖️ Meta-Enriched RAG for Legal LLMs
**Research-grade Retrieval-Augmented Generation system**

- 🧠 Metadata-aware context chunking and **FAISS-based hybrid (dense + lexical) retrieval** over legal documents
- 📈 **Recall@8 up +23%** on legal retrieval benchmarks
- 🔬 Applied **LoRA fine-tuning and DPO** on Aus LegalQA; **BERTScore F1 up +5%**

🔗 https://github.com/SuyashManiyar/meta-enriched-rag-for-legal-llms

---

### 📊 MCP LLM Analytics Agent (Publicis Sapient / Lloyds)
**Schema-aware SQL agent over enterprise pricing systems**

- 🤖 MCP-based analytics agent (**Gemini / OpenAI**) with schema-aware SQL generation, guardrails, and read-only execution
- ⏱️ Cut ad-hoc reporting cycle time **~60%** across **5+ product teams**
- 🔐 Audit logging and I/O validation for safely-callable internal APIs

---

### 🛒 UniTrade — Campus Marketplace
**Full-stack two-sided marketplace with real-time auctions**

- 🧩 Built with **Next.js, TypeScript, Node.js/Express, PostgreSQL**
- 🔄 Real-time auctions via **Socket.IO** and Gemini-powered AI semantic search
- 🔐 Secure APIs with admin moderation and access controls

🔗 https://github.com/rohithkumar27/UniTrade-Campus-Marketplace

---

## 🛠️ Tech Stack

**Languages**
Python · Java · TypeScript · C++ · SQL · JavaScript · Go

**Backend & Systems**
Spring Boot · Node.js · FastAPI · Kafka · Apache Spark · REST · gRPC · Microservices

**☁️ Cloud & Infra**
AWS (EKS, RDS, S3, Lambda) · Docker · Kubernetes · Helm · CI/CD · Grafana · Prometheus

**🤖 LLM & AI**
MCP · LangChain · LangGraph · LiteLLM · RAG · Knowledge Graphs · FAISS · PyTorch · Hugging Face · LoRA / DPO

**Databases & Storage**
PostgreSQL · MongoDB · Redis · Vector Stores · B+Tree Indexing · Partitioning

---

## 🎯 Open To
**New Grad Software Engineer roles, starting Jan / Feb 2027** (Dec 2026 graduation)
Backend • Distributed Systems • LLM Platforms & Agent Infrastructure • Applied AI • Cloud

🔗 LinkedIn: https://www.linkedin.com/in/rohithkumar27/

---

⭐ If you're interested in distributed backend systems, LLM platforms, or agent infrastructure, feel free to explore my repositories or reach out.

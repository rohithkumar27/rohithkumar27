<h1 align="center">Hi, I'm Rohith 👋</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/rohithkumar27/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:rohit.tumati@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://rohithkumar27.github.io/"><img src="https://img.shields.io/badge/Portfolio-24292E?style=for-the-badge&logo=github&logoColor=white" alt="Portfolio"/></a>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1200&color=00D9FF&center=true&vCenter=true&width=760&lines=Distributed+Backend+Systems;LLM+Platforms+%26+Agent+Infrastructure;Cloud-Native+Services;Currently+shipping+at+1.8B%2B+tokens%2Fday" alt="Typing SVG"/>
</p>

---

## 🧠 About Me

> I build **distributed backend platforms**, **LLM agent infrastructure**, and **cloud-native services**, most recently an internal AI gateway routing **1.8B+ tokens/day** and a federated knowledge platform spanning five product units.

- 🎓 **MS Computer Science @ UMass Amherst** (Sep 2025 – Dec 2026), CGPA **4.0 / 4.0**
- 🎯 **Open to New Grad SWE roles**, starting **Jan / Feb 2027**
- 💡 Interests: distributed storage, retrieval systems, agent infra, developer platforms
- 📍 Currently in **Boston, MA**

---

## 🚀 What I'm Up To

| | |
|---|---|
| 🛰️ **Currently @ SS&C Technologies** | AI gateway (LiteLLM, 1.8B+ tokens/day), KG + RAG platform, MCP tool servers |
| 🧪 **Recent research** | Disaggregated LLM serving (DistServe), file-aware DBMS storage engine, hybrid retrieval (BM25 + vector + RRF) |
| 🎤 **Ask me about** | MCP, LangGraph, RAG evaluation, Postgres partitioning, JVM tuning |
| 🏆 **Recent wins** | HackUMass XIII Winner (2025), ESORICS 2023 publication, AMTI AIR 9 |

---

## 💼 Experience

<table>
<tr>
<td width="130"><strong>Currently</strong></td>
<td>
🛰️ <strong>Software Engineer Intern</strong> — <em>SS&C Technologies, ACE Lab &amp; QE CoE Labs</em> (Boston, MA)<br>
<sub>AI gateway · MCP tool platform · KG + RAG knowledge layer · agentic QE</sub>
</td>
</tr>
<tr>
<td><strong>Prev</strong></td>
<td>
🏦 <strong>Software Development Engineer</strong> — <em>Publicis Sapient (Lloyds Banking Group, UK)</em><br>
<sub>Cloud-native pricing platform serving 1M+ merchants · £450K annual revenue</sub>
</td>
</tr>
<tr>
<td><strong>Prev</strong></td>
<td>
🐣 <strong>Founding Software Engineer</strong> — <em>CREW (SKDIV Industries)</em><br>
<sub>Event-driven backend + ML recommendation pipeline for a 10K+ user social platform</sub>
</td>
</tr>
</table>

---

## 🏆 Achievements

<p align="center">
  <img src="https://img.shields.io/badge/🥇_HackUMass_XIII-Winner_2025-FFD700?style=for-the-badge&labelColor=1E1E2E" alt="HackUMass Winner"/>
  <img src="https://img.shields.io/badge/📄_ESORICS-2023_Publication-4B0082?style=for-the-badge&labelColor=1E1E2E" alt="ESORICS"/>
  <img src="https://img.shields.io/badge/🧮_AMTI_Math_Olympiad-AIR_9-C41E3A?style=for-the-badge&labelColor=1E1E2E" alt="AMTI"/>
  <img src="https://img.shields.io/badge/🎯_JEE_Advanced-AIR_1295-1976D2?style=for-the-badge&labelColor=1E1E2E" alt="JEE"/>
</p>

- 🏆 **HackUMass XIII Winner (2025)** — MLH Best Use of ElevenLabs, from 300+ teams *(Slide Scribe, accessibility classroom agent)*
- 📄 **ESORICS 2023 Publication** — *Is Initial Consent, Final? Studying the Effect of Consent Modification in Websites* (peer-reviewed systems security venue)
- 🧮 **AMTI National Mathematics Olympiad, All India Rank 9** (Association of Mathematics Teachers of India, 2015)
- 🎯 **JEE Advanced, All India Rank 1295** (2019, top 160K of ~1M candidates for one of India's most competitive undergraduate entrance exams)
- 🎓 **CGPA 4.0 / 4.0** at UMass Amherst (MS CS, in progress) · **CGPA 3.5 / 4.0** at IIT Gandhinagar (BTech CSE)

---

## 🏗️ Featured Projects

### 🛰️ SS&C AI Gateway & Knowledge Platform *(current work)*
> Internal LLM platform routing **1.8B+ tokens/day** for **10K+ users**

- 🚦 **LiteLLM**-based gateway unifying self-hosted (Llama / Qwen / DeepSeek) and cloud LLMs behind per-request guardrails and audit logging
- 🧠 Distributed **KG + RAG** knowledge layer across **5 product units** (ingest, dedup, hybrid index + retrieval, eval) on Kubernetes microservices
- 🔧 **MCP servers** wrapping internal libraries as schema-validated tools for LLM agents across **4 engineering teams**

---

### 🧩 [Sage](#) — Federated Knowledge Retrieval Layer
> Making team docs AI-queryable in place, with citations

- 🔎 Citation-preserving hybrid retrieval resolver (**BM25 + vector + RRF fusion**) over a 191-page corpus
- 🛡️ Governed rails gate plus **MCP and CLI** surfaces
- 📊 Validated by a **golden-set eval** so every answer clears a measurable quality bar

---

### 🗄️ [DBMS Storage Engine (C++)](https://github.com/rohithkumar27/COMPSCI-645-DB-Design)
> File-aware buffer pool, LRU, B+Tree, page-level concurrency

- 🧱 **4KB heap-file pages** with LRU eviction, pin/unpin, and dirty-page flushing
- 🌲 **B+Tree indexing** and page-level concurrency primitives for recovery-friendly write paths
- ⚙️ Inspired by PostgreSQL storage internals

---

### ⚡ [DistServe](https://github.com/rohithkumar27/DistServeSystem) — Disaggregated LLM Serving
> Separating prefill and decode across GPUs

- 🧩 Disaggregated inference so long prefills stop starving decode
- 📈 **TTFT / TPOT improved ~25%** under latency SLOs
- 🚦 Multi-stage scheduler with **bandwidth-aware KV-cache transfer**

---

### 🎙️ [Slide Scribe](https://github.com/SuyashManiyar/HackUMass_codebase) — *HackUMass XIII Winner*
> Accessibility-focused classroom agent for visually impaired students

- 📱 **Flutter** cross-platform mobile client over an **AWS Lambda / S3** OCR + LLM backend
- 🗣️ Real-time voice-driven Q&A on live lecture slides via **ElevenLabs** (~500 ms latency, 95% OCR accuracy)
- 🏆 Won **MLH Best Use of ElevenLabs** from 300+ teams

---

### ⚖️ [Meta-Enriched RAG for Legal LLMs](https://github.com/SuyashManiyar/meta-enriched-rag-for-legal-llms)
> Research-grade Retrieval-Augmented Generation system

- 🧠 Metadata-aware context chunking + **FAISS hybrid (dense + lexical) retrieval**
- 📈 **Recall@8 up +23%** on legal retrieval benchmarks
- 🔬 **LoRA fine-tuning + DPO** on Aus LegalQA; **BERTScore F1 up +5%**

---

### 📊 MCP LLM Analytics Agent (Publicis Sapient / Lloyds)
> Schema-aware SQL agent over enterprise pricing systems

- 🤖 MCP-based analytics agent (**Gemini / OpenAI**) with schema-aware SQL generation, guardrails, and read-only execution
- ⏱️ Cut ad-hoc reporting cycle time **~60%** across **5+ product teams**

---

### 🛒 [UniTrade](https://github.com/rohithkumar27/UniTrade-Campus-Marketplace) — Campus Marketplace
> Full-stack two-sided marketplace with real-time auctions

- 🧩 **Next.js · TypeScript · Node.js/Express · PostgreSQL**
- 🔄 Real-time auctions via **Socket.IO** and Gemini-powered AI semantic search

---

## 🛠️ Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)

### Backend & Systems
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![gRPC](https://img.shields.io/badge/gRPC-4B9CD3?style=for-the-badge&logo=grpc&logoColor=white)

### LLM / AI
![LangChain](https://img.shields.io/badge/LangChain-1C3A2E?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-2E7D32?style=for-the-badge&logo=langgraph&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![FAISS](https://img.shields.io/badge/FAISS-0668E1?style=for-the-badge&logo=meta&logoColor=white)

### Cloud & Infra
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)

### Databases
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

---

## 📊 GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=rohithkumar27&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rohithkumar27&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=rohithkumar27&theme=tokyonight&hide_border=true" alt="Streak Stats"/>
</p>

---

## 🔐 Privacy & Security Work

Interested in how large-scale systems and AI applications handle user data.

- 📊 Analyzed **100K+ websites** for cookie consent behavior and UI dark patterns → *Is Initial Consent, Final? Studying the Effect of Consent Modification in Websites*, **ESORICS 2023**
- 🕵️ Studied tracking behaviors and data flows across the Indian web privacy ecosystem
- 🔍 Built Python multi-threaded pipelines to measure privacy signals at scale

---

## 🎯 Currently Open To

<p align="center">
  <strong>New Grad Software Engineer roles · Starting Jan / Feb 2027</strong><br>
  <sub>Backend · Distributed Systems · LLM Platforms · Agent Infrastructure · Applied AI · Cloud</sub>
</p>

<p align="center">
  <a href="mailto:rohit.tumati@gmail.com"><img src="https://img.shields.io/badge/Say_Hello-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://www.linkedin.com/in/rohithkumar27/"><img src="https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</p>

<p align="center">
  <sub>⭐ Interested in distributed backend systems, LLM platforms, or agent infra? Explore the repos or reach out.</sub>
</p>

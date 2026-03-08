<div align="center">

# Zain Abbas
### AI Software Engineer · Systems Architect · Published Researcher

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zainabbas313)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/zainabbas313)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white)](https://www.kaggle.com/zainabbas110)
[![IEEE Paper](https://img.shields.io/badge/IEEE_Xplore-Published-00629B?style=flat-square&logo=ieee&logoColor=white)](https://lnkd.in/dMJYy3nt)

</div>

---

## About

AI Software Engineer currently at **Codet AI** (Nov 2025–Present), building production-grade ML systems and LLM-powered applications. My work spans agentic AI infrastructure, distributed backend systems, and applied deep learning — from multi-agent orchestration pipelines and multi-tenant SaaS architectures to in-database ML extension design.

Previously **Associate AI Engineer at Netpace Inc.** (California, Jul–Nov 2025) and **AI Engineer at DreamSleep** (Jan–May 2025, Chicago), where I designed FastAPI-based AI services on GCP with LangGraph agentic workflows, knowledge graph reasoning, ontology-driven inference (OWL), and multi-tenant isolation.

**BSc Computer Science — FAST-NUCES Karachi** (2021–2025). Teaching Assistant for Graph Theory and Data Structures across 1.5 years. **IEEE-published researcher**, presented at C-CODE'25.

---

## Current Role

**AI Software Engineer — Codet AI** *(Nov 2025 – Present · Hybrid)*

- Large language model integration and prompt engineering for production workflows
- ML pipeline design for scalable AI-powered products
- Agentic system design with LangGraph and Autogen
- Backend systems with FastAPI, Spring Boot, and .NET

---

## Published Research

### Multi-Modal Image Fusion for Enhanced Multi-Class Diagnosis of Cardiovascular Diseases Using Deep Learning
**IEEE Xplore · C-CODE'25 · Bahria University, Islamabad · Oct 29, 2025**  
*Co-authors: Mohammad Haseeb, Hasan Mehdavi · Supervisor: Ms. Sania Urooj*  
**→ [[Full Paper on IEEE Xplore]](https://lnkd.in/dMJYy3nt)**

Proposed a deep learning diagnostic framework that addresses the core limitation of single-modality ECG analysis. The pipeline transforms 1D ECG signals into four complementary 2D visual representations — **Gramian Angular Fields (GAF)**, **Markov Transition Fields (MTF)**, **Recurrence Plots (RP)**, and **Time-Frequency Representations (TFR)** — which are fused and classified via a **ResNet50** backbone.

The system performs multi-class diagnosis of **Myocardial Infarction (MI)**, **Coronary Artery Disease (CAD)**, **Congestive Heart Failure (CHF)**, and **Arrhythmia**, achieving **99.75% accuracy** — among the highest reported for multi-class CVD detection in the literature.

Integrated **Explainable AI (XAI)** via Grad-CAM spatial saliency and SHAP global attribution to provide clinical interpretability, targeting physician trust and diagnostic transparency in real-world deployment.

---

## Technical Focus

**Agentic AI & LLM Systems**
- Multi-agent orchestration: LangGraph stateful graphs, Autogen role-based agents, tool-use and memory persistence
- RAG pipelines: document ingestion, chunking, vector indexing (FAISS, HNSW, pgvector), hybrid retrieval and re-ranking
- Knowledge graph construction with OWL ontologies for semantic reasoning and context-aware AI
- LLM integration across OpenAI, Anthropic (Claude), Groq, Gemini — structured outputs, streaming, function calling
- LLM policy design: access control layers, prompt-level guardrails, and policy enforcement within agentic pipelines

**Security, Access Control & Policy**
- RBAC, ABAC, PBAC, and IAM policy design for multi-tenant and enterprise systems
- Fine-grained permission modeling: role hierarchies, attribute-based conditions, resource-scoped policies
- Policy engines for runtime authorization — separating business rules from application logic
- Row-level security, schema isolation, and JWT-scoped access for SaaS architectures

**Data Infrastructure & Storage Architecture**
- In-database ML via PostgreSQL extension design (CSQLNN v3): GPU acceleration, fused operator kernels, modern optimizers — zero-copy inference without data movement
- YugabyteDB for distributed SQL: horizontal scalability, fault tolerance, PostgreSQL-compatible workloads
- EAV (Entity–Attribute–Value) modeling for high-cardinality, sparse-domain data
- Canonical data modeling and normalization strategies for analytical workloads
- Database sharding, horizontal partitioning, and large-scale storage design
- Probabilistic data structures: Bloom Filters for membership testing, HyperLogLog for approximate cardinality at scale

**Distributed & Backend Systems**
- Multi-tenant SaaS architecture: schema-per-tenant isolation, row-level security, RBAC, connection pooling
- FastAPI async services: JWT auth, WebSocket messaging, REST API design
- GCP deployment: Cloud Buckets, Cloud Run, Pub/Sub event pipelines, scalable compute, CI/CD
- Java Spring Boot and C# .NET for enterprise backend systems
- TypeScript Isolates (V8) for sandboxed, multi-tenant code execution with strict resource and scope boundaries

**Voice AI**
- Retell AI for production-grade conversational voice agents: call flows, interruption handling, latency optimization
- ElevenLabs TTS for real-time streaming voice synthesis integrated into LLM pipelines

**Code Intelligence & Graph Systems**
- Repository graph construction using hypergraph strategies for multi-way code relationship modeling
- LVSA on code graphs: random walks, graph embeddings, hierarchical indexing and paging
- Retrieval optimization: Bloom Filter gating, HyperLogLog-based cardinality estimation

**Compilation & Runtime**
- Python → WebAssembly (WASM) compiler: AST transformation, type lowering, memory layout, binary encoding
- Runtime execution semantics for compiled bytecode in constrained environments

**AI-Native Development Platforms**
- Building and shipping on Replit, Lovable, and Atoms.dev — AI-accelerated full-stack development and rapid prototyping

---

## Key Projects

### [`Researchify`](https://www.researchify.app) — AI Research Platform
A free-to-use AI platform that thinks like a researcher, not just writes like one. Researchify goes beyond LLM content generation — it finds references, builds research context, resolves ambiguities by asking clarifying questions, and synthesizes literature end-to-end. It acts as a co-author: the idea, hypothesis, and intellectual leadership remain yours; Researchify handles the research vocabulary, citation structure, and paper construction. Built for the era where researchers only need to think — not spend time mastering academic writing conventions or hiring ghostwriters.

**[→ www.researchify.app](https://www.researchify.app)**

### [`CSQLNN`](https://github.com/zainabbas313) — In-Database Neural Network Engine
Ground-up redesign of a PostgreSQL extension for native neural network inference inside the database. v3 eliminates data movement overhead via GPU acceleration, fused kernels, and modern optimizer support — targeting zero-copy inference for latency-critical analytical workloads.

### [`Agentic-Scraping-Workflow`](https://github.com/zainabbas313/Agentic-Scraping-Workflow)
Multi-engine orchestration for large-scale web data acquisition. Adaptive routing across Playwright, Selenium, Scrapy, and Pyppeteer with session-aware cookie lifecycle management and structured output extraction. Fault-tolerant design for production pipelines.

### `DreamSleep AI Platform` *(Proprietary)*
Full AI backend stack on GCP: FastAPI services, LangGraph agentic workflows with persistent memory, multi-tenant isolation, RBAC, OWL-based knowledge graph reasoning, and RAG-powered retrieval.

### [`VECTOR-SPACE-MODEL-FOR-INFORMATION-RETRIEVAL`](https://github.com/zainabbas313/VECTOR-SPACE-MODEL-FOR-INFORMATION-RETRIEVAL)
TF-IDF and cosine similarity IR system with inverted index construction, query preprocessing, and ranked retrieval — foundational implementation underlying modern embedding search.

### `VOICE-GENERATION-PROJECT`
Real-time AI voice conversation system integrating Groq LLM API with ElevenLabs TTS. Low-latency streaming synthesis, turn-taking logic, and session state management.

---

## Research & Experimentation

| Domain | Work |
|---|---|
| Biomedical AI | IEEE-published multimodal CVD diagnosis — ECG signal fusion via GAF/MTF/RP/TFR → ResNet50 + XAI |
| Time-Series Forecasting | S&P 500 return prediction and position-sizing (Hull Tactical — Kaggle) |
| OCR & Document Intelligence | PaddleOCR/TrOCR pipelines for manufacturing inspection sheet digitization |
| Information Retrieval | Vector space models, ANN indexing, probabilistic filters at scale |
| In-Database ML | PostgreSQL extension for native model inference without data movement |
| Generative AI | Diffusion models and GAN architectures for domain-specific generation |

---

## Experience

```
Nov 2025 – Present    AI Software Engineer         @ Codet AI (Hybrid)
Jul 2025 – Nov 2025   Associate AI Engineer        @ Netpace Inc. (Hybrid)
Jan 2025 – May 2025   AI Engineer I                @ DreamSleep (Chicago, Remote)
Aug 2024 – Jan 2025   AI Engineer (Intern)         @ DreamSleep (Remote)
Oct 2024 – Jan 2025   Full Stack Engineer (Intern) @ Talverse (On-site)
Aug 2024 – Jan 2025   Teaching Assistant           @ FAST-NUCES (Graph Theory)
Sep 2023 – Jul 2024   Teaching Assistant           @ FAST-NUCES (Data Structures)
```

---

## Stack

```
LLM / Agents    │ LangGraph · Autogen · LangChain · OpenAI · Anthropic (Claude) · Groq · Gemini
ML / DL         │ PyTorch · TensorFlow · ResNet · GANs · Diffusion Models
Voice AI        │ Retell AI · ElevenLabs
Backend         │ FastAPI · Spring Boot · .NET · REST · WebSocket · JWT · TypeScript Isolates (V8)
Auth / Policy   │ RBAC · ABAC · PBAC · IAM · Policy Engines · LLM Policy · Row-Level Security
Data / Storage  │ PostgreSQL · YugabyteDB · pgvector · Redis · SQL/NoSQL · GCP Cloud Storage
Messaging       │ GCP Pub/Sub · Event-driven architecture · Async task queues
Payments        │ Stripe (Subscriptions · Webhooks · Billing)
Cloud / DevOps  │ GCP · Docker · CI/CD · Cloud Run
AI Dev Tools    │ Replit · Lovable · Atoms.dev
Languages       │ Python · Java · C# · C · TypeScript
```

---

<div align="center">

**`Building systems that think, retrieve, and scale.`**

[github.com/zainabbas313](https://github.com/zainabbas313) · [kaggle.com/zainabbas110](https://www.kaggle.com/zainabbas110) · [linkedin.com/in/zainabbas313](https://www.linkedin.com/in/zainabbas313) · [IEEE Paper](https://lnkd.in/dMJYy3nt)

</div>
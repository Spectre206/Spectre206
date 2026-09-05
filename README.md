<h1 align="center">Hi, I'm Muhammad Adeel 👋</h1>
<h3 align="center">Computer Science Student | AI & Backend Developer | Distributed & Agentic Systems</h3>

<p align="center">
Building intelligent, reliable, and scalable software systems — with a focus on AI, backend engineering, distributed systems, and agentic architectures that run efficiently on commodity hardware.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/muhammad-adeel-174517297/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/Spectre206">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

---

### 🚀 Currently Working On

**Distributed Multi-Agent Coordination for Self-Healing Data Pipelines**
*A Human-in-the-Loop Approach Based on Commodity Hardware — Final Year Project, In Progress*

A hybrid multi-agent framework for detecting, diagnosing, and responding to anomalies in streaming data pipelines — exploring how agentic AI can improve reliability and self-healing in distributed systems without expensive infrastructure. Full architecture breakdown below in **Featured Projects** ⬇️

---

### 🔭 Featured Projects

#### 🧠 [Distributed Multi-Agent Self-Healing Data Pipelines](https://github.com/Spectre206/fyp-pipeline) ![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat-square)
*Final Year Project — hybrid multi-agent framework for streaming pipeline reliability on a 3-node commodity cluster*

A three-layer system where detection, agentic reasoning, and human-in-the-loop remediation work together to keep streaming pipelines self-healing:
- **Layer 1 — Detection:** five parallel anomaly detectors (Isolation Forest, Z-Score, Moving Average, Random Forest, PSI) fused through a correlation engine
- **Layer 2 — Reasoning:** Triage, Strategy, Policy & Learning agents coordinating over a RAG-backed knowledge base
- **Layer 3 — Action:** automated remediation with a human-in-the-loop dashboard, monitored via Prometheus & Grafana

🎯 Target MTTA (Mean Time to Acknowledge) ≤ 33s &nbsp;·&nbsp; 📝 Manuscript in preparation — targeting *MDPI Big Data and Cognitive Computing*

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![AI Agents](https://img.shields.io/badge/-AI%20Agents-4B32C3?style=flat-square)
![Distributed Systems](https://img.shields.io/badge/-Distributed%20Systems-2E86AB?style=flat-square)

[![View Repository](https://img.shields.io/badge/View-Repository-2b3137?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Spectre206/fyp-pipeline)

#### 🎓 [CampusCore](https://github.com/Spectre206/campuscore)
*AI-powered education management platform*

A full-featured education management system bringing together academic structure, attendance, assessments, role-based dashboards, and an AI-powered quiz generator into a single Django-based platform — built to run comfortably in local development and scale cleanly with Docker:
- **Academic operations:** Departments, Programs, Courses, Sections, and Enrollments, with attendance workflows for both teachers and students
- **AI Quiz Generator:** Groq-powered quiz generation with a mock provider fallback for offline development
- **REST API v1:** fully documented with OpenAPI, Swagger UI, and ReDoc
- **Async notifications:** in-app and email notifications delivered via Celery
- **Docker-first:** complete Docker & Docker Compose setup for reproducible environments

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Celery](https://img.shields.io/badge/-Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

[![View Repository](https://img.shields.io/badge/View-Repository-2b3137?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Spectre206/campuscore)

#### ✈️ [ResearchPilot](https://github.com/Spectre206/ResearchPilot)
*Evidence-grounded AI research assistant*

An enterprise-grade research assistant for analyzing academic papers and technical literature, built around a hybrid retrieval engine and a deterministic multi-agent verification pipeline:
- **Hybrid Retrieval:** Reciprocal Rank Fusion combining dense vector search (ChromaDB) with sparse keyword scoring (BM25Okapi)
- **4-stage verification pipeline:** Analyst → Evidence → Critic → Report agents working to eliminate hallucinated claims
- **Native tool-calling agent:** autonomous Groq function-calling loop with dynamic model auto-discovery and fallbacks
- **Observability:** SQLite-backed execution tracing with a dedicated `/traces` API endpoint
- **Table & font-aware ingestion:** PyMuPDF-powered layout parsing with automatic Markdown table extraction

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/-Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![ChromaDB](https://img.shields.io/badge/-ChromaDB-orange?style=flat-square)
![Groq](https://img.shields.io/badge/-Groq-purple?style=flat-square)

[![View Repository](https://img.shields.io/badge/View-Repository-2b3137?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Spectre206/ResearchPilot)

#### 📄 [SmartForm](https://github.com/Spectre206/smartform)
*AI-powered form automation & validation, backend-first*

A form automation system that extracts data from uploaded document images via OCR, auto-fills structured forms, and pairs it with a locally-hosted LLM assistant that validates entries and answers questions — no cloud inference dependency:
- **OCR extraction:** Tesseract-based pipeline pulling name, ID number, address, and other fields from CNIC images
- **AI assistant:** local Ollama LLM (qwen3:1.7b) that explains fields, checks for missing data, and highlights errors
- **Fully asynchronous:** OCR and validation run as Celery + Redis background tasks with live HTMX status polling
- **PDF generation:** produces a ready-to-submit, filled application via WeasyPrint

![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=django&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![HTMX](https://img.shields.io/badge/-HTMX-3D72D7?style=flat-square&logo=htmx&logoColor=white)
![Tesseract OCR](https://img.shields.io/badge/-Tesseract%20OCR-4285F4?style=flat-square)
![Ollama](https://img.shields.io/badge/-Ollama-000000?style=flat-square)
![Celery](https://img.shields.io/badge/-Celery-37814A?style=flat-square&logo=celery&logoColor=white)

[![View Repository](https://img.shields.io/badge/View-Repository-2b3137?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Spectre206/smartform)

---

### 🛠️ Technical Toolbox

**Languages**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Backend & Data**
![Django](https://img.shields.io/badge/-Django-092E20?style=flat-square&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/-Django%20REST%20Framework-092E20?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![REST APIs](https://img.shields.io/badge/-REST%20APIs-005571?style=flat-square&logo=fastapi&logoColor=white)

**AI & Machine Learning**
![LLMs](https://img.shields.io/badge/-LLMs-412991?style=flat-square&logo=openai&logoColor=white)
![Agentic Systems](https://img.shields.io/badge/-Agentic%20Systems-4B32C3?style=flat-square)
![RAG](https://img.shields.io/badge/-RAG-8A2BE2?style=flat-square)
![ChromaDB](https://img.shields.io/badge/-ChromaDB-orange?style=flat-square)

**Distributed & Infrastructure**
![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Celery](https://img.shields.io/badge/-Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat-square&logo=github&logoColor=white)

---

### 📚 Currently Learning

- Advanced backend architecture
- Distributed systems
- Multi-agent architectures
- AI-assisted software engineering
- System observability and reliability

---

### 🎯 Long-Term Direction

Growing toward **AI engineering, backend architecture, and distributed systems**, with a continued focus on integrating intelligent agents into real-world production software.

---

### 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Spectre206&show_icons=true&theme=default&hide_border=true" alt="Adeel's GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Spectre206&hide_border=true" alt="GitHub Streak" />
</p>

---

<p align="center"><i>This profile evolves as I build, experiment, and document my work throughout my CS degree.</i></p>

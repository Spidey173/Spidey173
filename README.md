<!-- HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Pruthvi%20R&fontSize=45&fontColor=ff4d4d&animation=fadeIn" />

<h1 align="center">Backend & Data Engineer · Applied LLM Systems</h1>

<p align="center">
  <a href="https://pruthvi-17.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-pruthvi--17.vercel.app-24243e?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/pruthvir173/"><img src="https://img.shields.io/badge/LinkedIn-Connect-ff4d4d?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:pruthvi.r0006@gmail.com"><img src="https://img.shields.io/badge/Email-Hire%20Me-ff4d4d?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

## 👋 About

I build backend and data systems in Python, and I care about the reliability details: dead-letter queues for bad data, atomic stock reservation, verified webhooks, and retrieval that is actually measured instead of assumed to work.

Three internships, plus a set of tested, deployed projects across **data pipelines**, **retrieval / RAG systems**, **event-driven backends** and **full-stack apps**.

> 🔍 **Open to:** Backend, Data Engineering, Full-Stack and AI/GenAI roles. Internship or full-time.

---

## 💼 Experience

**Software Engineer Intern, ElinaAI** · Remote · *Aug 2026 – Sep 2026*
Built and styled React front-desk UI components for appointment and patient tracking. Used AI developer tools (GitHub Copilot, Claude) to speed up drafting, debugging and writing tests.

**AI Automation Intern, Coresium** · Remote · *Apr 2026 – May 2026*
Built n8n automation workflows using REST APIs, with Python scripts to validate data before processing.

**Python Full-Stack Intern, PyGenicArc** · Chitradurga · *Feb 2025 – May 2025*
Led a 4-person intern team building **DailyDrop**, a Flask e-commerce platform. Built authentication, cart, checkout, the admin dashboard and the PostgreSQL schema, and set up GitHub Actions CI with Pytest and Flake8.

---

## 🚀 Featured Projects

### 🏦 [LedgerFlow](https://github.com/Spidey173/LedgerFlow): Banking ETL Pipeline & Warehouse
End-to-end pipeline over **10 banking datasets (~5.87M raw records)**. Chunked streaming, pre-load foreign-key validation, **~720K bad records quarantined** to an audited dead-letter queue, and **~5.15M clean rows** bulk-loaded into PostgreSQL with `COPY`. Customer 360 and branch marts served through FastAPI. **41 Pytest tests**, Airflow DAG, Docker Compose, one-command run.
`Python` `Pandas` `PostgreSQL` `FastAPI` `Airflow` `Docker` · 🔗 [Live API](https://ledgerflow17.vercel.app/docs)

### 🧠 [Chronexa](https://github.com/Spidey173/Chronexa): Work-Memory Search & Action Assistant
Answers questions about past meetings, Slack, email and notes. Hybrid retrieval (**BM25 + dense embeddings fused with RRF**, then **cross-encoder rerank**), strict `as_of` temporal gating so future records can't answer past questions, and calibrated abstention. On 76 unseen dev paraphrases, reranking lifted **Recall@5 from 54% (BM25) to 75%** and MRR from 0.54 to 0.68. Includes a dry-run action assistant that confirms destructive commands and asks to clarify ambiguous names.
`Python` `BM25` `RRF` `FastEmbed` `Cross-Encoder` `Multi-LLM`

### 📄 [Veridocs](https://github.com/Spidey173/Veridocs): Document Q&A with Claim Checking
Chat with PDFs, DOCX and TXT files with clickable page citations. Two-stage retrieval (BM25 + FAISS, RRF, then **cross-encoder rerank**) and sentence-level checks that mark each claim **verified, inferred or unsupported**, including numeric consistency checks. Streams answers over SSE. **78 Pytest tests.**
`Next.js` `FastAPI` `FAISS` `FastEmbed` · 🔗 [Live Demo](https://veridocs-gamma.vercel.app/)

### 🛒 [DailyDrop](https://github.com/Spidey173/Dailydrop): E-Commerce Platform
Internship project, later extended with **Redis Lua atomic stock reservation**, idempotency keys, a transactional outbox with RQ workers, and **Razorpay HMAC** webhook reconciliation. Blueprint + service-layer Flask design, admin dashboard, CI on GitHub Actions. **42 Pytest tests.**
`Flask` `PostgreSQL` `Redis` `Razorpay` · 🔗 [Live Demo](https://dailydrop17.vercel.app/)

### 🔄 [Chronicle](https://github.com/Spidey173/Chronicle): Data Ingestion & Analytics Platform
Ingests CSV, Excel, JSON and REST sources through a validate → quarantine → transform → load pipeline into a normalized 3NF PostgreSQL schema (SQLAlchemy 2.0 + Alembic). Bad records go to a dead-letter quarantine with root-cause logs. FastAPI layer with JWT role-based auth, a Chart.js dashboard, Power BI model + DAX measures, and Terraform for AWS. **36 tests, 81%+ coverage.**
`FastAPI` `PostgreSQL` `SQLAlchemy` `Alembic` `Docker` `Terraform` · 🔗 [Demo](https://chronicle-sigma-ashy.vercel.app/)

### 🤖 [Darkrai](https://github.com/Spidey173/Darkrai): Event-Driven GitHub Automation
HMAC-verified GitHub webhooks with `X-GitHub-Delivery` deduplication, a Redis queue with retries and a **dead-letter queue**, a **Python AST security linter** for PR patches, and an AI PR reviewer with offline fallback. Live WebSocket/SSE dashboard. **26 tests.**
`FastAPI` `Redis` `Next.js` `PostgreSQL` · 🔗 [Live Demo](https://darkrai-one.vercel.app/)

---

## 🧪 More Projects

| Project | What it does | Links |
|---|---|---|
| **[Akari](https://github.com/Spidey173/Akari)** | CLI research agent: takes a topic or arXiv ID, parses the paper (column-aware PyMuPDF, ar5iv fallback), writes a structured briefing, and answers follow-ups via RAG that refuses when the paper doesn't say. Local embeddings, Gemini / Groq / Ollama backends, SQLite session resume. | [Repo](https://github.com/Spidey173/Akari) |
| **[DreamWalls](https://github.com/Spidey173/DreamWalls)** | Paint-shop visualizer: vision LLM reads the room, color-science shortlist (CIE-L\*a\*b\*) picks candidates, an ID-validated gate stops hallucinated shades, then SegFormer / MobileSAM masks recolor walls in 4 Asian Paints shades. | [Repo](https://github.com/Spidey173/DreamWalls) |
| **[CogniStream](https://github.com/Spidey173/CogniStream)** | Real-time facial-affect analytics. Face landmarks run in the browser (zero video upload); only compact JSON telemetry reaches a FastAPI + Neon backend. | [Demo](https://cognistream17.vercel.app/) |
| **[Zyra](https://github.com/Spidey173/Zyra)** | Django social app: feed, 24-hour stories, follows, Fernet-encrypted DMs with optimistic UI and incremental polling, Cloudinary media (~89% smaller payloads). | [Demo](https://zyra17.vercel.app/) |
| **[ChibiBytes](https://github.com/Spidey173/ChibiBytes)** | Anime & movie discovery with watchlists, reviews and a Groq → Gemini fallback chat assistant. Flask blueprints, Neon PostgreSQL, CI against a Postgres container. | [Demo](https://chibibytes.vercel.app/) |
| **[Pixora](https://github.com/Spidey173/Pixora)** | Arcade platform with 17 mini-games, Redis sorted-set leaderboards, auth, telemetry queue and an admin dashboard. | [Demo](https://pixora-17.vercel.app) |
| **[SQL Quest](https://github.com/Spidey173/SQL-Quest)** | 100 SQL challenges in a sandboxed in-memory SQLite runner with an AST validator. | [Demo](https://sql-quest-frontend.vercel.app) |
| **[CourtBook-Pro](https://github.com/Spidey173/CourtBook-Pro)** | Court booking with atomic slot locking and 37 Pytest tests. | [Demo](https://court-book-pro-r6oj.vercel.app/) |

---

## 💻 Tech Stack

| Area | Tools |
|---|---|
| **Backend** | Python · FastAPI · Flask · Django · REST · WebSockets · SSE · JWT |
| **Data** | PostgreSQL · Redis · Pandas · Airflow · SQLAlchemy · Alembic · SQLite |
| **AI / RAG** | FastEmbed · FAISS · Chroma · BM25 · RRF · Cross-Encoder Reranking · Gemini · Groq · Claude · n8n |
| **Frontend** | React · Next.js · TypeScript · Tailwind CSS |
| **Infra & Testing** | Pytest · Docker · GitHub Actions · Terraform · Vercel · Render |

---

## 🎓 Education

**MCA (Online)**, Jain University, Bengaluru · 2025 – 2027 · CGPA 8.45
**Bachelor's in Computer Science**, Davangere University · 2022 – 2025

**Certifications:** Google IT Automation with Python · Meta Full-Stack Developer · Microsoft SQL Server

---

## 🏸 Off the Clock
Shuttlecock and cricket, both taken more seriously than is probably necessary.

---

## 📊 GitHub Stats
<p align="center">
  <img src="https://streak-stats.demolab.com?user=Spidey173&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

<!-- FOOTER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" />

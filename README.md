<!-- HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=220&section=header&text=Pruthvi%20R&fontSize=45&fontColor=ff4d4d&animation=fadeIn" />

<h1 align="center">Backend & Data Engineer · Applied LLM Systems · Real-Time Platforms</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&duration=3000&pause=1200&color=FF4D4D&center=true&vCenter=true&width=750&lines=FastAPI+%7C+Kafka+%7C+Redis+%7C+PostgreSQL;RAG+Pipelines+%7C+Temporal+Retrieval+%7C+Claim+Verification;Atomic+Concurrency+%7C+HMAC-Verified+Webhooks+%7C+DLQs;MCA+%40+Jain+University+2025-27" />
</p>

<p align="center">
  <a href="https://pruthvi-17.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-pruthvi--17.vercel.app-24243e?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/pruthvi-r-48ba9b2b4/"><img src="https://img.shields.io/badge/LinkedIn-Connect-ff4d4d?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:pruthvi.r0006@gmail.com"><img src="https://img.shields.io/badge/Email-Hire%20Me-ff4d4d?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

## 👋 About

I build backend and data systems that hold up under real conditions: checkouts that don't oversell, webhooks that don't double-fire, pipelines that quarantine bad records instead of crashing, and retrieval systems that return the right chunk and say when they can't back a claim.

My work sits where **backend engineering meets data pipelines and applied LLM systems**. I care about the unglamorous parts (idempotency, atomic reservations, dead-letter queues, signature verification, execution isolation, tests) that make a system reliable beyond the demo.

> 🔍 **Open to:** Backend, Data Engineering, Full-Stack, and AI/GenAI internships and junior roles, with the goal of converting to full-time.

---

## 🎓 Currently

- 🏫 **MCA (Online)** at Jain University, Bengaluru (2025–2027) · CGPA **8.45**, built on a BCA foundation (CGPA 8.07)
- 🧠 Deepening system design and distributed-systems fundamentals
- 🛠️ Hardening projects with tests, reproducible setups, and measured results

---

## 💼 Experience

**AI Automation Intern, Coresium** · Remote · *Apr 2026 – May 2026*
Built automation workflows with n8n and REST APIs for client operations. Wrote validation and monitoring scripts to improve workflow reliability, and integrated third-party services into backend systems.

**Python Full-Stack Intern, PyGenicArc** · Remote · *Feb 2025 – May 2025*
Led a 4-person intern team shipping **DailyDrop**, a Flask e-commerce platform. Designed the core backend, database schemas, and checkout REST endpoints.

---

## 🚀 Featured Projects

### 🛒 [DailyDrop](https://github.com/Spidey173/Dailydrop): Flash-Sale Safe E-Commerce Backend
Started as my PyGenicArc internship project (team of 4) and extended with a **Redis Lua atomic stock reservation** (10-minute hold TTL), **client idempotency keys**, a **transactional outbox** feeding RQ workers (invoices, emails), and **Razorpay HMAC-SHA256** webhook reconciliation. Role-based admin console with low-stock alerts. **42 Pytest tests.**
`Flask` `PostgreSQL (Neon)` `Redis` `RQ` `Razorpay`
🔗 [Live Demo](https://daily-drop-nu.vercel.app/)

### 📡 [Chronicle](https://github.com/Spidey173/Chronicle): Event Ingestion & Analytics Platform
Async FastAPI ingestion gateway writing to **partitioned Kafka topics**; consumer groups validate, enrich, and batch-load into a **PostgreSQL star schema**. Malformed payloads go to an audited **dead-letter queue** with error metadata for replay, consumers are idempotent, and Redis handles caching and sliding-window rate limiting. Docker Compose services with GitHub Actions CI and structured JSON logging with correlation IDs.
`FastAPI` `Kafka` `PostgreSQL` `Redis` `Docker Compose` `GitHub Actions`

### 🏦 Banking Data Engineering Pipeline: Medallion ETL & Customer 360
Ingests **5.84M records across 10 banking datasets** with chunked streaming (constant memory). Validators check referential integrity before the database and quarantine **718K invalid records** to an audited DLQ with rejection reasons, leaving about **5.12M curated rows** loaded via native PostgreSQL `COPY`. Customer 360, loan-risk, and fraud-velocity marts are served through FastAPI. **41 Pytest tests**, one-command run (`make run`), Docker Compose, and an Airflow DAG.
`Python` `Pandas` `PostgreSQL` `FastAPI` `Docker` `Airflow` `Pytest`
<!-- TODO: add repo link -->

### 🧠 [Veridocs](https://github.com/Spidey173/InsightPDF): Document Q&A with Claim Verification
Layout-aware parsing with table-preserving chunking, **FastEmbed (ONNX) embeddings**, two-stage retrieval (vector search, then **cross-encoder rerank**), and **sentence-level claim checking** (supported / contradicted / unverifiable). Answers stream over SSE with citations that jump to the exact spot in the PDF viewer. **78 Pytest tests.**
`Next.js 16` `React 19` `FastAPI` `FastEmbed` `Cross-Encoder` `SSE`
🔗 [Live Demo](https://huggingface.co/spaces/Spidey173/insightpdf)

### 🕰️ Chronexa: Temporal Memory Search & Dry-Run Action Assistant
A retrieval engine for work data (email, calendar, Slack, meetings, commits) that enforces **point-in-time (`as_of`) filtering before indexing**, so answers can't leak future information. Uses body-aware **BM25**, sub-query decomposition for date-heavy questions, and **Reciprocal Rank Fusion** with per-document diversification. A deterministic dry-run layer turns requests into validated actions (send email, schedule meeting, create ticket). 100% top-10 recall on its internal benchmark set.
`Python` `BM25` `RRF` `Multi-LLM (Claude / GPT / Gemini / Ollama)`
<!-- TODO: add repo link -->

### 🛡️ [Darkrai](https://github.com/Spidey173/Darkrai): DevSecOps Webhook Automation
Verifies GitHub webhooks with **HMAC-SHA256**, queues work through **Redis with retries and a DLQ**, and runs a custom **Python AST security linter** that flags `eval`/`exec`, `shell=True`, string-formatted SQL, and hard-coded credentials. Declarative rules drive PR labeling, review comments, and Slack alerts, with a live SSE telemetry dashboard. **26 Pytest tests.**
`FastAPI` `Next.js 14` `Redis` `Python AST` `SSE`
🔗 [Live Demo](https://darkrai-one.vercel.app/)

---

## 🧪 More Projects

| Project | What it does | Stack | Links |
|---|---|---|---|
| **[CogniStream](https://github.com/Spidey173/CogniStream.git)** | Real-time vision pipeline: pluggable detectors (YOLOv8, MediaPipe, OpenCV DNN), multi-object tracking, restricted-zone alerts and heatmaps over WebSockets with JWT-authenticated streams and adaptive frame dropping. | React 19, FastAPI, OpenCV, WebSockets | [Demo](https://cogni-stream-plum.vercel.app/) |
| **[SQL Quest](https://github.com/Spidey173/SQL-Quest)** | 100 SQL interview challenges run in a two-phase in-memory SQLite sandbox with an AST validator that blocks destructive statements and enforces timeouts and row caps. | Next.js 16, FastAPI, SQLAlchemy 2.0, Neon, 14 Pytest tests | [Demo](https://sql-quest-frontend.vercel.app) · [API Docs](https://sql-quest-backend.vercel.app/docs) |
| **[Python Quest](https://github.com/Spidey173/Python)** | DSA practice platform with sandboxed Python execution against test suites, an LLM mentor returning structured hints, and JWT auth with XP/streaks. | Next.js 16, FastAPI, Monaco, Groq/Gemini | [Live App](https://python-frontend-ruby.vercel.app/) · [API Docs](https://python-7pu9.vercel.app/api/docs) |
| **[CourtBook-Pro](https://github.com/Spidey173/CourtBook-Pro.git)** | Court booking with atomic slot locking to prevent double-booking and a server-side pricing engine. 37 Pytest tests. | Flask 3, SQLAlchemy 2.0, Neon, Alembic | [Demo](https://courtbook-pro-4c7j.onrender.com/) |
| **[Pixora](https://github.com/Spidey173/Glitch4ce)** | Arcade platform hosting 17 mini-games: postMessage SDK for sandboxed iframes, Redis sorted-set leaderboards, write-behind telemetry batching, and score-rate cheat checks. 37 Pytest tests. | Flask, Redis, PostgreSQL | [Demo](https://glitch4ce.onrender.com/) |
| **[ChibiBytes](https://github.com/Spidey173/ChibiBytes)** | Anime discovery with a write-through catalog that pulls misses from Jikan, a trailer modal, and a Groq/Gemini chatbot that checks the local catalog first. 13 Pytest tests. | Flask, Neon PostgreSQL, Groq, Gemini | [Demo](https://chibibytes.vercel.app/) |
| **[Zyra](https://github.com/Spidey173/Zyra.git)** | Social + real-time messaging: WebSocket DMs, typing indicators, presence, 24h stories, reels. ORM joins eliminate N+1 queries. | Django 5, Channels, Cloudinary | [Demo](https://zyra-fa4v.onrender.com/) |
| **[CoreClicks](https://github.com/Spidey173/CoreClicks.git)** | Link management + clickstream analytics: Redis-cached slug resolution for fast redirects, async geo/device parsing. | Flask, Redis, PostgreSQL, Chart.js | [Demo](https://coreclicks.onrender.com/) |

---

## 🔧 What I've Engineered

The patterns that show up across my projects:

| Concern | How I've handled it | Where |
|---|---|---|
| **Oversell and double-booking** | Redis Lua atomic reservation with hold TTLs; atomic slot locking | DailyDrop, CourtBook-Pro |
| **Duplicate side effects** | Idempotency keys, transactional outbox, idempotent consumers | DailyDrop, Chronicle |
| **Bad data and failures** | Dead-letter queues with audit metadata and replay | Chronicle, Banking Pipeline, Darkrai |
| **Data pipeline design** | Medallion layering, chunked streaming, referential checks before load, native `COPY` | Banking Pipeline |
| **Event streaming** | Partitioned Kafka topics, consumer groups, star-schema loading | Chronicle |
| **Webhook trust** | HMAC-SHA256 signature verification (GitHub, Razorpay) | Darkrai, DailyDrop |
| **Retrieval quality** | Hybrid and two-stage retrieval, reranking, claim-level verification, temporal filtering | Veridocs, Chronexa |
| **Untrusted code and queries** | AST validation, quotas, isolated in-memory execution | Darkrai, SQL Quest, Python Quest |
| **Real-time delivery** | WebSockets, SSE streaming, presence and typing state | Zyra, CogniStream, Darkrai |

---

## 💻 Tech Stack

<p>
  <img src="https://skillicons.dev/icons?i=python,fastapi,django,flask,postgres,sqlite,redis,kafka,react,nextjs,ts,tailwind,docker,git,github,vercel&theme=dark" />
</p>

| Area | Tools |
|---|---|
| **Backend** | Python · FastAPI · Django · Flask · REST APIs · WebSockets · SSE · async I/O · JWT auth |
| **Data & Messaging** | PostgreSQL (Neon) · SQLite · Redis · Kafka · Pandas · Airflow · SQLAlchemy · Alembic · Pydantic |
| **AI / RAG** | FastEmbed · Cross-Encoder Reranking · BM25 · FAISS · Gemini API · Groq · MediaPipe · YOLOv8 · n8n |
| **Frontend** | React 19 · Next.js 16 · TypeScript · Tailwind CSS · Monaco Editor |
| **Testing & Infra** | Pytest · Docker / Compose · Git/GitHub · GitHub Actions · Vercel · Render · Hugging Face Spaces |

---

## 💬 Ask Me About
`Redis Lua reservations` · `Kafka and DLQs` · `medallion pipelines` · `RAG and claim verification` · `webhook security (HMAC)` · `FastAPI` · debugging nightmares 😄

## 🏸 Off the Clock
Shuttlecock and cricket, both taken more seriously than is probably necessary 😌

---

## 📊 GitHub Stats
<p align="center">
  <img src="https://streak-stats.demolab.com?user=Spidey173&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>


<!-- FOOTER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" />

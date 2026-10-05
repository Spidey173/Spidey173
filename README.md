<!-- HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Pruthvi%20R&fontSize=45&fontColor=ff4d4d&animation=fadeIn" />

<h1 align="center">Backend & Data Engineer · Applied LLM Systems</h1>

<p align="center">
  <a href="https://pruthvi-17.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-pruthvi--17.vercel.app-24243e?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/pruthvi-r-48ba9b2b4/"><img src="https://img.shields.io/badge/LinkedIn-Connect-ff4d4d?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:pruthvi.r0006@gmail.com"><img src="https://img.shields.io/badge/Email-Hire%20Me-ff4d4d?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

## 👋 About

MCA student at Jain University, Bengaluru (2025–27, CGPA 8.45). I build backend and data systems and focus on the reliability details: atomic inventory reservation, idempotent checkouts, dead-letter queues for bad data, and verified webhooks.

> 🔍 **Open to:** Backend, Data Engineering, Full-Stack, and AI/GenAI internships and junior roles, with the goal of converting to full-time.

---

## 💼 Experience

**AI Automation Intern, Coresium** · Remote · *Apr 2026 – May 2026*
Built n8n and REST API automation workflows for client operations, plus validation and monitoring scripts.

**Python Full-Stack Intern, PyGenicArc** · Remote · *Feb 2025 – May 2025*
Led a 4-person intern team shipping **DailyDrop**, a Flask e-commerce platform. Designed the core backend, schemas, and checkout endpoints.

---

## 🚀 Featured Projects

### 🏦 [LedgerFlow](https://github.com/Spidey173/LedgerFlow): Banking Data Pipeline
Medallion-style ETL over **5.84M records in 10 banking datasets**. Chunked streaming, referential checks before load, **718K bad records quarantined** to an audited DLQ, and about 5.12M curated rows bulk-loaded with PostgreSQL `COPY`. Customer 360 mart served via FastAPI. **41 Pytest tests**, Airflow DAG, Docker Compose, and one-command run.
`Python` `Pandas` `PostgreSQL` `FastAPI` `Airflow` `Docker`

### 🛒 [DailyDrop](https://github.com/Spidey173/Dailydrop): Oversell-Safe E-Commerce
Internship project extended with **Redis Lua atomic stock reservation**, idempotency keys, a transactional outbox with RQ workers, and **Razorpay HMAC** webhook reconciliation. **42 Pytest tests.**
`Flask` `PostgreSQL` `Redis` `Razorpay` · 🔗 [Live Demo](https://daily-drop-nu.vercel.app/)

### 📡 [Chronicle](https://github.com/Spidey173/Chronicle): Event Ingestion Platform
FastAPI gateway → **partitioned Kafka topics** → consumer groups loading a **PostgreSQL star schema**, with an audited dead-letter queue, idempotent consumers, and Redis rate limiting. Docker Compose and GitHub Actions CI.
`FastAPI` `Kafka` `PostgreSQL` `Redis`

### 🧠 [Veridocs](https://github.com/Spidey173/InsightPDF): Document Q&A with Claim Checking
Two-stage retrieval (embeddings, then **cross-encoder rerank**) plus sentence-level checks that mark claims supported, contradicted, or unverifiable. Streams answers with citations linked to the PDF. **78 Pytest tests.**
`Next.js` `FastAPI` `FastEmbed` · 🔗 [Live Demo](https://huggingface.co/spaces/Spidey173/insightpdf)

---

## 🧪 More Projects

| Project | What it does | Links |
|---|---|---|
| **Chronexa** | Work-memory search with point-in-time (`as_of`) filtering to prevent future-data leakage; BM25 + RRF retrieval and a dry-run action assistant. <!-- TODO: add repo link --> | |
| **[Darkrai](https://github.com/Spidey173/Darkrai)** | HMAC-verified GitHub webhooks, Redis queue with DLQ, and a Python AST security linter. 26 tests. | [Demo](https://darkrai-one.vercel.app/) |
| **[CogniStream](https://github.com/Spidey173/CogniStream.git)** | Real-time video detection and tracking over WebSockets with zone alerts. | [Demo](https://cogni-stream-plum.vercel.app/) |
| **[SQL Quest](https://github.com/Spidey173/SQL-Quest)** | 100 SQL challenges in a sandboxed in-memory SQLite runner with an AST validator. | [Demo](https://sql-quest-frontend.vercel.app) |
| **[Python Quest](https://github.com/Spidey173/Python)** | DSA practice with sandboxed execution and an LLM hint mentor. | [Demo](https://python-frontend-ruby.vercel.app/) |
| **[CourtBook-Pro](https://github.com/Spidey173/CourtBook-Pro.git)** | Court booking with atomic slot locking and 37 Pytest tests. | [Demo](https://courtbook-pro-4c7j.onrender.com/) |
| **[Zyra](https://github.com/Spidey173/Zyra.git)** | Social app with real-time WebSocket messaging, stories, and reels. | [Demo](https://zyra-fa4v.onrender.com/) |

---

## 💻 Tech Stack

| Area | Tools |
|---|---|
| **Backend** | Python · FastAPI · Django · Flask · REST · WebSockets · SSE · JWT |
| **Data** | PostgreSQL · Redis · Kafka · Pandas · Airflow · SQLAlchemy · Alembic |
| **AI / RAG** | FastEmbed · Cross-Encoder Reranking · BM25 · FAISS · Gemini · Groq |
| **Frontend** | React · Next.js · TypeScript · Tailwind CSS |
| **Infra & Testing** | Pytest · Docker · GitHub Actions · Vercel · Render |

---

## 🏸 Off the Clock
Shuttlecock and cricket, both taken more seriously than is probably necessary 😌

<!-- FOOTER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" />

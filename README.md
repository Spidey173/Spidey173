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

I build backend and data systems in Python, and I care about the reliability details: atomic inventory reservation, idempotent checkouts, dead-letter queues for bad data, and verified webhooks. Three internships and a set of tested, deployed projects across data pipelines, retrieval systems and full-stack apps.

> 🔍 **Open to:** Backend, Data Engineering, Full-Stack, and AI/GenAI roles. Internship or full-time.

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

### 🏦 [LedgerFlow](https://github.com/Spidey173/LedgerFlow): Banking Data Pipeline
Medallion-style ETL over **5.84M records in 10 banking datasets**. Chunked streaming, referential checks before load, **718K bad records quarantined** to an audited DLQ, and about 5.12M clean rows bulk-loaded with PostgreSQL `COPY`. Customer 360 mart served via FastAPI. **41 Pytest tests**, Airflow DAG, Docker Compose, and one-command run.
`Python` `Pandas` `PostgreSQL` `FastAPI` `Airflow` `Docker`

### 🧠 [Chronexa](https://github.com/Spidey173/Chronexa): Work-Memory Search Assistant
A personal memory assistant that answers questions about past work, meetings and notes. Point-in-time (`as_of`) filtering keeps future records from answering past questions, with BM25 + RRF retrieval and a dry-run action assistant.
`Python` `BM25` `RRF` `Multi-LLM`

### 📄 [Veridocs](https://github.com/Spidey173/Veridocs.git): Document Q&A with Claim Checking
Two-stage retrieval (embeddings, then **cross-encoder rerank**) plus sentence-level checks that mark claims supported, contradicted, or unverifiable. Streams answers with citations linked to the PDF. **78 Pytest tests.**
`Next.js` `FastAPI` `FastEmbed` · 🔗 [Live Demo](https://veridocs-gamma.vercel.app/))

### 🛒 [DailyDrop](https://github.com/Spidey173/Dailydrop): E-Commerce Platform
Internship project, later extended with **Redis Lua atomic stock reservation**, idempotency keys, a transactional outbox with RQ workers, and **Razorpay HMAC** webhook reconciliation. **42 Pytest tests.**
`Flask` `PostgreSQL` `Redis` `Razorpay` · 🔗 [Live Demo](https://dailydrop17.vercel.app/)

---

## 🧪 More Projects

| Project | What it does | Links |
|---|---|---|
| **[Chronicle](https://github.com/Spidey173/Chronicle)** | Event ingestion: FastAPI gateway → partitioned Kafka topics → consumer groups loading a PostgreSQL star schema, with an audited DLQ, idempotent consumers and Redis rate limiting. | [Demo](https://chronicle-sigma-ashy.vercel.app/) |
| **[Darkrai](https://github.com/Spidey173/Darkrai)** | HMAC-verified GitHub webhooks, Redis queue with DLQ, and a Python AST security linter. 26 tests. | [Demo](https://darkrai-one.vercel.app/) |
| **[CogniStream](https://github.com/Spidey173/CogniStream.git)** | Real-time video detection and tracking over WebSockets with zone alerts. | |
| **[SQL Quest](https://github.com/Spidey173/SQL-Quest)** | 100 SQL challenges in a sandboxed in-memory SQLite runner with an AST validator. | [Demo](https://sql-quest-frontend.vercel.app) |
| **[Python Quest](https://github.com/Spidey173/Python)** | DSA practice with sandboxed execution and an LLM hint mentor. | [Demo](https://python-frontend-ruby.vercel.app/) |
| **[CourtBook-Pro](https://github.com/Spidey173/CourtBook-Pro.git)** | Court booking with atomic slot locking and 37 Pytest tests. | [Demo](https://court-book-pro-r6oj.vercel.app/) |
| **[Zyra](https://github.com/Spidey173/Zyra.git)** | Social app with real-time WebSocket messaging, stories, and reels. | [Demo](https://zyra-fa4v.onrender.com/) |

---

## 💻 Tech Stack

| Area | Tools |
|---|---|
| **Backend** | Python · FastAPI · Flask · REST · WebSockets · SSE · JWT |
| **Data** | PostgreSQL · Redis · Kafka · Pandas · Airflow · SQLAlchemy · Alembic |
| **AI / RAG** | FastEmbed · Cross-Encoder Reranking · BM25 · Gemini · Groq · n8n |
| **Frontend** | React · Next.js · TypeScript · Tailwind CSS |
| **Infra & Testing** | Pytest · Docker · GitHub Actions · Vercel · Render |

---

## 🎓 Education

**MCA**, Jain University, Bengaluru · 2025 – 2027 · CGPA 8.45
**Bachelor's in Computer Science**, Davangere University · 2022 – 2025

---

## 🏸 Off the Clock
Shuttlecock and cricket, both taken more seriously than is probably necessary 

---

## 📊 GitHub Stats
<p align="center">
  <img src="https://streak-stats.demolab.com?user=Spidey173&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Spidey173&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="GitHub Stats" />
</p>

<!-- FOOTER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" />

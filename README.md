<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=180&section=header&text=Pruthvi%20R&fontSize=42&fontColor=ff4d4d&animation=fadeIn" />

<h3 align="center">Backend & Data Engineer · Applied LLM Systems</h3>

<p align="center">
  <a href="https://pruthvi-17.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-pruthvi--17.vercel.app-24243e?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/pruthvir173/"><img src="https://img.shields.io/badge/LinkedIn-Connect-ff4d4d?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:pruthvi.r0006@gmail.com"><img src="https://img.shields.io/badge/Email-Hire%20Me-ff4d4d?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

I build Python backend and data systems and care about the reliability details: dead-letter queues for bad data, atomic stock reservation, verified webhooks, and retrieval that is measured instead of assumed to work.

> 🔍 **Open to:** Backend · Data Engineering · Full-Stack · AI/GenAI roles (internship or full-time)

---

## 📈 Proof, not claims

| 5.87M | 720K | 54% → 75% | 78 |
|:---:|:---:|:---:|:---:|
| banking records processed end to end ([LedgerFlow](https://github.com/Spidey173/LedgerFlow)) | bad rows quarantined to an audited DLQ, 5.15M clean rows loaded via `COPY` | Recall@5 gain from cross-encoder reranking ([Chronexa](https://github.com/Spidey173/Chronexa), dev set) | Pytest tests on a claim-checking RAG app ([Veridocs](https://github.com/Spidey173/Veridocs)) |

---

## 🚀 Featured Projects

### 🏦 [LedgerFlow](https://github.com/Spidey173/LedgerFlow) · Banking ETL Pipeline & Warehouse
10 datasets, chunked streaming, foreign-key checks before load, audited dead-letter queue, PostgreSQL `COPY` bulk loads, Customer 360 marts served by FastAPI. 41 tests, Airflow DAG, Docker Compose.
`Python` `Pandas` `PostgreSQL` `FastAPI` `Airflow` `Docker` · [Live API](https://ledgerflow17.vercel.app/docs)

### 🧠 [Chronexa](https://github.com/Spidey173/Chronexa) · Work-Memory Search & Action Assistant
BM25 + dense embeddings fused with RRF, then cross-encoder rerank. Strict `as_of` gating so future records can't answer past questions, plus calibrated abstention. Dry-run action assistant confirms destructive commands.
`Python` `BM25` `RRF` `FastEmbed` `Cross-Encoder` `LLMs`

### 📄 [Veridocs](https://github.com/Spidey173/Veridocs) · Document Q&A with Claim Checking
Two-stage retrieval with clickable page citations. Every sentence of an answer is marked **verified, inferred or unsupported**, with numeric consistency checks. Streams over SSE.
`Next.js` `FastAPI` `FAISS` `FastEmbed` · [Live Demo](https://veridocs-gamma.vercel.app/)

### 🛒 [DailyDrop](https://github.com/Spidey173/Dailydrop) · E-Commerce Platform
Built during my internship, then extended with Redis Lua atomic stock reservation, idempotency keys, a transactional outbox with RQ workers, and Razorpay HMAC webhook reconciliation. 42 tests, CI on GitHub Actions.
`Flask` `PostgreSQL` `Redis` `Razorpay` · [Live Demo](https://dailydrop17.vercel.app/)

---

<details>
<summary><b>🧪 More projects (8)</b></summary>

<br>

| Project | What it does | Link |
|---|---|---|
| **[Chronicle](https://github.com/Spidey173/Chronicle)** | Ingests CSV, Excel, JSON and REST sources; validates, quarantines bad records, loads a 3NF PostgreSQL schema. JWT role-based FastAPI, Power BI model, Terraform for AWS. 36 tests, 81% coverage. | [Demo](https://chronicle-sigma-ashy.vercel.app/) |
| **[Darkrai](https://github.com/Spidey173/Darkrai)** | HMAC-verified GitHub webhooks, Redis queue with retries and DLQ, Python AST security linter for PRs, live SSE/WebSocket dashboard. 26 tests. | [Demo](https://darkrai-one.vercel.app/) |
| **[Akari](https://github.com/Spidey173/Akari)** | CLI research agent: arXiv paper in, structured briefing out, then RAG Q&A that refuses when the paper doesn't say. Local embeddings, Gemini/Groq/Ollama. | [Repo](https://github.com/Spidey173/Akari) |
| **[DreamWalls](https://github.com/Spidey173/DreamWalls)** | Paint-shop visualizer: vision LLM + color-science shortlist, an ID-validated gate against hallucinated shades, SegFormer wall masks recolored in 4 Asian Paints shades. | [Repo](https://github.com/Spidey173/DreamWalls) |
| **[CogniStream](https://github.com/Spidey173/CogniStream)** | Real-time facial-affect analytics. Landmarks run in the browser, so no video leaves the device. FastAPI + Neon for telemetry. | [Demo](https://cognistream17.vercel.app/) |
| **[Zyra](https://github.com/Spidey173/Zyra)** | Django social app: feed, 24h stories, Fernet-encrypted DMs, Cloudinary media (~89% smaller payloads). | [Demo](https://zyra17.vercel.app/) |
| **[ChibiBytes](https://github.com/Spidey173/ChibiBytes)** | Anime/movie discovery with watchlists and a Groq → Gemini fallback chat assistant. | [Demo](https://chibibytes.vercel.app/) |
| **[Pixora](https://github.com/Spidey173/Pixora)** | Arcade platform: 17 games, Redis leaderboards, auth, admin dashboard. | [Demo](https://pixora-17.vercel.app) |

Also: [SQL Quest](https://github.com/Spidey173/SQL-Quest) (100 SQL challenges in a sandboxed runner, [demo](https://sql-quest-frontend.vercel.app)) and [CourtBook-Pro](https://github.com/Spidey173/CourtBook-Pro) (atomic slot locking, 37 tests, [demo](https://court-book-pro-r6oj.vercel.app/)).

</details>

---

## 💼 Experience

**Software Engineer Intern · ElinaAI** · Remote · *Aug – Sep 2026*
Built React front-desk UI for appointment and patient tracking; used Copilot and Claude to speed up debugging and tests.

**AI Automation Intern · Coresium** · Remote · *Apr – May 2026*
Built n8n workflows over REST APIs, with Python scripts validating data before processing.

**Python Full-Stack Intern · PyGenicArc** · *Feb – May 2025*
Led a 4-person team building DailyDrop: auth, cart, checkout, admin dashboard, PostgreSQL schema, CI with Pytest and Flake8.

---

## 💻 Tech Stack

| | |
|---|---|
| **Backend** | Python · FastAPI · Flask · Django · REST · WebSockets · SSE · JWT |
| **Data** | PostgreSQL · Redis · Pandas · Airflow · SQLAlchemy · Alembic |
| **AI / RAG** | FastEmbed · FAISS · BM25 · RRF · Cross-Encoder Reranking · Gemini · Groq · Claude · n8n |
| **Frontend** | React · Next.js · TypeScript · Tailwind CSS |
| **Infra & Testing** | Pytest · Docker · GitHub Actions · Terraform · Vercel · Render |

---

## 🎓 Education

**MCA (Online)**, Jain University · 2025 – 2027 · CGPA 8.45
**Bachelor's in Computer Science**, Davangere University · 2022 – 2025
Certifications: Google IT Automation with Python · Meta Full-Stack Developer · Microsoft SQL Server

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Spidey173&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" />

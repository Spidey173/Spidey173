<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=180&section=header&text=Pruthvi%20R&fontSize=42&fontColor=ff4d4d&animation=fadeIn" />

<h3 align="center">Backend & Data Engineer | Python · PostgreSQL · FastAPI | Applied AI Systems</h3>

<p align="center">
  <a href="https://pruthvi-17.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-pruthvi--17.vercel.app-24243e?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/pruthvir173/"><img src="https://img.shields.io/badge/LinkedIn-Connect-ff4d4d?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:pruthvi.r0006@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-ff4d4d?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

I build Python backend and data systems, with a focus on reliable pipelines, APIs, and applied AI. Recent work includes processing millions of banking records, preventing duplicate or oversold orders, and measuring retrieval quality instead of assuming it works.

> 🔍 **Open to:** Backend Engineering and Data Engineering internships or full-time roles.

---

## 📈 Selected results

| 5.87M | 720K | 54% → 75% | 78 |
|:---:|:---:|:---:|:---:|
| banking records processed end to end in [LedgerFlow](https://github.com/Spidey173/LedgerFlow) | invalid rows quarantined in an audited dead-letter queue; 5.15M clean rows loaded with PostgreSQL `COPY` | Recall@5 on the [Chronexa](https://github.com/Spidey173/Chronexa) development set after cross-encoder reranking | tests in [Veridocs](https://github.com/Spidey173/Veridocs) |

---

## 🚀 Featured projects

### 🏦 [LedgerFlow](https://github.com/Spidey173/LedgerFlow) · Banking ETL pipeline and warehouse
Processes 10 datasets with chunked streaming, foreign-key validation, an audited dead-letter queue, and PostgreSQL `COPY` bulk loads. Serves Customer 360 marts through FastAPI. Includes 41 tests, an Airflow DAG, and Docker Compose.

`Python` `Pandas` `PostgreSQL` `FastAPI` `Airflow` `Docker` · [Live API](https://ledgerflow17.vercel.app/)

### 🧠 [Chronexa](https://github.com/Spidey173/Chronexa) · Work-memory search and action assistant
Combines BM25 and dense retrieval with RRF fusion and cross-encoder reranking. Enforces strict `as_of` filters to prevent future records from answering past questions, supports calibrated abstention, and previews destructive actions before execution.

`Python` `BM25` `RRF` `FastEmbed` `Cross-Encoder` `LLMs` · [Live demo](https://chronexa.streamlit.app/)

### 📄 [Veridocs](https://github.com/Spidey173/Veridocs) · Document Q&A with claim checking
Uses two-stage retrieval and clickable page citations. Labels each answer sentence as **verified, inferred, or unsupported**, checks numeric consistency, and streams results over SSE.

`Next.js` `FastAPI` `FAISS` `FastEmbed` · [Live demo](https://veridocs-gamma.vercel.app/)

### 🛒 [DailyDrop](https://github.com/Spidey173/Dailydrop) · E-commerce platform
Built during my internship and extended with Redis Lua atomic stock reservation, idempotency keys, a transactional outbox with RQ workers, and Razorpay HMAC webhook reconciliation. Includes 42 tests and GitHub Actions CI.

`Flask` `PostgreSQL` `Redis` `Razorpay` · [Live demo](https://dailydrop17.vercel.app/)

---

<details>
<summary><b>🧪 More projects</b></summary>

<br>

| Project | What it does | Link |
|---|---|---|
| **[Chronicle](https://github.com/Spidey173/Chronicle)** | Ingests CSV, Excel, JSON, and REST sources; validates and quarantines bad records; loads a 3NF PostgreSQL schema. Includes JWT role-based access, a Power BI model, AWS Terraform, 36 tests, and 81% coverage. | [Demo](https://chronicle-sigma-ashy.vercel.app/) |
| **[Darkrai](https://github.com/Spidey173/Darkrai)** | Verifies GitHub webhook signatures, processes jobs with Redis retries and a dead-letter queue, lints pull requests with a Python AST security checker, and provides a live SSE/WebSocket dashboard. Includes 26 tests. | [Demo](https://darkrai-one.vercel.app/) |
| **[Akari](https://github.com/Spidey173/Akari)** | CLI research assistant that turns an arXiv paper into a structured briefing, then answers questions with retrieval and abstains when the paper does not support an answer. | [Repository](https://github.com/Spidey173/Akari) |
| **[DreamWalls](https://github.com/Spidey173/DreamWalls)** | Paint visualization app combining a vision model, color-science suggestions, validated shade selection, and SegFormer wall masks. | [Repository](https://github.com/Spidey173/DreamWalls) |
| **[CogniStream](https://github.com/Spidey173/CogniStream)** | Real-time facial-affect analytics with browser-side landmark processing, so video stays on the device, and FastAPI telemetry storage. | [Demo](https://cognistream17.vercel.app/) |
| **[Zyra](https://github.com/Spidey173/Zyra)** | Django social app with a feed, 24-hour stories, encrypted direct messages, and Cloudinary media. | [Demo](https://zyra17.vercel.app/) |
| **[ChibiBytes](https://github.com/Spidey173/ChibiBytes)** | Anime and movie discovery app with watchlists and a chat assistant that can fall back from Groq to Gemini. | [Demo](https://chibibytes.vercel.app/) |
| **[Pixora](https://github.com/Spidey173/Pixora)** | Arcade platform with 17 games, Redis leaderboards, authentication, and an admin dashboard. | [Demo](https://pixora-17.vercel.app/) |
| **[SQL Quest](https://github.com/Spidey173/SQL-Quest)** | Interactive SQL practice with 100 challenges and a sandboxed query runner. | [Demo](https://sql-quest-frontend.vercel.app/) |
| **[CourtBook-Pro](https://github.com/Spidey173/CourtBook-Pro)** | Court-booking system with atomic slot locking and 37 tests. | [Demo](https://court-book-pro-r6oj.vercel.app/) |

</details>

---

## 💼 Experience

**Software Engineer Intern · ElinaAI** · Remote · *Aug – Sep 2026*  
Built a React front-desk interface for appointment and patient tracking; used Copilot and Claude to speed up debugging and tests.

**AI Automation Intern · Coresium** · Remote · *Apr – May 2026*  
Built n8n workflows over REST APIs, with Python scripts validating data before processing.

**Python Full-Stack Intern · PyGenicArc** · *Feb – May 2025*  
Led a four-person team building DailyDrop, including authentication, cart, checkout, admin dashboard, PostgreSQL schema, and CI with Pytest and Flake8.

---

## 💻 Tech stack

| Area | Technologies |
|---|---|
| **Backend** | Python · FastAPI · Flask · Django · REST · WebSockets · SSE · JWT |
| **Data** | PostgreSQL · Redis · Pandas · Airflow · SQLAlchemy · Alembic |
| **Applied AI** | FastEmbed · FAISS · BM25 · RRF · Cross-encoder reranking · Gemini · Groq · Claude |
| **Frontend** | React · Next.js · TypeScript · Tailwind CSS |
| **Infrastructure & testing** | Pytest · Docker · GitHub Actions · Terraform · Vercel · Render |

---

## 🎓 Education

**MCA (Online)** · Jain University · 2025–2027 · CGPA 8.45  
**Bachelor of Computer Science** · Davangere University · 2022–2025  
**Certifications:** Google IT Automation with Python · Meta Full-Stack Developer · Microsoft SQL Server

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Spidey173&theme=tokyonight&hide_border=true" alt="GitHub contribution streak" />
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" alt="" />

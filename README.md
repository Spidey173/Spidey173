<!-- HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=220&section=header&text=Pruthvi%20R&fontSize=45&fontColor=ff4d4d&animation=fadeIn" />

<h1 align="center">Backend Engineer · Applied LLM Systems · Real-Time Platforms</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&duration=3000&pause=1200&color=FF4D4D&center=true&vCenter=true&width=700&lines=RAG+Pipelines+%7C+FastAPI+%7C+FAISS;Event-Driven+Backends+%7C+HMAC-Verified+Webhooks;Sandboxed+Code+Execution+%7C+Real-Time+WebSockets;MCA+%40+Jain+University+2025-27" />
</p>

<p align="center">
  <a href="https://pruthvi-17.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-pruthvi--17.vercel.app-24243e?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/pruthvi-r-48ba9b2b4/"><img src="https://img.shields.io/badge/LinkedIn-Connect-ff4d4d?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:pruthvi.r0006@gmail.com"><img src="https://img.shields.io/badge/Email-Hire%20Me-ff4d4d?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

---

## 👋 About

I build backend systems that hold up under real conditions: webhooks that don't double-fire, retrieval pipelines that return the right chunk, transactions that don't double-book under concurrent writes, and code sandboxes that don't fall over when a user submits an infinite loop.

Most of my work sits where **backend engineering meets applied LLM systems**: RAG pipelines, semantic search, and the unglamorous plumbing (idempotency, signature verification, atomic transactions, execution isolation) that makes AI and real-time features reliable in production, not just in a notebook.

> 🔍 **Open to:** Backend, Full-Stack, and AI/GenAI internships and junior roles, with the goal of converting to full-time.

---

## 🎓 Currently

- 🏫 **MCA (Online)** at Jain University, Bengaluru (2025–2027) · CGPA **8.45**, built on a BCA foundation (CGPA 8.07)
- 🧠 Deepening system design and distributed-systems fundamentals
- 🛠️ Sharpening production-readiness: idempotency, HMAC verification, atomic DB concurrency, token encryption, execution sandboxing

---

## 💼 Experience

**AI Automation Intern, Coresium** · Remote · *Apr 2026 – May 2026*
Built automation workflows with n8n and REST APIs for client operations. Wrote validation and monitoring scripts to improve workflow reliability, and integrated third-party services into backend systems.

**Python Full-Stack Intern, PyGenicArc** · Remote · *Feb 2025 – May 2025*
Led a 4-person intern team shipping **DailyDrop**, a Flask e-commerce platform. Designed the core backend, database schemas, and checkout REST endpoints.

---

## 🚀 Featured Projects

### 🐍 [Python Quest](https://github.com/Spidey173/Python): DSA Practice Platform with AI Mentor
Interactive coding platform for DSA prep: in-browser **sandboxed Python execution** against test suites with strict quotas, an **LLM mentor** (Groq/Gemini) returning structured JSON hints, spoken interview Q&As per problem, and JWT auth with XP/streak tracking.
`Next.js 16` `React 19` `FastAPI` `SQLAlchemy` `Monaco Editor` `Groq/Gemini`
🔗 [Live App](https://python-frontend-ruby.vercel.app/) · [API Docs](https://python-7pu9.vercel.app/api/docs)

### 🗄️ [SQL Quest](https://github.com/Spidey173/SQL-Quest): 100-Challenge SQL Interview Platform
100 curated SQL challenges (joins, subqueries, CTEs, window functions) run in a **two-phase SQLite sandbox** that separates schema DDL from query execution. Includes ASCII mental models, execution-order breakdowns, spoken interview scripts, and streak/acceptance telemetry, deployed serverless on Vercel with Neon PostgreSQL.
`Next.js 16` `FastAPI` `SQLAlchemy 2.0 (Async)` `Neon PostgreSQL` `SQLite` `14 Pytest tests`
🔗 [Live App](https://sql-quest-frontend.vercel.app) · [API Docs](https://sql-quest-backend.vercel.app/docs) · [Health](https://sql-quest-backend.vercel.app/health)

### ⚙️ [CommitForge](https://github.com/Spidey173/CommitForge.git): Event-Driven GitHub Automation
Verifies GitHub webhooks with **HMAC-SHA256**, evaluates rule-based workflows, and automates issue labeling, PR comments, and Slack notifications. Ships with a real-time observability dashboard for event processing and automation history.
`FastAPI` `Next.js` `HMAC-SHA256` `Webhooks`
🔗 [Live Demo](https://commitforge-one.vercel.app/)

### 🧠 [InsightPDF](https://github.com/Spidey173/InsightPDF.git): RAG Document Q&A
Two-stage retrieval (**FAISS + cross-encoder reranker**) with a post-generation **fact-verification layer**, returning cited answers in under 1.5s on fully local CPU inference.
`Next.js 16` `React 19` `FastAPI` `FAISS` `Cross-Encoder`
🔗 [Live Demo](https://huggingface.co/spaces/Spidey173/insightpdf)

### 🏟️ [CourtBook-Pro](https://github.com/Spidey173/CourtBook-Pro.git): Concurrency-Safe Booking Engine
Sports court booking platform with **atomic slot locking** to eliminate race conditions, a server-side pricing engine, and **37 automated Pytest suites**.
`Flask 3` `SQLAlchemy 2.0` `Pydantic` `Neon PostgreSQL` `Alembic`
🔗 [Live Demo](https://courtbook-pro-4c7j.onrender.com/)



---

## 🧪 More Projects

| Project | What it does | Stack | Links |
|---|---|---|---|
| **[Zyra](https://github.com/Spidey173/Zyra.git)** | Social + real-time messaging: sub-30ms WebSocket DMs, typing indicators, presence, 24h stories, reels. ORM joins eliminate N+1 queries. | Django 5, Channels, Cloudinary | [Demo](https://zyra-fa4v.onrender.com/) |
| **[CogniStream](https://github.com/Spidey173/CogniStream.git)** | Real-time facial emotion analyzer: MediaPipe Face Mesh alignment, HSEmotion ONNX inference (8 classes) over WebSockets. | React 19, FastAPI, MediaPipe, ONNX | [Demo](https://cogni-stream-plum.vercel.app/) |
| **[CoreClicks](https://github.com/Spidey173/CoreClicks.git)** | Link management + clickstream analytics: Redis-cached slug resolution for sub-5ms redirects, async geo/device parsing. | Flask, Redis, PostgreSQL, Chart.js | [Demo](https://coreclicks.onrender.com/) |
| **[ChibiBytes](https://github.com/Spidey173/ChibiBytes)** | Anime & movie discovery with pre-warmed cache, admin panel, and a Gemini chatbot that checks the local catalog before hitting the LLM. | Flask, Neon PostgreSQL, Gemini | [Demo](https://chibibytes-vutq.onrender.com) |
| **[DailyDrop](https://github.com/Spidey173/Daily-Drop.git)** | E-commerce with guest + authenticated carts and transactional checkout that prevents inventory double-allocation. *(Internship deliverable, led a team of 4.)* | Flask, SQLite | [Frontend](https://dailydrop-alpha.vercel.app/) · [Full stack](https://daily-drop-c96q-f5su.onrender.com/) |
| **[Glitch4ce](https://github.com/Spidey173/Glitch4ce.git)** | Cyberpunk gaming hub with 10+ retro mini-games, player auth, guest access, and live telemetry. | Flask (App Factory), SQLAlchemy | [Demo](https://glitch4ce.onrender.com/) |

---

## 🔧 What I've Engineered

The patterns that show up across my projects:

| Concern | How I've handled it | Where |
|---|---|---|
| **Webhook trust** | HMAC-SHA256 signature verification, idempotent event handling | CommitForge |
| **Concurrent writes** | Atomic slot locking and transactional inventory allocation | CourtBook-Pro, DailyDrop |
| **Retrieval quality** | Two-stage retrieval (FAISS, then cross-encoder rerank) plus fact verification | InsightPDF |
| **Untrusted code** | Isolated execution runners with quotas (Python) and two-phase in-memory sandbox (SQL) | Python Quest, SQL Quest |
| **Real-time delivery** | WebSocket messaging with presence and typing state | Zyra, CogniStream |
| **Read performance** | Redis-cached lookups, pre-warmed catalog cache, `select_related`/`prefetch_related` | CoreClicks, ChibiBytes, Zyra |
| **Serverless deploys** | FastAPI on Vercel functions with Neon PostgreSQL | SQL Quest, Python Quest |

---

## 💻 Tech Stack

<p>
  <img src="https://skillicons.dev/icons?i=python,fastapi,django,flask,postgres,sqlite,redis,react,nextjs,ts,tailwind,docker,git,github,vercel&theme=dark" />
</p>

| Area | Tools |
|---|---|
| **Backend** | Python · FastAPI · Django · Flask · REST APIs · WebSockets · async I/O · JWT auth |
| **AI / RAG** | FAISS · Cross-Encoder Reranking · Gemini API · Groq · HSEmotion ONNX · MediaPipe · n8n |
| **Data** | PostgreSQL (Neon) · SQLite · Redis · SQLAlchemy · Alembic · Pydantic |
| **Frontend** | React 19 · Next.js 16 · TypeScript · Tailwind CSS · Monaco Editor |
| **Testing & Infra** | Pytest · Docker · Git/GitHub · GitHub Actions · Vercel · Render · Hugging Face Spaces |

---

## 💬 Ask Me About
`RAG pipelines` · `FastAPI` · `event-driven systems` · `webhook security (HMAC)` · `sandboxed code execution` · `WebSockets` · debugging nightmares 😄

## 🏸 Off the Clock
Shuttlecock and cricket, both taken more seriously than is probably necessary 😌

---

## 📊 GitHub Stats
<p align="center">
  <img src="https://streak-stats.demolab.com?user=Spidey173&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>


<!-- FOOTER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=120&section=footer" />

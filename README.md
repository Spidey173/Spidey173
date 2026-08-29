<!-- HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=220&section=header&text=Pruthvi%20R&fontSize=45&fontColor=ff4d4d&animation=fadeIn" />

<h1 align="center">Python Backend Developer, building with LLMs</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=20&duration=3000&pause=1200&color=FF4D4D&center=true&vCenter=true&width=650&lines=RAG+Pipelines+%7C+FastAPI+%7C+FAISS;Event-Driven+Backends+%7C+HMAC-Verified+Webhooks;Real-Time+Systems+with+WebSockets;MCA+%40+Jain+University+2025-27" />
</p>

---

I build backend systems that hold up under real conditions — webhooks that don't double-fire, retrieval pipelines that return the right chunk, transactions that don't double-book under concurrent writes.

Most of my recent work sits at the intersection of **backend engineering** and **applied LLM systems**: RAG pipelines, semantic search, and the plumbing (idempotency, signature verification, atomic transactions) that makes AI and real-time features actually reliable in production, not just in a notebook.

---

## 🎓 Currently

- 🏫 Pursuing MCA at Jain University, Bengaluru (2025–2027) — CGPA 8.45, on a BCA foundation (CGPA 8.07)
- 🔍 Actively looking for backend, full-stack, or AI/GenAI internship & junior engineering roles
- 🧠 Deepening system design and distributed systems fundamentals
- 🛠️ Sharpening production-readiness: idempotency, HMAC signature verification, atomic DB concurrency, token encryption

---

## 💼 Experience

**AI Automation Intern — Coresium** · Remote · *Apr 2026 – May 2026*
Built automation workflows with n8n and REST APIs for client operations; wrote validation and monitoring scripts to improve workflow reliability, and integrated third-party services into backend systems.

**Python Full-Stack Intern — PyGenicArc** · Remote · *Feb 2025 – May 2025*
Led a 4-person intern team to build **DailyDrop**, a Flask e-commerce platform — designed the core backend, database schemas, and checkout REST endpoints.

---

## 🚀 Featured Projects

### 🔹 [InsightPDF](https://github.com/Spidey173/InsightPDF.git) — RAG document Q&A
Next.js 16 / React 19 / FastAPI app with a two-stage retrieval pipeline (FAISS + cross-encoder reranker) and a post-generation fact-verification layer, returning cited answers in under 1.5s, running fully on local/CPU inference.
`Live:` [huggingface.co/spaces/Spidey173/insightpdf](https://huggingface.co/spaces/Spidey173/insightpdf)

### 🔹 [ChibiBytes](https://github.com/Spidey173/ChibiBytes) — AI content discovery platform
Flask anime & movie discovery platform on Neon PostgreSQL (with SQLite fallback), with a pre-warmed in-memory cache for fast catalog reads, a full admin panel, and a Gemini-powered chatbot that checks the local catalog before falling back to the LLM.
`Live:` [chibibytes-vutq.onrender.com](https://chibibytes-vutq.onrender.com)

### 🔹 [DailyDrop](https://github.com/Spidey173/Daily-Drop.git) — e-commerce platform
Full-stack Flask app with session-based cart tracking (guest + authenticated) and SQLite transactions that prevent inventory double-allocation at checkout. My PyGenicArc internship deliverable, built leading a 4-person team.
`Live:` [Frontend](https://dailydrop-alpha.vercel.app/) · [Full stack](https://daily-drop-c96q-f5su.onrender.com/)

### 🔹 [GitHub Automation Bot](https://github.com/Spidey173/GitHub-Automation-Bot-MVP.git) — event-driven webhook automation
FastAPI + Next.js app that verifies inbound GitHub webhooks with HMAC-SHA256, processes them asynchronously via background tasks, and deduplicates deliveries to prevent repeat triggers.
`Live:` [git-hub-automation-bot-mvp.vercel.app](https://git-hub-automation-bot-mvp.vercel.app/)

### 🔹 [Zyra](https://github.com/Spidey173/Zyra.git) — social & real-time messaging platform
Django 5 + Django Channels app with sub-30ms WebSocket direct messaging, typing indicators, online presence, 24h stories, and vertical reels. ORM joins (`select_related`/`prefetch_related`) eliminate N+1 query overhead, media offloaded to Cloudinary.
`Live:` [zyra-fa4v.onrender.com](https://zyra-fa4v.onrender.com/)

---

## 🧪 Open Source

| Project | What it does | Stack |
|---|---|---|
| [Glitch4ce](https://github.com/Spidey173/Glitch4ce.git) | Interactive gaming hub — 10+ retro mini-games in a unified cyberpunk dashboard, with player auth, guest access, and live SQLAlchemy-backed telemetry · [demo](https://glitch4ce.onrender.com/) | Flask (App Factory), SQLAlchemy, Flask-Login |
| [CourtBook-Pro](https://github.com/Spidey173/CourtBook-Pro.git) | Enterprise sports court booking platform — atomic slot locking to eliminate race conditions, server-side pricing engine, 37 automated Pytest suites · [demo](https://courtbook-pro-4c7j.onrender.com/) | Flask 3+, SQLAlchemy 2.0, Pydantic, Neon PostgreSQL, Alembic |
| [CogniStream](https://github.com/Spidey173/CogniStream.git) | Real-time facial emotion analyzer — MediaPipe Face Mesh alignment, HSEmotion ONNX inference across 8 emotion classes, streamed over WebSockets · [demo](https://cogni-stream-plum.vercel.app/) | React 19, FastAPI, MediaPipe, HSEmotion ONNX, Neon PostgreSQL |
| [CoreClicks](https://github.com/Spidey173/CoreClicks.git) | Link management & clickstream analytics engine — Redis-cached slug resolution for sub-5ms redirects, async geolocation/device parsing, live metric dashboards · [demo](https://coreclicks.onrender.com/) | Flask, Redis, PostgreSQL, SQLAlchemy, Chart.js |

---

## 💻 Tech I use

**Backend** — Python (FastAPI, Django, Flask) · REST APIs · WebSockets · async I/O
**AI / RAG** — FAISS · Cross-Encoder Reranking · Gemini API (`google-genai`) · HSEmotion ONNX · MediaPipe
**Data** — PostgreSQL (Neon) · SQLite · Redis · SQLAlchemy · Alembic
**Frontend** — React · Next.js · TypeScript · Jinja2
**Infra** — Docker · Git/GitHub · Vercel · Render · Hugging Face Spaces

---

## 💬 Ask me about
`RAG pipelines` · `FastAPI` · `event-driven systems` · `WebSockets` · `webhook security (HMAC)` · debugging nightmares 😄

## 🏸 Off the clock
Shuttlecock and cricket, both taken more seriously than is probably necessary 😌

---

## 🌐 Connect
<p align="left">
  <a href="https://www.linkedin.com/in/pruthvi-r-48ba9b2b4/">
    <img src="https://img.shields.io/badge/LinkedIn-ff4d4d?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:pruthvi.r0006@gmail.com">
    <img src="https://img.shields.io/badge/Email-ff4d4d?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://pruthvi-17.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-24243e?style=for-the-badge&logo=vercel&logoColor=white" />
  </a>
</p>

---

## 📊 GitHub Stats
<p align="center">
  <img src="https://streak-stats.demolab.com?user=Spidey173&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

Here is an upgraded, production-grade README.md tailored specifically to your
portfolio content.

It highlights your exact technical architecture decisions (atomic DB locking,
two-stage RAG reranking, HMAC webhook security, WebSocket concurrency), fixes
minor discrepancies (like MCA CGPA and DailyDrop stack), and uses clean styling
designed to impress tech recruiters and senior engineers.

<!-- HEADER BANNER -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=220&section=header&text=Pruthvi%20R&fontSize=48&fontColor=ff4d4d&animation=fadeIn" alt="Header Banner" />
</p>

<h1 align="center">Software Engineer — Backend & AI Systems</h1>

<p align="center">
  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=19&duration=2800&pause=1000&color=FF4D4D&center=true&vCenter=true&width=650&lines=FastAPI+%C2%B7+Django+%C2%B7+Express+(Node.js)+%C2%B7+PostgreSQL;Sub-1.5s+RAG+Search+%2B+Cross-Encoder+Reranking;Real-Time+WebSockets+%C2%B7+Atomic+DB+Concurrency;HMAC-SHA256+Webhook+Ingestion+%C2%B7+Event-Driven" alt="Typing Animation" />
  </a>
</p>

<p align="center">
  <b>📍 Bengaluru, India</b> &nbsp;•&nbsp; 
  <a href="https://spidey173.github.io/"><b>🌐 Live Portfolio</b></a> &nbsp;•&nbsp; 
  <a href="mailto:pruthvi.r0006@gmail.com"><b>✉️ Email Me</b></a> &nbsp;•&nbsp; 
  <a href="https://linkedin.com/in/pruthvi-r-48ba9b2b4"><b>💼 LinkedIn</b></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-Available_for_Internships_%26_Junior_Roles-success?style=for-the-badge&logo=target&color=22c55e" alt="Status Badge" />
</p>

---

## 💡 About Me

I build **high-performance backend APIs, real-time systems, and document retrieval (RAG) pipelines** — then test their limits before they hit production. 

I am an **MCA student at Jain University, Bengaluru** with a focus on clean modular architecture, API performance, low-latency search, and race-condition prevention across distributed connections.

* ⚡ **Engineering Bias:** Clean separation of concerns, defensive error-handling, sub-millisecond DB concurrency, and minimal third-party dependency overhead.
* 🎯 **What I'm currently working on:** Optimizing vector search grounding mechanisms, asynchronous queuing patterns, and real-time WebSocket state distribution.

---

## 🛠️ Tech Stack

<div align="center">

| Category | Technologies |
| :--- | :--- |
| **Backend Frameworks** | `Python` `FastAPI` `Django` `Flask` `Node.js` `Express` `REST APIs` `WebSockets` |
| **AI & Retrieval (RAG)** | `RAG Pipelines` `FAISS` `Cross-Encoder Reranking` `MediaPipe` `Gemini API` |
| **Databases & Caching** | `PostgreSQL` `MongoDB` `SQLite` `Redis` `SQLAlchemy` `Django ORM` |
| **Frontend & Integration**| `Next.js 16` `React 19` `TypeScript` `JavaScript` `Tailwind CSS` `Jinja2` |
| **DevOps & Tooling** | `Docker` `Git` `GitHub Actions` `Linux` `HMAC Security` `Postman` |
| **Deployment Platforms** | `Vercel` `Render` `Hugging Face Spaces` `Cloudinary` |

</div>

---

## 🚀 Featured Projects

### 📄 [InsightPDF](https://github.com/Spidey173/InsightPDF.git) — RAG Document Intelligence Platform
> **Next.js 16 · React 19 · TypeScript · FastAPI · FAISS · Cross-Encoder Reranker · Gemini API**  
> 🌐 **[Live Space](https://huggingface.co/spaces/Spidey173/insightpdf)**

* Built a **two-stage document retrieval system** combining FAISS vector search with a Cross-Encoder semantic reranker to eliminate context drift.
* Engineered an automated **grounding verification module** (`verification.py`) that cross-verifies LLM outputs against source vectors to prevent hallucinations.
* Delivers sub-1.5s cited answer generation with page/line references running on standard CPU hardware without external cloud DB lock-in.

---

### ⚡ [GitHub Webhook Automation Bot](https://github.com/Spidey173/GitHub-Automation-Bot-MVP.git) — Event-Driven System
> **FastAPI · Next.js · HMAC-SHA256 · Python asyncio · Background Tasks**  
> 🌐 **[Live Demo](https://git-hub-automation-bot-mvp.vercel.app/)**

* Processes GitHub repository webhooks asynchronously using FastAPI background tasks to return non-blocking `200 OK` status immediately.
* Secured incoming webhooks via **HMAC-SHA256 signature verification** to prevent spoofing and unauthorized payload injection.
* Tracked active Delivery IDs in-memory for instant request deduplication, avoiding network retry conflicts without adding broker complexity.

---

### 📅 [Expert Booking System](https://github.com/Spidey173/Expert-Booking-System.git) — Real-Time Slot Reservation
> **React · Node.js · Express · MongoDB · Socket.io · Tailwind CSS**  
> 🌐 **[Live Demo](https://expert-booking-system-lovat.vercel.app/)**

* Solved concurrent booking race conditions using **MongoDB compound unique indexes** and atomic `findOneAndUpdate` queries.
* Integrated bi-directional **Socket.io WebSockets** to sync reservation state across all active client screens with **sub-100ms latency**.

---

### 🛒 [DailyDrop E-Commerce Backend](https://github.com/Spidey173/Daily-Drop.git) — Session & Checkout Pipeline
> **Flask · Python · SQLite · Session Middleware · REST API**  
> 🌐 **[Frontend Demo](https://dailydrop-alpha.vercel.app/)** · **[Full Stack (Render)](https://daily-drop-c96q-f5su.onrender.com/)**

* Designed transactional schema structures with strict isolation levels to prevent inventory double-allocation during high-concurrency checkouts.
* Led a 4-person intern team to deliver the complete backend, session middleware tracking, and RESTful cart/order endpoints.

---

## 📂 Other Open Source Work

| Project | Stack | Description | Links |
| :--- | :--- | :--- | :--- |
| **CogniStream** | `FastAPI` `MediaPipe` `Docker` `NumPy` `PostgreSQL` | Real-time computer vision engine ingesting frames via WebSockets & streaming zero-OpenCV MJPEG. | [Code](https://github.com/Spidey173/CogniStream.git) |
| **Zyraa** | `Django` `PostgreSQL` `Cloudinary` `WhiteNoise` | Scalable social platform backend with `select_related` DB query optimizations to eliminate N+1 loops. | [Code](https://github.com/Spidey173/Zyraa.git) |
| **ChibiBytes** | `Flask` `SQLite` `Gemini API` `Jinja2` | Anime discovery platform with custom local DB intent detection falling back to Gemini LLM. | [Code](https://github.com/Spidey173/ChibiBytes) • [Demo](https://chibibytes-vutq.onrender.com) |
| **Glitch4ce** | `Flask` `SQLite` `Sessions` `JS` | Retro arcade platform featuring 15+ mini-games with dynamic session tracking and gameplay logs. | [Code](https://github.com/Spidey173/Glitch4ce.git) • [Demo](https://glitch4ce-8qk3.onrender.com/) |

---

## 💼 Work Experience

#### **AI Automation Intern** — *Coresium* `(Apr 2026 – May 2026)`
* Engineered n8n and REST API workflows to automate client operational pipelines.
* Authored data verification & monitoring scripts to catch edge cases and maintain workflow reliability.

#### **Python Full Stack Intern** — *PyGenicArc* `(Feb 2025 – May 2025)`
* Led a 4-person developer team to design and deploy the core backend architecture for **DailyDrop**.
* Built session management systems, relational DB schemas, and checkout validation workflows.

---

## 🎓 Education

* **Master of Computer Applications (MCA)** — *Jain University, Bengaluru* `(2025 – 2027)` | **CGPA: 8.45**
* **Bachelor of Computer Applications (BCA)** — *Bits Hi-Tech College, Chitradurga* `(2022 – 2025)` | **CGPA: 8.07**

---

## 📊 GitHub Analytics

<div align="center">

  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Spidey173&theme=tokyonight&hide_border=true&show_icons=true&count_private=true&title_color=ff4d4d&text_color=cbd5e1&icon_color=ff4d4d" alt="Spidey173 GitHub Stats" />
  &nbsp;
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Spidey173&theme=tokyonight&hide_border=true&layout=compact&title_color=ff4d4d&text_color=cbd5e1" alt="Top Languages" />

  <br/><br/>

  <img src="https://streak-stats.demolab.com?user=Spidey173&theme=tokyonight&hide_border=true&fire=ff4d4d&ring=ff4d4d&currStreakNum=ff4d4d" alt="GitHub Streak Stats" />

</div>

---

## 📫 Let's Connect

<p align="center">
  <a href="https://linkedin.com/in/pruthvi-r-48ba9b2b4">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="mailto:pruthvi.r0006@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  &nbsp;
  <a href="https://spidey173.github.io/">
    <img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge&logo=safari&logoColor=white" alt="Portfolio" />
  </a>
</p>

<p align="center">
  <i>© 2026 Pruthvi R. Built with restraint and clean backend engineering.</i>
</p>

What Makes This README Stand Out?

1.  Accurate to Your Portfolio: Fixes stack details (e.g., Flask for DailyDrop,
    Next.js + FastAPI for InsightPDF, 8.45 MCA CGPA).
2.  Engineering Focus over Hype: Clearly highlights how you solved problems
    (HMAC security, atomic findOneAndUpdate, Cross-Encoder reranking, vector
    grounding verification).
3.  High Impact Visuals: Uses dark-mode friendly typing banners, dark slate
    badges, concise layout tables, and Tokio-Night themed stat cards.
4.  Recruiter Ready: Features clear links to GitHub repositories, live
    Render/Vercel deployments, and direct contact options.

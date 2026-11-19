<!-- HEADER -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:090d16,35:1e1b4b,70:311042,100:090d16&height=200&section=header&text=Pruthvi%20R&fontSize=44&fontColor=ff4d4d&fontAlignY=42&animation=fadeIn" width="100%" alt="Pruthvi R" />

  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=19&duration=2800&pause=1000&color=38BDF8&center=true&vCenter=true&width=650&height=42&lines=%E2%9A%A1+Backend+Engineering+%7C+Distributed+Locking;%E2%8F%B3+Temporal+Information+Retrieval+%26+TextOS;%F0%9F%8F%A6+5.86M+Record+Lakehouse+%26+Kafka+Pipelines;%F0%9F%9B%A1%EF%B8%8F+DevSecOps+AST+Static+Analysis+%26+Automation" alt="Typing SVG" />
  </a>

  <p align="center">
    <a href="https://pruthvi-17.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-pruthvi--17.vercel.app-ff4d4d?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
    <a href="https://pruthvi-17.vercel.app/Pruthvi_Resume.pdf"><img src="https://img.shields.io/badge/R%C3%A9sum%C3%A9-PDF%20Download-22c55e?style=for-the-badge&logo=googledocs&logoColor=white" alt="Resume" /></a>
    <a href="https://www.linkedin.com/in/pruthvir173/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:pruthvi.r0006@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  </p>

  <p align="center">
    MCA student at Jain University (CGPA 8.45/10) with three engineering internships.<br/>
    Focused on building <strong>resilient backend services, high-throughput data pipelines, and concurrency-safe web applications</strong> in Python and PostgreSQL.
  </p>

  <p align="center">
    <code>🎯 Target Roles</code>: <strong>Backend Engineer / Data Engineer</strong> (Junior / Associate / Full-Time)
  </p>
</div>

---

## ⚡ Key Highlights & Metrics

<table align="center" width="100%">
  <tr>
    <td align="center" width="20%">
      <b>5.86M</b><br/>
      <sub>Financial records processed by LedgerFlow</sub>
    </td>
    <td align="center" width="20%">
      <b>~42,000 /s</b><br/>
      <sub>Bulk PostgreSQL binary <code>COPY</code> throughput</sub>
    </td>
    <td align="center" width="20%">
      <b>&lt; 1 ms</b><br/>
      <sub>Redis Lua atomic stock locking in DailyDrop</sub>
    </td>
    <td align="center" width="20%">
      <b>0.0%</b><br/>
      <sub>Future data leakage in Chronexa temporal search</sub>
    </td>
    <td align="center" width="20%">
      <b>470+</b><br/>
      <sub>Automated Pytests &amp; Playwright E2E suites</sub>
    </td>
  </tr>
</table>

---

## 🚀 Featured Projects

### 🛒 [DailyDrop — Quick-Commerce Web Platform](https://github.com/Spidey173/Dailydrop)
*Full-stack grocery platform engineered with atomic transactional checkout, server-authoritative cart pricing, and race condition prevention.*
* **Problem**: Flash-sale checkout bursts cause overselling race conditions and client-side price payload tampering.
* **Engineering**: Enforced server-authoritative price reconciliation, **Redis Lua atomic stock decrements** with conditional SQL lock ordering (`UPDATE products SET stock = stock - %s WHERE id = %s AND stock >= %s`), and Razorpay HMAC-SHA256 signature verification.
* **Testing & Proof**: **116 passing tests across 21 test files** verifying zero overselling across simulated concurrent checkouts and atomic rollbacks.
* 🌐 **Links**: [Live Storefront](https://dailydrop17.vercel.app/) · [Admin Portal](https://dailydrop17.vercel.app/admin_login) · [GitHub Repo](https://github.com/Spidey173/Dailydrop)

---

### 🏦 [LedgerFlow — Banking Data Pipeline & AWS S3 Lakehouse](https://github.com/Spidey173/LedgerFlow)
*End-to-end data pipeline that ingests, validates, and cleans multi-million financial records across 10 relational entities.*
* **Problem**: Loading 5.86M unvalidated financial records risks foreign-key deadlocks, corrupted row crashes, and credential leaks.
* **Engineering**: **Medallion Architecture (Bronze ➔ Silver ➔ Gold)**, Apache Airflow DAG orchestration, AWS Glue ETL jobs, dynamic in-memory AES-256 decryption via AWS SSM KMS SecureString, 4-tier topological sorting, and audited AWS S3 Dead Letter Queue (DLQ).
* **Testing & Proof**: **~42,000 rows/sec** bulk binary COPY streaming loading 5.15M+ rows in ~2.1m; **720,000+ quarantined rows** in S3 DLQ with zero pipeline crashes; **60 passing Pytests**.
* 🌐 **Links**: [Live Dashboard](https://ledgerflow17.vercel.app/) · [DLQ Audit Report](https://ledgerflow17.vercel.app/audit-report) · [GitHub Repo](https://github.com/Spidey173/LedgerFlow)

---

### ⏱️ [Chronexa — Temporal Workplace-Memory Search & Assistant](https://github.com/Spidey173/Chronexa)
*Point-in-time workplace-memory search engine and dry-run Action Assistant (TextOS) eliminating temporal data leakage.*
* **Problem**: Standard RAG pipelines retrieve future facts invalid at historical query times, and unconstrained LLM actions risk destructive side-effects.
* **Engineering**: Pre-retrieval temporal boundaries (`timestamp <= as_of`), dual-stream FastEmbed ONNX dense vectors + cached BM25 fused via Reciprocal Rank Fusion ($k=60$), cross-encoder reranking, and allowlisted dry-run action schemas.
* **Testing & Proof**: **86.8% Holdout Top-10 retrieval** (MRR 0.683, local benchmark) with **0.0% future knowledge leakage**; **12/12 passing action benchmark schemas**; **62 passing Pytests**.
* 🌐 **Links**: [Live Web UI](https://chronexa17.vercel.app/) · [GitHub Repo](https://github.com/Spidey173/Chronexa)

---

## 🛠️ More Projects

| Project | Focus | Key Highlights | Verified Testing | Links |
| :--- | :--- | :--- | :--- | :--- |
| **⚡ Darkrai** | DevSecOps &amp; AST Linter | Sub-5ms webhook HMAC-SHA256 gateway, Redis worker queue with DLQ, Python AST security linter (`ast.parse()`), and transactional outbox. | **75 Pytests** | [Live Console](https://darkrai17.vercel.app/) • [Code](https://github.com/Spidey173/Darkrai) |
| **📑 Veridocs** | Document AI &amp; Verification | PostgreSQL **pgvector (HNSW cosine embeddings)** + hybrid BM25 search, automated **RAG Triad Telemetry**, and citation drawer. | **160 Tests** (Unit + E2E) | [Live Demo](https://veridocs17.vercel.app/) • [Code](https://github.com/Spidey173/Veridocs) |
| **🏸 Haneka** | Concurrency &amp; Booking | Engineered with database-level pessimistic row locking (`SELECT ... FOR UPDATE`) and atomic slot allocations to prevent double-bookings. | **43 Pytests** | [Live Demo](https://haneka.vercel.app/) • [Code](https://github.com/Spidey173/Haneka) |
| **👾 Pixora** | Real-Time Gaming Platform | Retro arcade platform with 17 mini-games, anti-cheat session tokens, and sub-millisecond leaderboards backed by Redis Sorted Sets (ZSET). | **100 Pytests** | [Live Arcade](https://pixora17.vercel.app/) • [Code](https://github.com/Spidey173/Pixora) |

---

## 🧰 Tech Stack

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,fastapi,flask,postgres,redis,kafka,docker,aws,nextjs,ts,react,tailwind,git,githubactions&theme=dark" alt="Tech Stack Icons" />
  </a>
</p>

* **Backend &amp; APIs**: Python (3.11/3.12), FastAPI, Flask 3, RESTful APIs, Redis (Caching, Queues &amp; Lua), Pydantic v2, WebSockets
* **Data Engineering**: PostgreSQL 16 (Neon), Bulk psycopg COPY Streaming (~42k rows/sec), Apache Airflow DAGs, AWS S3 Lakehouse, AWS Glue ETL, Dead Letter Queues (DLQ)
* **Retrieval &amp; Search**: pgvector (HNSW Indexing), FastEmbed ONNX BGE Embeddings, BM25 Lexical Search, Reciprocal Rank Fusion (RRF), Temporal Filtering (`as_of`)
* **DevOps &amp; Testing**: Docker, Docker Compose, Pytest (470+ tests across repositories), Playwright E2E browser testing, GitHub Actions CI/CD

---

## 💼 Experience

* **Software Engineer Intern · ElinaAI** *(Aug 2026 – Sep 2026 · Remote)*
  * Built and styled appointment scheduling and patient tracking components using React.js and modern JavaScript.
  * Integrated front-end components with backend Python REST APIs to fetch and update clinic records.
  * Leveraged modern developer workflows (GitHub Copilot, Claude) to accelerate code drafting and test authoring under senior guidance.

* **Artificial Intelligence Intern · Coresium** *(Apr 2026 – May 2026 · Remote)*
  * Created automated workflows using n8n and REST endpoints to connect internal tools and eliminate repetitive manual entry.
  * Wrote automated Python validation scripts to inspect data formatting and catch schema errors before downstream ingestion.
  * Collaborated with team members to monitor and document production pipelines across daily operations.

* **Python Backend &amp; Full-Stack Intern · PyGenicArc** *(Feb 2025 – May 2025 · Chitradurga)*
  * Co-led an intern team developing DailyDrop (e-commerce platform), modularizing core logic into catalog, order, and payment services.
  * Designed normalized PostgreSQL schemas with connection pooling and configured CI pipelines executing automated Pytests.

---

## 🎓 Education

* **Master of Computer Applications (MCA)** — Jain University, Bengaluru *(2025–2027)* | **CGPA: 8.45 / 10**
* **Bachelor of Computer Applications (BCA)** — Davangere University, Chitradurga *(2022–2025)* | **CGPA: 8.07 / 10** (First Class with Distinction)

---

## 📊 GitHub Activity

<table align="center" width="100%">
  <tr>
    <td align="center" width="50%">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Spidey173&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDF8&text_color=E2E8F0" alt="Top Languages" />
    </td>
    <td align="center" width="50%">
      <img src="https://streak-stats.demolab.com?user=Spidey173&theme=tokyonight&hide_border=true&background=0D1117&ring=38BDF8&fire=F43F5E&currStreakLabel=38BDF8" alt="GitHub Streak" />
    </td>
  </tr>
</table>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:090d16,50:1e1b4b,100:090d16&height=80&section=footer" width="100%" />
</div>

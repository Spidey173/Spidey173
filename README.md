<!-- HEADER -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=180&section=header&text=Pruthvi%20R&fontSize=42&fontColor=ff4d4d&animation=fadeIn" alt="Pruthvi R" />

<h3 align="center">Backend &amp; Data Engineer · Python · PostgreSQL · Distributed Systems</h3>

<p align="center">
  <a href="https://pruthvi-17.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-pruthvi--17.vercel.app-ff4d4d?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://pruthvi-17.vercel.app/Pruthvi_Resume.pdf"><img src="https://img.shields.io/badge/R%C3%A9sum%C3%A9-PDF%20Download-22c55e?style=for-the-badge" alt="Résumé PDF" /></a>
  <a href="https://www.linkedin.com/in/pruthvir173/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:pruthvi.r0006@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

MCA student at Jain University (CGPA 8.45/10) with three engineering internships, building resilient backend services, high-throughput data pipelines, and temporal retrieval systems in Python and PostgreSQL.

> **🎯 Target Roles**: **Backend Engineer / Data Engineer** (Internship or Junior Full-Time)  
> *Relational database modeling, high-throughput bulk ingestion via COPY streaming, Dead Letter Queue governance, and concurrency control.*

---

## ⚡ Grounded Metrics Across Projects

| 5.86M | ~42,000 / sec | 86.8% | 76 | 330+ |
|:---:|:---:|:---:|:---:|:---:|
| Synthetic records processed by LedgerFlow | Bulk COPY streaming throughput into PostgreSQL | Holdout Top-10 retrieval (n=100) in Chronexa | Passing Pytests in DailyDrop | Automated tests across repositories |

---

## 🏆 Top 3 Flagship Systems

### 1. 🛒 [DailyDrop — Full-Stack Quick-Commerce Platform](https://github.com/Spidey173/Dailydrop) *(Backend Focus)*
*Quick-commerce platform engineered with atomic transactional checkout, server-authoritative cart pricing, and modular service blueprints.*
- **Problem**: Concurrent grocery checkout spikes cause overselling race conditions and client-side price tampering.
- **Decision**: Enforced server-authoritative price reconciliation against PostgreSQL, atomic conditional decrements (`UPDATE products SET stock = stock - %s WHERE id = %s AND stock >= %s`), connection pooling (`minconn=1, maxconn=4`), and Razorpay HMAC-SHA256 signature verification.
- **Evidence**: **76 passing Pytests** across 14 modules verifying race conditions and HMAC checks; live storefront deployed on Vercel with Neon PostgreSQL.
- 🌐 **Links**: [Live Storefront](https://dailydrop17.vercel.app/) · [Admin Portal](https://dailydrop17.vercel.app/admin_login) · [GitHub Repository](https://github.com/Spidey173/Dailydrop)

### 2. 🏦 [LedgerFlow — Banking Data Pipeline & AWS S3 Lakehouse](https://github.com/Spidey173/LedgerFlow) *(Data Engineering Focus)*
*End-to-end financial data pipeline that ingests, validates, and cleans raw banking records across 10 relational tables.*
- **Problem**: Ingesting 5.86M unvalidated banking records risks pipeline stalls, foreign-key deadlocks, and credential leakage.
- **Decision**: Dynamic in-memory AES-256 decryption via AWS SSM KMS SecureString, 4-tier topological sorting (Lookups ➔ Customers ➔ Portfolios ➔ Transactions), audited AWS S3 Dead Letter Queue (DLQ), and native PostgreSQL binary COPY streaming (`chunksize=250k–300k`).
- **Evidence**: **~42,000 rows/sec** bulk COPY streaming benchmark loading 5.15M+ rows in ~2.1m; **720,000+ quarantined rows** in S3 DLQ with zero pipeline crashes; **55 passing Pytests**.
- 🌐 **Links**: [Live Executive Portal](https://ledgerflow17.vercel.app/) · [DLQ Audit Report](https://ledgerflow17.vercel.app/audit-report) · [GitHub Repository](https://github.com/Spidey173/LedgerFlow)

### 3. ⏱️ [Chronexa — Point-in-Time Workplace-Memory Search & Safe Action Assistant](https://github.com/Spidey173/Chronexa) *(Retrieval & AI Systems Focus)*
*Point-in-time workplace-memory search engine and dry-run Action Assistant (TextOS) eliminating temporal leakage and prompt injection risks.*
- **Problem**: Standard RAG retrieves future facts invalid at historical query times, and unconstrained LLM actions risk destructive OAuth side-effects.
- **Decision**: Pre-retrieval temporal cutoff (`timestamp <= as_of & NOT deleted`, guaranteeing 0.0% future leakage), dual-stream FastEmbed ONNX BGE dense vectors + passage-cached BM25 fused via RRF ($k=60$), cross-encoder reranking, and allowlisted dry-run JSON schemas.
- **Evidence**: **86.8% Holdout Top-10 retrieval** on $n=100$ unseen queries (MRR 0.683); **12/12 passing action benchmark schemas**; **50 passing Pytests**.
- 🌐 **Links**: [Live Web UI](https://chronexa17.vercel.app/) · [GitHub Repository](https://github.com/Spidey173/Chronexa)

---

## 🛠️ Additional Builds

| System | Focus | Architectural Highlights | Verified Testing | Links |
| :--- | :--- | :--- | :--- | :--- |
| **Darkrai** | DevSecOps Automation &amp; AST Linter | Sub-5ms webhook HMAC-SHA256 gateway, Redis worker queues with DLQ, Python AST security linter (`ast.parse()`), transactional outbox, and SSE streaming. | **44 Pytests** | [Live Console](https://darkrai17.vercel.app/) • [Code](https://github.com/Spidey173/Darkrai) |
| **Veridocs** | Forensic Document AI &amp; Canvas Diff | PDF.js viewport coordinate normalization, hybrid BM25 + FAISS search, cross-version clause contradiction diffing, and pixel-level bounding boxes. | **107 Tests** | [Live Viewer](https://veridocs17.vercel.app/) • [Code](https://github.com/Spidey173/Veridocs) |

---

## 💼 Experience (Measurable Outcomes)

- **Software Engineer Intern · ElinaAI** · Remote · *Aug 2026 – Sep 2026*  
  - Developed responsive front-desk appointment and patient tracking interfaces in React connected to 8+ Python REST endpoints for real-time CRUD and status updates.
  - Implemented client-side schema validation and error boundaries, eliminating booking dropouts.
  - Automated frontend component and API integration tests under senior engineering guidance, accelerating PR verification cycles.

- **Artificial Intelligence Intern · Coresium** · Remote · *Apr 2026 – May 2026*  
  - Engineered 12+ automated integration workflows connecting internal tools and operational databases via n8n and REST APIs, cutting manual data re-entry time by ~60%.
  - Authored Python schema validation scripts that intercepted malformed payloads prior to ingestion, reducing pipeline runtime failures across daily syncs.
  - Documented webhook schemas and failover protocols, establishing automated alerting for operational disruptions.

- **Python Backend &amp; Full-Stack Intern · PyGenicArc** · Chitradurga · *Feb 2025 – May 2025*  
  - Led a 4-intern team building DailyDrop (Flask 3 quick-commerce platform with 200+ grocery SKUs), architecting decoupled services for catalog validation, inventory reservation, and checkout.
  - Enforced single-source-of-truth inventory consistency with atomic conditional SQL decrements, sub-millisecond Redis Lua fast-rejection, Decimal financial precision, and Razorpay HMAC-SHA256 verification.
  - Configured CI pipelines running 76 unit &amp; integration Pytests on pull requests, covering concurrency, outbox durability, and HMAC verification.

---

## 🎓 Education

- **Master of Computer Applications (MCA)** — Jain University, Bengaluru *(2025–2027)* | **CGPA: 8.45 / 10**
- **Bachelor of Computer Applications (BCA)** — Davangere University, Chitradurga *(2022–2025)* | **CGPA: 8.07 / 10** (First Class with Distinction)

---

## 🧰 Technical Stack (Grounded in Featured Work)

- **Languages &amp; Core**: Python (3.11+), SQL (PostgreSQL), Modern JavaScript (ES6+), HTML5/CSS3, Bash
- **Backend Systems**: FastAPI, Flask 3, RESTful APIs, Redis (Caching, Queues &amp; Lua), Pydantic, WebSockets &amp; SSE
- **Data Engineering**: PostgreSQL 16 (Neon), Bulk psycopg COPY Streaming (~42k rows/sec), AWS S3 Lakehouse, AWS SSM (KMS SecureString), Dead Letter Queues (DLQ), Connection Pooling
- **Retrieval &amp; RAG**: Hybrid RAG (FastEmbed ONNX BGE-small + BM25), Reciprocal Rank Fusion (RRF, k=60), Cross-Encoder Reranking, Temporal Filtering (`as_of`)
- **DevOps &amp; Testing**: Docker, Git/GitHub, Pytest (330+ tests across repositories), GitHub Actions CI/CD matrix, Flake8

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Spidey173&amp;theme=tokyonight&amp;hide_border=true" alt="GitHub Streak" />
</p>
<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:24243e,50:302b63,100:0f0c29&amp;height=100&amp;section=footer" />

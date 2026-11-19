<!-- ========================================================================= -->
<!-- HEADER BANNER & TERMINAL HERO                                              -->
<!-- ========================================================================= -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:090d16,35:1e1b4b,70:311042,100:090d16&height=210&section=header&text=PRUTHVI%20R&fontSize=48&fontColor=ff4d4d&fontAlignY=42&animation=fadeIn" width="100%" alt="Pruthvi R Banner" />

  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2800&pause=1000&color=38BDF8&center=true&vCenter=true&width=700&height=45&lines=%E2%9A%A1+High-Concurrency+Backends+%7C+Distributed+Locking;%E2%8F%B3+Temporal+Information+Retrieval+%26+Safe+TextOS;%F0%9F%8F%A6+5.86M+Record+Lakehouse+%26+Kafka+Ingestion;%F0%9F%9B%A1%EF%B8%8F+DevSecOps+AST+Static+Analysis+%26+Automation" alt="Typing SVG" />
  </a>

  <p align="center">
    <a href="https://pruthvi-17.vercel.app/"><img src="https://img.shields.io/badge/LIVE%20PORTFOLIO-pruthvi--17.vercel.app-ff4d4d?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
    <a href="https://pruthvi-17.vercel.app/Pruthvi_Resume.pdf"><img src="https://img.shields.io/badge/R%C3%89SUM%C3%89-DOWNLOAD%20PDF-22c55e?style=for-the-badge&logo=googledocs&logoColor=white" alt="Resume" /></a>
    <a href="https://www.linkedin.com/in/pruthvir173/"><img src="https://img.shields.io/badge/LINKEDIN-PRUTHVIR173-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:pruthvi.r0006@gmail.com"><img src="https://img.shields.io/badge/EMAIL-DIRECT%20CONTACT-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  </p>

  <p align="center">
    <strong>Master of Computer Applications (MCA)</strong> · Jain University (CGPA 8.45/10) · 3x Engineering Internships<br/>
    Specializing in <strong>resilient backend services, high-throughput data platforms, concurrency control, and deterministic AI systems</strong>.
  </p>
</div>

---

<!-- ========================================================================= -->
<!-- MISSION CONTROL TELEMETRY HUD                                              -->
<!-- ========================================================================= -->
<div align="center">
  <h2>⚡ MISSION CONTROL // PRODUCTION TELEMETRY</h2>
</div>

<table align="center" width="100%">
  <tr>
    <td align="center" width="20%">
      <kbd>⚡ DATA ENGINE</kbd><br/>
      <h2 style="margin: 4px 0; color: #38bdf8;">5.86M</h2>
      <sub>Financial records parsed &amp; cleaned by LedgerFlow</sub>
    </td>
    <td align="center" width="20%">
      <kbd>🚀 STREAMING INGEST</kbd><br/>
      <h2 style="margin: 4px 0; color: #22c55e;">~42,000 /s</h2>
      <sub>Native PostgreSQL binary <code>COPY</code> throughput</sub>
    </td>
    <td align="center" width="20%">
      <kbd>🔒 CONCURRENCY</kbd><br/>
      <h2 style="margin: 4px 0; color: #ff4d4d;">&lt; 1 ms</h2>
      <sub>Redis Lua atomic locks preventing overselling</sub>
    </td>
    <td align="center" width="20%">
      <kbd>⏱️ TEMPORAL ACCURACY</kbd><br/>
      <h2 style="margin: 4px 0; color: #a855f7;">0.0%</h2>
      <sub>Future data leakage in Chronexa time-sliced IR</sub>
    </td>
    <td align="center" width="20%">
      <kbd>🧪 VERIFIED SUITE</kbd><br/>
      <h2 style="margin: 4px 0; color: #f59e0b;">470+</h2>
      <sub>Passing Pytests, E2E browser tests &amp; race checks</sub>
    </td>
  </tr>
</table>

---

<!-- ========================================================================= -->
<!-- ENGINEERING PHILOSOPHY                                                     -->
<!-- ========================================================================= -->
<details open>
<summary><h3>🧠 Core Systems Engineering Philosophy</h3></summary>

```bash
[01] ZERO-OVERSELLING ARCHITECTURE
     Never trust client-side prices. Lock stocks atomically in Redis via Lua scripts before 
     dispatching to PostgreSQL ACID transactions.

[02] HERMETIC TEMPORAL BOUNDARIES
     RAG systems that search without temporal boundaries leak future facts into past queries. 
     Every search index must enforce strict point-in-time 'timestamp <= as_of' gating.

[03] STREAM, NEVER BUFFER
     Loading gigabytes of financial transactions into Python RAM causes OOM crashes.
     Always stream native PostgreSQL binary COPY chunks with dedicated Dead Letter Queues (DLQ).

[04] RIGOROUS CONCURRENCY PROOF
     If double-booking prevention, lock ordering, and crash recovery are not proved in multi-threaded 
     automated test suites, they do not exist.
```
</details>

---

<!-- ========================================================================= -->
<!-- FLAGSHIP PRODUCTION ARCHITECTURES                                          -->
<!-- ========================================================================= -->
<div align="center">
  <h2>🏆 FLAGSHIP PRODUCTION SYSTEMS</h2>
  <p>Architectural specifications, concurrency primitives, and verified benchmark proofs.</p>
</div>

### 1. 🛒 [DailyDrop — High-Concurrency Quick-Commerce Platform](https://github.com/Spidey173/Dailydrop)
> **Domain**: *High-Concurrency Backend Systems · Distributed State Management · Flash-Sale Protection*

```text
  [Concurrent Checkouts] 
             │
             ▼
  ┌──────────────────────┐      Redis Lua Atomic Decrement       ┌──────────────────────┐
  │ Server Price Check   │ ────────────────────────────────────► │ Lock Stock In Memory │
  │ (Reconcile Catalog)  │                                       │ (Sub-Millisecond)    │
  └──────────────────────┘                                       └──────────┬───────────┘
             │                                                              │
             ▼                                                              ▼
  ┌──────────────────────┐     FSM State Machine (migrations/004) ┌──────────────────────┐
  │ Neon PostgreSQL ACID │ ◄───────────────────────────────────── │ Razorpay HMAC-SHA256 │
  │ (UPDATE WHERE s>=qty)│                                        │ (Cryptographic FSM)  │
  └──────────────────────┘                                        └──────────────────────┘
```

* **The Problem**: High-traffic flash-sale checkouts cause race conditions, negative inventory counts (overselling), and client-side price payload tampering.
* **The Architecture**:
  * **Redis Lua Atomic Decrements**: Stock levels are validated and locked atomically in Redis before committing to the relational database.
  * **Conditional SQL Lock Ordering**: Transactions enforce `UPDATE products SET stock = stock - %s WHERE id = %s AND stock >= %s` with deterministic sorting to eliminate deadlocks.
  * **ACID State Machine**: Orders progress through strict cryptographic status transitions (`CREATED` ➔ `PAYMENT_PENDING` ➔ `CONFIRMED` ➔ `DISPATCHED`).
* **Verified Evidence**: **116 automated tests across 21 test files** verifying zero overselling across simulated concurrent race test fixtures (`test_inventory_lock_ordering.py`), rollback safety, and HMAC verification.
* 🌐 **Direct Links**: [Live Storefront](https://dailydrop17.vercel.app/) · [Admin Portal](https://dailydrop17.vercel.app/admin_login) · [GitHub Repo](https://github.com/Spidey173/Dailydrop)

---

### 2. 🏦 [LedgerFlow — Enterprise Banking Lakehouse & Pipeline](https://github.com/Spidey173/LedgerFlow)
> **Domain**: *Analytics Engineering · Financial Lakehouse · Batch ETL & Quarantine Governance*

```text
  Raw Financial Streams (5.86M Records Across 10 Entities)
             │
             ▼
  ┌─────────────────────────────────┐      Dynamic AES-256 Decrypt       ┌─────────────────────────────────┐
  │ AWS SSM Parameter Store         │ ─────────────────────────────────► │ In-Memory KMS SecureString     │
  │ (Decoupled Infrastructure Keys) │                                    │ (Zero Plaintext on Disk)        │
  └─────────────────────────────────┘                                    └──────────────┬──────────────────┘
             │                                                                          │
             ▼                                                                          ▼
  ┌─────────────────────────────────┐      4-Tier Topological Sort       ┌─────────────────────────────────┐
  │ Apache Airflow DAG Orchestrator │ ─────────────────────────────────► │ Lookups ➔ Users ➔ Accounts ➔ Tx │
  └─────────────────────────────────┘                                    └──────────────┬──────────────────┘
             │                                                                          │
             ▼                                                                          ▼
  ┌─────────────────────────────────┐     ~42,000 rows/sec Bulk Stream   ┌─────────────────────────────────┐
  │ PostgreSQL 16 Binary COPY Stream│ ◄───────────────────────────────── │ Audited AWS S3 DLQ Isolation    │
  │ (5.15M+ Clean Core Records)     │                                    │ (720k+ Quarantined Records)     │
  └─────────────────────────────────┘                                    └─────────────────────────────────┘
```

* **The Problem**: Ingesting multi-million-row financial datasets causes foreign-key dependency deadlocks, pipeline crashes on corrupt rows, and credential leakage in code.
* **The Architecture**:
  * **Medallion Data Architecture**: Layered Bronze (Raw Ingestion) ➔ Silver (Cleaned/Typed) ➔ Gold (Dimensional Star Schema) with Apache Airflow DAG scheduling and AWS Glue ETL integration.
  * **Topological Dependency Resolution**: Strict 4-tier dependency sequencing guarantees zero foreign-key constraint violations during bulk loads.
  * **Audited Dead Letter Queue (DLQ)**: Corrupted or negative-balance rows are quarantined to AWS S3 DLQ with automated audit telemetry rather than halting the ingestion batch.
* **Verified Evidence**: **~42,000 rows/sec** bulk binary COPY streaming loading 5.15M+ rows in ~2.1 minutes; **720,000+ quarantined rows** isolated without pipeline interruption; **60 passing Pytests**.
* 🌐 **Direct Links**: [Live Executive Dashboard](https://ledgerflow17.vercel.app/) · [DLQ Audit Report](https://ledgerflow17.vercel.app/audit-report) · [GitHub Repo](https://github.com/Spidey173/LedgerFlow)

---

### 3. ⏱️ [Chronexa — Temporal Workplace-Memory OS & Action Assistant](https://github.com/Spidey173/Chronexa)
> **Domain**: *Applied AI Systems · Information Retrieval (IR) · Point-in-Time Temporal Boundaries*

```text
  Corporate Event Stream (Gmail, Slack, Calendar, Git Commits, Transcripts)
             │
             ▼
  ┌─────────────────────────────────┐
  │ Pre-Retrieval Temporal Boundary │ ──► Guarantees: timestamp <= as_of & NOT deleted
  │ (Zero Future Leakage Guard)     │     (Completely eliminates future knowledge drift)
  └────────────────┬────────────────┘
                   │
                   ▼
  ┌─────────────────────────────────┐      Reciprocal Rank Fusion        ┌─────────────────────────────────┐
  │ Dual-Stream Retrieval Engine    │ ─────────────────────────────────► │ RRF Fusion (k=60) + Joint Rerank│
  │ (FastEmbed BGE + Cached BM25)   │                                    │ (86.8% Holdout Top-10 Retrieval)│
  └─────────────────────────────────┘                                    └──────────────┬──────────────────┘
                                                                                        │
                                                                                        ▼
                                                                         ┌─────────────────────────────────┐
                                                                         │ Allowlisted Dry-Run Action FSM  │
                                                                         │ (12/12 Verified Schemas)        │
                                                                         └─────────────────────────────────┘
```

* **The Problem**: Standard RAG pipelines retrieve facts that were not yet known at the historical point in time being queried, and unconstrained LLMs execute destructive external side-effects.
* **The Architecture**:
  * **Hermetic Temporal Boundaries**: Enforces strict mathematical slicing (`timestamp <= as_of`), guaranteeing **0.0% future knowledge leakage**.
  * **Hybrid Dual-Stream IR**: Combines lexical precision (passage-cached BM25) with semantic recall (FastEmbed ONNX BGE dense vectors), fused via Reciprocal Rank Fusion ($k=60$) and cross-encoder joint reranking.
  * **Deterministic TextOS Actions**: Restricts model actions to allowlisted, dry-run schema validations before executing any external side-effect.
* **Verified Evidence**: **86.8% Holdout Top-10 Retrieval** on $n=100$ unseen queries (MRR 0.683); **94.4% Dev Top-10**; **12/12 passing action benchmark schemas**; **62 passing Pytests**.
* 🌐 **Direct Links**: [Live Web UI](https://chronexa17.vercel.app/) · [GitHub Repo](https://github.com/Spidey173/Chronexa)

---

<!-- ========================================================================= -->
<!-- ADDITIONAL SPECIALIZED PRODUCTION BUILDS                                   -->
<!-- ========================================================================= -->
<div align="center">
  <h2>🛠️ SPECIALIZED ARCHITECTURAL BUILDS</h2>
</div>

<table width="100%">
  <thead>
    <tr>
      <th width="20%">System</th>
      <th width="22%">Domain &amp; Stack</th>
      <th width="38%">Core Engineering Primitives</th>
      <th width="20%">Verified Suite &amp; Live</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>⚡ Darkrai</strong></td>
      <td><code>DevSecOps</code><br/>FastAPI · Redis · Next.js</td>
      <td>Sub-5ms webhook HMAC-SHA256 signature gateway over raw request bytes, Transactional Outbox pattern with lease recovery, and formal Python Abstract Syntax Tree (<code>ast.parse()</code>) security linting.</td>
      <td><b>75 Pytests</b><br/><a href="https://darkrai17.vercel.app/">Live Console</a> · <a href="https://github.com/Spidey173/Darkrai">Code</a></td>
    </tr>
    <tr>
      <td><strong>📑 Veridocs</strong></td>
      <td><code>Document AI</code><br/>pgvector · Next.js · Playwright</td>
      <td>PostgreSQL <b>pgvector (HNSW cosine embeddings)</b> + hybrid BM25 search, automated <b>RAG Triad Telemetry</b> (Groundedness, Context Relevance, Answer Relevance), citation drawer, and document diffing.</td>
      <td><b>160 Tests</b> (E2E + Unit)<br/><a href="https://veridocs17.vercel.app/">Live Viewer</a> · <a href="https://github.com/Spidey173/Veridocs">Code</a></td>
    </tr>
    <tr>
      <td><strong>🏸 Haneka</strong></td>
      <td><code>Concurrency Systems</code><br/>Flask · PostgreSQL · Neon</td>
      <td>Engineered with database-level pessimistic row locking (<code>SELECT ... FOR UPDATE</code>) and atomic slot allocations to eliminate double-booking race conditions across concurrent reservations.</td>
      <td><b>43 Pytests</b><br/><a href="https://haneka.vercel.app/">Live Demo</a> · <a href="https://github.com/Spidey173/Haneka">Code</a></td>
    </tr>
    <tr>
      <td><strong>👾 Pixora</strong></td>
      <td><code>Real-Time Gaming</code><br/>Redis ZSET · WebSockets · Canvas</td>
      <td>Web arcade platform featuring 17 mini-games with cryptographic client-server anti-cheat handshakes, session token verification, and real-time sub-millisecond leaderboards backed by Redis Sorted Sets.</td>
      <td><b>100 Pytests</b><br/><a href="https://pixora17.vercel.app/">Live Arcade</a> · <a href="https://github.com/Spidey173/Pixora">Code</a></td>
    </tr>
  </tbody>
</table>

---

<!-- ========================================================================= -->
<!-- COMPREHENSIVE TECH STACK MATRIX                                            -->
<!-- ========================================================================= -->
<div align="center">
  <h2>🧰 TECHNICAL ARSENAL</h2>
  <p>Production tools grounded directly in the featured codebases above.</p>
</div>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=py,fastapi,flask,postgres,redis,kafka,docker,aws,nextjs,ts,react,tailwind,git,githubactions&theme=dark" alt="Tech Stack Icons" />
  </a>
</p>

<table width="100%">
  <tr>
    <td width="25%" valign="top">
      <strong>💻 Backend &amp; Concurrency</strong><br/>
      • Python 3.11 / 3.12<br/>
      • FastAPI &amp; Flask 3<br/>
      • Redis (Lua Scripts &amp; Queues)<br/>
      • WebSockets &amp; Server-Sent Events<br/>
      • Pydantic v2 &amp; Type Hinting
    </td>
    <td width="25%" valign="top">
      <strong>🏦 Data Engineering &amp; Lakehouse</strong><br/>
      • PostgreSQL 16 (Neon Serverless)<br/>
      • Binary COPY Streaming (~42k/s)<br/>
      • Apache Airflow DAGs<br/>
      • AWS S3 Lakehouse &amp; Glue ETL<br/>
      • AWS SSM (KMS SecureString)
    </td>
    <td width="25%" valign="top">
      <strong>🧠 Retrieval &amp; AI Systems</strong><br/>
      • pgvector (HNSW Indexing)<br/>
      • FastEmbed ONNX BGE Embeddings<br/>
      • BM25 Lexical Search &amp; RRF (k=60)<br/>
      • RAG Triad Telemetry Evaluation<br/>
      • Point-in-Time Temporal Slicing
    </td>
    <td width="25%" valign="top">
      <strong>🛠️ DevOps, Testing &amp; Security</strong><br/>
      • Docker &amp; Docker Compose<br/>
      • Pytest (470+ Automated Tests)<br/>
      • Playwright E2E Browser Testing<br/>
      • Python AST Static Analysis<br/>
      • GitHub Actions CI/CD Matrices
    </td>
  </tr>
</table>

---

<!-- ========================================================================= -->
<!-- WORK EXPERIENCE TIMELINE                                                   -->
<!-- ========================================================================= -->
<details>
<summary><h3>💼 Verified Engineering Experience</h3></summary>
<br/>

* **Software Engineer Intern · ElinaAI** *(Aug 2026 – Sep 2026 · Remote)*
  * Built and styled front-desk UI components using React.js and modern JavaScript for medical practice scheduling and patient tracking.
  * Integrated front-end appointment components with backend Python REST APIs to fetch, mutate, and reconcile clinic records.
  * Accelerated code refactoring, test drafting, and API integration using modern AI developer workflows (GitHub Copilot, Claude).

* **Artificial Intelligence Intern · Coresium** *(Apr 2026 – May 2026 · Remote)*
  * Automated operational pipelines using n8n and REST endpoints to bridge internal analytics tools with external communication hooks.
  * Authored automated Python validation suites to scrub input data and quarantine schema anomalies before downstream processing.
  * Collaborated with engineering leads to monitor, diagnose, and maintain production data flows.

* **Python Backend &amp; Full-Stack Intern · PyGenicArc** *(Feb 2025 – May 2025 · Chitradurga)*
  * Led a 4-engineer intern team architecting DailyDrop (e-commerce platform), modularizing monolith logic into catalog, order, and payment services.
  * Designed normalized PostgreSQL schemas with connection pooling, and configured CI pipelines executing unit &amp; integration Pytests on pull requests.
</details>

---

<!-- ========================================================================= -->
<!-- GITHUB ACTIVITY & STREAK HUD                                               -->
<!-- ========================================================================= -->
<div align="center">
  <h2>📊 GITHUB ACTIVITY HUD</h2>
  <br/>
  <table align="center">
    <tr>
      <td align="center">
        <img src="https://github-readme-stats.vercel.app/api?username=Spidey173&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=38BDF8&icon_color=F43F5E&text_color=E2E8F0" alt="GitHub Stats" />
      </td>
      <td align="center">
        <img src="https://streak-stats.demolab.com?user=Spidey173&theme=tokyonight&hide_border=true&background=0D1117&ring=38BDF8&fire=F43F5E&currStreakLabel=38BDF8" alt="GitHub Streak" />
      </td>
    </tr>
  </table>
  <br/>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:090d16,50:1e1b4b,100:090d16&height=100&section=footer" width="100%" />
</div>

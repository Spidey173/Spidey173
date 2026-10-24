<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=180&section=header&text=Pruthvi%20R&fontSize=42&fontColor=ff4d4d&animation=fadeIn" alt="Pruthvi R" />

<h3 align="center">Backend, Data & Applied AI Engineer · Python · PostgreSQL · FastAPI</h3>

<p align="center">
  <a href="https://pruthvi-17.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Visit-24243e?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/pruthvir173/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:pruthvi.r0006@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

I build dependable backend and data systems—from a banking warehouse processing millions of records, to workplace-memory search that respects time, to commerce flows that protect inventory and payments.

> **Open to:** Backend Engineering and Data Engineering internships or full-time roles.

## Selected results

| 5.87M | 720,520 | 100 | 63 |
|:---:|:---:|:---:|:---:|
| banking records processed by LedgerFlow | rejected rows audited in LedgerFlow’s dead-letter queue | held-out retrieval runs in Chronexa | passing tests in DailyDrop |

## Featured projects

### 🏦 [LedgerFlow](https://github.com/Spidey173/LedgerFlow) · Banking data pipeline & analytical warehouse

A Python and PostgreSQL pipeline for 10 connected banking datasets. It streams large files in chunks, validates records in dependency order, audits rejected rows in a dead-letter queue, and bulk-loads clean data through PostgreSQL `COPY` and staged refreshes. The warehouse processed **5.87M records**: **5.15M loaded** and **720,520 quarantined**. Includes a FastAPI service, AWS S3 lakehouse layers, and **55 automated tests**.

`Python` `PostgreSQL` `Pandas` `FastAPI` `AWS S3` `Docker` · [Live dashboard](https://ledgerflow17.vercel.app/) · [API docs](https://ledgerflow17.vercel.app/docs)

### ⏱️ [Chronexa](https://github.com/Spidey173/Chronexa) · Point-in-time workplace-memory search

A local prototype for searching workplace messages, email, calendar events, transcripts, and dictation. It applies an `as_of` cutoff before retrieval to prevent future information from leaking into historical answers, combines BM25 and dense search with reciprocal-rank fusion and reranking, and supports grounded answers with abstention. Its action assistant returns schema-validated dry-run plans, with confirmation for destructive actions. Includes **46 tests** and **100 held-out retrieval runs**.

`Python` `BM25` `FastEmbed` `RRF` `Cross-encoder` `Prompt-injection defenses` · [Repository & local demo guide](https://github.com/Spidey173/Chronexa)

### 🛒 [DailyDrop](https://github.com/Spidey173/Dailydrop) · Full-stack quick-commerce application

A grocery storefront and admin platform built with Flask and PostgreSQL. Checkout recomputes prices from the server-side catalog, inventory changes happen atomically to prevent overselling, and Razorpay webhooks use signature verification and idempotency safeguards. Includes Redis caching, a background worker, **200+ products**, and **63 passing tests**.

`Python` `Flask` `PostgreSQL` `Redis` `Razorpay` `Pytest` · [Live storefront](https://dailydrop17.vercel.app/) · [Admin portal](https://dailydrop17.vercel.app/admin_login)

## Toolbox

**Backend:** Python · Flask · FastAPI · REST APIs  
**Data:** PostgreSQL · Redis · Pandas · AWS S3  
**Retrieval:** BM25 · FastEmbed · Reciprocal Rank Fusion · Cross-encoder reranking  
**Delivery:** Docker · GitHub Actions · Pytest

## Experience

**Software Engineer Intern · ElinaAI** · Remote · *Aug – Sep 2026*  
Built a React front-desk interface for appointment and patient tracking.

**AI Automation Intern · Coresium** · Remote · *Apr – May 2026*  
Built n8n workflows over REST APIs, with Python validation before processing.

**Python Full-Stack Intern · PyGenicArc** · *Feb – May 2025*  
Led a four-person team building DailyDrop, from authentication and checkout to the admin dashboard and CI.

## Education

**MCA (Online)** · Jain University · 2025–2027 · CGPA 8.45  
**Bachelor of Computer Science** · Davangere University · 2022–2025  
**Certifications:** Google IT Automation with Python · Meta Full-Stack Developer · Microsoft SQL Server

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer" alt="" />

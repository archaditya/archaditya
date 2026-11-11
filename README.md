<h1 align="center">Hi, I'm Aditya 👋</h1>

<p align="center">
  <b>Software Engineer (Backend)</b><br/>
  Node.js · TypeScript · Python (FastAPI) · Go<br/>
  Building production APIs, AI-powered products, and distributed systems.
</p>

<p align="center">
  <a href="https://archadi.dev"><img src="https://img.shields.io/badge/Portfolio-archadi.dev-111111?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/akkpk"><img src="https://img.shields.io/badge/LinkedIn-akkpk-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://x.com/archadi_dev"><img src="https://img.shields.io/badge/X-@archadi__dev-000000?style=for-the-badge&logo=x&logoColor=white" alt="X"/></a>
  <a href="mailto:akkpk933@gmail.com"><img src="https://img.shields.io/badge/Email-akkpk933@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
</p>

---

## 👨‍💻 About me

Backend Software Engineer (2 years) with production experience in **Node.js / Express (MERN)** and **FastAPI**, plus **Go** for high-concurrency services. I like owning systems end to end: design, implementation, deployment, and monitoring.

- 💼 **Day job:** Software Engineer at **Spirehubs Softwares**. I own two products: **DWIVE** (ride-hailing platform) and **Spire Engage** (multi-tenant AI agent platform)
- 🚀 **Own product:** I build, run, and market **[PushPostVault](https://www.pushpostvault.com)**, a live file-sharing SaaS used daily by teams
- 🖥️ **Ops:** All my products run on a self-managed VPS (Docker, Nginx, monitoring and observability)
- 🤖 **Applied AI:** RAG pipelines, agent frameworks, LLM integrations, AI code review
- 📬 **Open to:** SDE / Backend roles (Node.js, TypeScript, Python, Go) · Noida, hybrid or remote

---

## 🛠️ Tech stack

![Stack](https://skillicons.dev/icons?i=nodejs,express,ts,py,fastapi,go,react,nextjs,mongodb,postgres,redis,docker,nginx,linux,githubactions&perline=15)

| Area | What I use |
| --- | --- |
| **Backend** | Node.js, Express.js, FastAPI, Go, REST APIs, WebSockets, SSE |
| **Async & queues** | BullMQ, Celery, Redis Streams, Inngest |
| **Databases** | PostgreSQL, MongoDB, MySQL, Redis, Qdrant (vectors), Neo4j (graphs) |
| **Auth & payments** | JWT (access + refresh), RBAC, Razorpay, Stripe, webhook verification |
| **AI / LLM** | RAG, HyDE, Reciprocal Rank Fusion, reranking, agents, function calling, MCP |
| **Infra** | Docker, Docker Compose, Nginx, Linux, VPS, Cloudflare R2, GitHub Actions |
| **Frontend** | React, Next.js, Tailwind CSS |

---

## 💼 Experience

**Software Engineer (Backend & AI), Spirehubs Softwares** · Aug 2025 – Present
- Own two products end to end: **DWIVE** (Caribbean ride-hailing) and **Spire Engage** (AI agent for multiple clients)
- DWIVE: split a FastAPI monolith into a modular structure, implemented RBAC across 100+ routes, unified API responses, migrated auth to two-token JWT
- Built queues, rate limiting, and background jobs; a Go-based AI report analysis system over 1000+ references

**Full Stack Developer (MERN), Evren Global Solutions** · Feb 2025 – Aug 2025
- Shipped production apps end to end on MongoDB, Express, React, Node.js: IBIEA2025 (100+ award recipients), ICCIC (200+ researchers' paper submissions)
- Built an AI visa document validation pipeline

---

## 🚀 Featured projects

### 1. [PushPostVault](https://www.pushpostvault.com) · live SaaS
Send large files and collect files from clients. Resumable chunked uploads with SHA-256 verification (client and server), an atomic Redis-backed state machine with optimistic locking on PostgreSQL, self-expiring and one-time download links, guest upload invites with enforced quotas, Cloudflare R2 storage, and subscription billing. 25 registered users, 4-5 active daily.
`Go` `Next.js` `PostgreSQL` `Redis` `Cloudflare R2` `Docker` `Nginx`
[🌐 Live](https://www.pushpostvault.com) · [📦 Source](https://github.com/archaditya/bytevault)

### 2. [AI PR Review Bot](https://pr-review-bot.archadi.dev) · live platform
Multi-tenant GitHub App that reviews pull requests using a Neo4j code-dependency graph, so findings are grounded in real cross-file impact. Inline `@mention` follow-up chat, encrypted bring-your-own-key (AES-256-GCM), tenant admin dashboard, and merged PRs turned into LinkedIn / X post drafts. Three decoupled services (webhook, Node/Express API, Python/FastAPI AI engine).
`Node.js` `Express` `FastAPI` `Neo4j` `PostgreSQL` `Inngest` `Next.js`
[🌐 Live](https://pr-review-bot.archadi.dev) · [📦 Source](https://github.com/archaditya/github-pr-review-bot)

### 3. [ArchadiLM](https://archadilm.archadi.dev) · multi-tenant RAG workspace
NotebookLM-style assistant that indexes PDFs, web pages, video transcripts, and source archives, then answers with grounded, citation-backed responses. HyDE query expansion, Qdrant HNSW search, Reciprocal Rank Fusion, cross-encoder reranking, async Redis Streams ingestion workers, SSE streaming.
`Go` `FastAPI` `Qdrant` `PostgreSQL` `Redis Streams` `Cloudflare R2`
[🌐 Live](https://archadilm.archadi.dev) · [📦 Source](https://github.com/archaditya/course-bot)

### 4. [archadi-agent](https://www.npmjs.com/package/archadi-agent) · TypeScript Agent SDK (on npm)
Fluent builder API, native function-calling runner, multi-agent handoffs, guardrails, structured output, streaming events and tracing, model fallback, and a CLI (`archadi chat`).
`TypeScript` `Node.js` `npm`

<details>
<summary><b>More projects</b></summary>

| Project | What it is | Link |
| --- | --- | --- |
| **AI Engineering Playground** | Next.js 15 workspace: persona chat, multi-LLM voting, RAG, tool calling, MCP | [ai-playground.archadi.dev](https://ai-playground.archadi.dev) |
| **PR Review Pilot** | Landing and companion site for the PR review tooling | [prreviewpilot.archadi.dev](https://prreviewpilot.archadi.dev) |
| **Verkin** | Networking platform matching engineers by topic semantics (in development) | n/a |
| **ImageVibe** | Image-focused web app | [image-vibe.vercel.app](https://image-vibe.vercel.app) |
| **TaxPro** | Tax-focused web app | [taxpro-hazel.vercel.app](https://taxpro-hazel.vercel.app) |
| **Gemini Clone** | Gemini-style AI chat interface | [gemini-clone-akk.vercel.app](https://gemini-clone-akk.vercel.app) |

</details>

---

## 🧭 My journey

| When | Milestone |
| --- | --- |
| **Jul 2022** | Graduate Trainee in enterprise IT support at Wipro |
| **Late 2023** | Left IT operations, learned software development from scratch |
| **Feb 2025** | First production role as a MERN developer (Evren Global Solutions) |
| **Aug 2025** | Moved to Spirehubs: backend and applied AI work |
| **Now** | 10+ live projects shipped, running a live SaaS on my own infrastructure |

---

## ✍️ Learning in public

- 📓 [Building PushPostVault in Public](https://github.com/archaditya/bytevault/tree/main/docs/Engineering-Journal): decisions, mistakes, trade-offs
- 🧵 [Learning GenAI with JavaScript](https://aditya-engineering.hashnode.dev/): cohort notes
- 🐳 [Docker learning notes](https://github.com/archaditya/bytevault/tree/main/docs/Docker-Learning)

---

## 🤝 Let's connect

- 🌐 [archadi.dev](https://archadi.dev) · 💼 [LinkedIn](https://linkedin.com/in/akkpk) · 𝕏 [@archadi_dev](https://x.com/archadi_dev) · 🧩 [LeetCode](https://leetcode.com/akkpk933/)
- ✉️ [akkpk933@gmail.com](mailto:akkpk933@gmail.com)
- 📄 [Resume](https://www.pushpostvault.com/s/111d33ec-35ef-49b9-8991-946407df92cc)

Hiring for backend / SDE roles? I'd love to hear from you.

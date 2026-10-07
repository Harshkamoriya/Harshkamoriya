# Harsh Kamoriya

Backend engineer · Final-year ECE, NIT Surat (2027)
Production trading systems, concurrency, and low-latency APIs.

[LinkedIn](https://linkedin.com/in/harshkamoriya) · [Portfolio](https://harshkamoriya.vercel.app) · [LeetCode](LEETCODE_URL) · your-email@example.com

---

## Experience

**Software Engineer Intern, Mintzy** (fintech / algorithmic trading) · START_DATE – Present
Own production backends that execute real trades for live users. Reporting directly to the CTO and founders.

**Auto-trader engine (FastAPI, Redis, Gunicorn)**
- Built the engine that fetches ML predictions, applies entry/exit logic, and places broker orders for users during market hours. Trader workers run as separate processes from the API, coordinated through Redis (session metadata, heartbeats, stop jobs, exit queues).
- Debugged and fixed multi-worker session-state bugs, deadlocks, and race conditions found under live market load.
- Added per-symbol exposure and leverage caps, per-ticker loss-threshold exits on live ticks, and a session-scoped EOD square-off that exits only engine-owned quantity, so manual holdings on shared broker accounts are never touched.
- Ported the same core engine to 4 brokers (Angel One, Bear Street, Trader-Hut, Tradex), isolating broker-specific logic from shared trading logic.

**API gateway (Node.js, Express, MongoDB)**
- Gateway routing desktop-app trading requests to per-broker plugin servers, with JWT auth, session lifecycle APIs (start / stop / force-stop), IST-based schedulers for simulation-to-live handoff, and PnL / trade-log APIs.

**Performance**
- Prediction service latency: ~10s → ~3s by isolating and fixing a bottleneck on the request path.
- Backtesting engine: ~1 hr → ~30 min via horizontal scaling.

**Backend and infra**
- Rearchitected a messy Node.js monolith into routes / controllers / services / middlewares, with centralized error handling, auth, rate limiting, logging, config management, and a role-based admin portal.
- Migrated authentication from Clerk to custom OAuth, removing per-user registration limits.
- Docker, Nginx, PM2, and GitHub Actions CI/CD to EC2 across services.

Stack: Python, FastAPI, Node.js, Express, Redis, MongoDB, Docker, AWS, Azure, GitHub Actions

---

## Projects

### [Intervu AI](https://github.com/Harshkamoriya/REPO)
AI technical interview platform: resume-aware questions, sandboxed code execution, live proctoring.
- Resume-aware RAG pipeline (Gemini + Pinecone) generating personalized questions
- Docker-sandboxed service for compiling and testing candidate code
- Async interview workflows on Redis + BullMQ
- Live interviews over WebRTC with AssemblyAI transcription; MediaPipe-based proctoring

`Next.js · Node.js · PostgreSQL · Prisma · Redis · BullMQ · Docker`

### Other work
- [GitSaathi](https://github.com/Harshkamoriya/REPO): chat and semantic search over a repository using embeddings and retrieval
- [ChalChitra](https://github.com/Harshkamoriya/REPO): freelance marketplace with role-based auth and order lifecycle
- [API Performance Analyzer](https://github.com/Harshkamoriya/REPO): concurrent API benchmarking with latency and throughput reports

---

## Skills
**Languages:** Python, C++, JavaScript, TypeScript
**Backend:** FastAPI, Node.js / Express, REST, WebSockets
**Data:** Redis, MongoDB, PostgreSQL
**Infra:** AWS, Azure, Docker, Nginx, GitHub Actions

## Problem solving
LeetCode Knight, peak rating 1947, 1000+ problems solved.

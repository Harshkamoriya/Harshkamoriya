<h1 align="center">Hi 👋, I'm Harsh Kamoriya</h1>

<p align="center">
  <strong>Backend-focused Software Engineer · Production Systems · Distributed Infrastructure</strong>
</p>

<p align="center">
  I build backend systems, real-time applications and production services — with a particular interest in performance, reliability and distributed systems.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/harsh-kamoriya/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:harshkamoriya@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://leetcode.com/u/Harsh-32/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/>
  </a>
</p>

---

## 🧑‍💻 About Me

- 🎓 B.Tech in Electronics & Communication Engineering at **NIT Surat** (2023–2027)
- 💼 Software Development Engineer Intern at **Mintzy.in**, working on production backend services and automated trading infrastructure
- ⚙️ Experience with **backend architecture, distributed workers, concurrency, real-time systems, APIs and cloud deployment**
- 🧠 LeetCode max rating: **1947 (Knight)**
- 🚀 Currently building a freelance product and strengthening DSA, backend engineering and system design
- 🎯 Open to **Software Engineering Internship** opportunities

---

## 💼 Experience

### Software Development Engineer Intern · Mintzy.in
*Aug 2025 – [End Month 2026]*

Worked across the company's web platform, backend services, API gateway and automated trading infrastructure.

- Built and maintained backend and product features across Node.js/Express and Python/FastAPI services, including APIs, chatbot streaming and other user-facing functionality.
- Migrated the platform's authentication system from Clerk to a custom OAuth-based solution, removing external registration constraints and giving the product greater control over authentication.
- Re-architected a previously unstructured **Node.js monolithic backend** into a modular architecture with controllers, services, routes, middleware and shared libraries; introduced centralized authentication, error handling, logging, rate limiting, configuration management and role-based admin access.
- Built and maintained a **FastAPI-based automated trading engine** supporting live and simulated trading, with background trader workers, Redis coordination, broker integrations and real-time market data.
- Diagnosed and resolved production **race conditions, deadlocks and multi-worker session-management failures** affecting long-running trading sessions in a live market environment.
- Implemented trading risk and execution capabilities including exposure/leverage controls, position management, real-time risk exits, session lifecycle handling and session-scoped end-of-day square-off.
- Extended the trading infrastructure across multiple brokers — including **Angel One, Bear Street, TraderHut and Tradex** — while keeping shared trading-engine logic separate from broker-specific integrations.
- Built a **Node.js API gateway** for the desktop trading application, routing authenticated trading and session requests to broker-specific plugin services and exposing session, PnL and trade-log APIs.
- Improved performance-critical systems by reducing **ML prediction latency from ~10s to ~3s** through successive optimizations and bottleneck identification.
- Reduced a backtesting workload from approximately **1 hour to ~30 minutes** through horizontal scaling.
- Deployed and maintained production services on **AWS EC2** using Docker, Nginx, PM2 and GitHub Actions-based CI/CD.

**Tech:** Python · FastAPI · Node.js · Express · MongoDB · Redis · AWS · Docker · GitHub Actions

---

## 🧾 Freelance Work

### Stayly · Hostel & PG Rental Platform
*In development · Client engagement*

Building a full-stack hostel and PG discovery platform from product design through production deployment.

- Developing the platform across discovery, hostel listings, search/filtering and property-management workflows.
- Working across frontend, backend, database and deployment layers as the primary developer.

**Tech:** Next.js · TypeScript · Tailwind CSS · PostgreSQL

---

## 🚀 Selected Projects

### [GitSaathi](https://github.com/Harshkamoriya/Git_saathi)

AI collaboration workspace that turns GitHub repositories into searchable, conversational project knowledge.

- Built a full-stack Next.js application that ingests GitHub repositories, generates structured file summaries, creates embeddings and stores project-scoped vectors in Pinecone.
- Designed a **RAG pipeline** that retrieves relevant repository context before generating streaming Gemini responses, with source-file references to keep answers grounded in the indexed codebase.
- Built repository ingestion around GitHub and Gemini API constraints using batching, retries and usage-based project credits.
- Implemented multi-project vector isolation using **Pinecone namespaces**, allowing independent searchable knowledge spaces for different projects.
- Added AI-powered commit summarization and a meeting workflow that converts uploaded audio into transcriptions, chapters and actionable issues using AssemblyAI.
- Integrated GitHub analytics, pull requests, issues and repository metadata through Octokit.

**Tech:** Next.js · TypeScript · React · PostgreSQL · Prisma · Gemini · Pinecone · Octokit · AssemblyAI · Vercel

---

### [AeroGuide](https://github.com/Harshkamoriya/Aeroguide)

AI airport companion combining conversational AI, voice interaction and indoor navigation.

- Built the application end-to-end, including passenger chat/voice experience, airport knowledge base, backend APIs and admin interface.
- Designed a grounded conversational pipeline that classifies intent, extracts entities, queries structured airport data and generates responses rather than relying solely on free-form LLM output.
- Implemented indoor airport navigation using a custom graph representation and **Dijkstra's shortest-path algorithm**, converting paths into step-by-step walking directions.
- Built a voice pipeline using **Whisper for speech-to-text** and **pyttsx3 for text-to-speech**, with cloud/local LLM execution paths through Groq and Ollama.
- Integrated **Twilio** for proactive departure reminder calls and built background scheduling around passenger flight information.
- Designed deployment fallbacks for constrained hosting environments by separating heavy local voice dependencies from the production server stack.

**Tech:** Python · FastAPI · SQLite · WebSockets · Groq · Ollama · Whisper · Twilio · JavaScript

---

### [IntervuAI](https://github.com/Harshkamoriya/verviq)

Real-time interview platform with collaborative interviewing and sandboxed code execution.

**Tech:** Next.js · TypeScript · Node.js · PostgreSQL · Prisma · WebSockets · Docker

---

## 🧰 Technical Skills

**Languages**

Python · TypeScript · JavaScript · C++

**Backend & APIs**

Node.js · Express · FastAPI · REST APIs · WebSockets

**Frontend**

Next.js · React · Tailwind CSS

**Databases & Infrastructure**

PostgreSQL · MongoDB · Prisma · Redis · Docker

**Cloud & DevOps**

AWS · EC2 · Nginx · PM2 · GitHub Actions · CI/CD

**AI / Data**

Gemini · Pinecone · RAG · LLM APIs · AssemblyAI

---

## 🏆 Achievements

- 🥇 **LeetCode Knight** — max rating **1947**
- 🚇 Team Leader of a 6-member team at **Smart India Hackathon 2025**, building an automation prototype for Kochi Metro Rail
- 🧑‍🤝‍🧑 **Branch Councillor** of the ECE department for one year
- 🏏 Captain of the department **Cricket Team** for 2 years
- 🏆 Captain of the department **Tug of War Team**

---

## 🎓 Education

**B.Tech — Electronics & Communication Engineering**  
Sardar Vallabhbhai National Institute of Technology (NIT Surat)  
2023–2027 · **CGPA: 8.01**

---

## 🤝 Let's Connect

I'm actively looking for **Software Engineering Internship** opportunities, particularly roles involving backend engineering, distributed systems and building production software.

<p>
  📫 <strong>Email:</strong> <a href="mailto:harshkamoriya@gmail.com">harshkamoriya@gmail.com</a>
  ·
  💬 <strong>LinkedIn:</strong> <a href="https://www.linkedin.com/in/harsh-kamoriya/">linkedin.com/in/harsh-kamoriya</a>
</p>

# Siddharth Patni

**AI & Autonomous Systems Engineer** · Agentic AI · LLM Infrastructure · Robotics

M.Sc. Digital Technologies @ TU Clausthal & Ostfalia · Braunschweig, Germany

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://siddharth-portfolio-pi.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/siddharth-divyang-patni-644857185)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:patnisiddharth1311@gmail.com)

---

## About

I build AI systems that **act**, not just respond: agentic crawlers that learn from their own successes, compilers that turn human intent into verified robot skills, memory runtimes that stop agent mistakes from becoming permanent, and observability tooling that makes LLMs auditable.

My background is backend engineering (Python, FastAPI, Celery, Redis, PostgreSQL, Docker) applied to AI/ML and robotics. I care about systems that are deterministic where they can be, honest about failure, and inspectable end to end.

- 🎓 M.Sc. Digital Technologies, TU Clausthal & Ostfalia University (since Mar 2025)
- 🚆 Currently: **FastMile**, a 6-person CORE Master's Project building an LLM-guided door-to-door mobility planner (WS 2026/27)
- 🛰️ Currently: **Orbit Observers**, NeoSpace Hackathon team on the ClearSpace serviceable-satellite challenge
- 🌍 Languages: English (C1), German (A2–B1)

---

## Experience

| Role | Organisation | Focus | Period |
| --- | --- | --- | --- |
| AI Software Engineer (Research Intern) | CORE Research Group, TU Clausthal · Ciconia Systems GmbH | Vergabepilot.AI / NexusCrawler: agentic procurement-document extraction | Mar 2026 – Aug 2026 |
| Open Source Developer | Independent | RoboWeaver, MemWeaver, Sentinel, Spidey, Workflow Engine | 2025 – Present |
| Research Assistant | Academic Labs, IoT Prototyping | Robotics and embedded systems (ShopMate-R, AI Driver Safety) | 2024 – 2025 |
| Software Developer Intern | L&T Technology Services | React and Flask services, Docker CI/CD, ~30% latency reduction | Dec 2023 – May 2024 |
| Data Analyst Intern | Snapfix Ltd. | SQL automation and workflow auditing | Jun 2023 – Jul 2023 |

---

## Featured Projects

### NexusCrawler AI / Vergabepilot.AI

*Built during my research internship, CORE Research Group × Ciconia Systems*

Autonomous agentic crawling and extraction engine. Each URL runs through a **7-strategy cascade**, cheapest first (cached → deterministic → adaptive → LLM-generated scraper → learned route → computer-use agent → manual), and stops at the first success. Successful LLM scrapers and computer-use routes are saved and replayed for free. URL intelligence covers **30 portal families on every continent**, with per-domain Redis circuit breakers and rate limiting, 1,000+ URL jobs (designed for 10,000+), 32-field German document extraction and **262 tests** in CI. Failures are reported honestly, in plain-English outcome buckets.

`Python` · `FastAPI` · `Celery` · `Redis` · `PostgreSQL` · `MinIO` · `Playwright` · `browser-use` · `Next.js` · `Prometheus`

### [RoboWeaver](https://github.com/Siddharthpatni/Roboweaver)

An **LLVM-style compiler infrastructure for robotics**: `human intent → RoboIR → robot skill`. Task understanding, motion planning, safety analysis, simulation, code generation, deployment and recovery share one intermediate representation. The compiler is deterministic by default. A local Ollama co-pilot can explain results and propose fixes, but it can never bypass diagnostics, verification or deployment gates.

`Python` · `Compilers / IR` · `Motion Planning` · `Simulation` · `Ollama`

### [MemWeaver](https://github.com/Siddharthpatni/MemWeaver)

A fault-tolerant **lifelong memory runtime for AI agents**, published as `memweaver` / `engramward`. Instead of a passive vector store, it audits, buffers, reconciles and consolidates agent experience, so hallucinations, leaked data or crashed writes don't persist as permanent memory. Works with OpenAI, Claude and LangChain agents.

`Python` · `LLM Agents` · `Memory Systems` · `PyPI`

### [Sentinel](https://github.com/Siddharthpatni/Sentinel)

Drop-in **LLM observability proxy** with span-tree request waterfalls, judge-model evaluations, and a SHA-256 hash-chained audit ledger designed against EU AI Act record-keeping requirements.

`FastAPI` · `Celery` · `Next.js`

### [Spidey](https://github.com/Siddharthpatni/Spidey)

Fully offline, self-hosted **autonomous agent platform** with a live React Flow reasoning graph, Vosk speech recognition, local models via Ollama, and a two-stage SFT → DPO fine-tuning pipeline across 17 modules.

`Python` · `FastAPI` · `React Flow` · `Vosk` · `Ollama` · `Unsloth` · `TRL`

### [ShopMate-R](https://github.com/Siddharthpatni/ShopMate-R)

**Multi-robot grocery assistant**: Pepper handles dialogue, Temi handles autonomous navigation, and M5Stack IoT shelf sensors provide live inventory awareness.

`Python` · `Flask` · `Pepper` · `Temi` · `M5Stack`

---

## More Projects

| Project | Description |
| --- | --- |
| [FastMile](https://github.com/Siddharthpatni/Fast-v1) | Team project: LLM-guided intermodal route planning across multiple transport modes in one door-to-door journey |
| [Orbit Observers](https://github.com/Siddharthpatni/Orbit_Observers) | Monte Carlo simulator for rendezvous and proximity operations with tumbling GEO satellites (NeoSpace Hackathon, ClearSpace challenge) |
| [Workflow Engine](https://github.com/Siddharthpatni/Workflow_Engine) | Distributed low-code automation platform in the spirit of n8n: Bull workers, sandboxed Node VM and containerised Python runtimes |
| [Cereforge](https://github.com/Siddharthpatni/Cereforge) | Competitive AI engineering platform: 24 curated tasks, automated Gemini evaluation, XP and leaderboards |
| [AI Driver Safety](https://github.com/Siddharthpatni/ai-driver-safety) | ADAS prototype: CNN traffic-sign recognition, YOLOv4 pedestrian detection, dlib drowsiness monitoring, Arduino and OBD-II braking interface |
| [StockFlow](https://github.com/Siddharthpatni/Digital_Inventory) | Full-stack retail inventory SaaS with QR lookup, audit logging and hardened access control |
| [LLM Chatbot](https://github.com/Siddharthpatni/LLM_chatbot) | Self-hosted DialoGPT deployment optimised for Apple Silicon (MPS), containerised with Docker |
| [SmartBot](https://github.com/Siddharthpatni/Chatbot) | Offline-first FAQ assistant (Flask + React) with no external API calls |

---

## Tech Stack

**Languages:** Python, TypeScript, JavaScript, SQL

**AI / ML:** PyTorch, TensorFlow, Unsloth, TRL, SFT and DPO fine-tuning, Ollama, OpenRouter / Gemini, computer vision (CNN, YOLO, dlib)

**Agentic Systems:** browser-use computer-use agents, Playwright, cascade orchestration, self-healing code generation, agent memory

**Backend:** FastAPI, Flask, Node.js, Celery, Bull, Redis, PostgreSQL, SQLAlchemy / Alembic, MinIO

**Frontend:** React, Next.js, React Flow, Tailwind CSS

**Infrastructure:** Docker Compose, GitHub Actions, Prometheus, Vercel

**Robotics & IoT:** Pepper, Temi, Arduino, OBD-II, M5Stack, motion planning, simulation

---

## Education

| Qualification | Institution | Period |
| --- | --- | --- |
| M.Sc. Digital Technologies | TU Clausthal & Ostfalia University, Germany | Mar 2025 – Present |
| B.Tech Computer Engineering | CHARUSAT, India (CGPA 7.6/10) | 2021 – 2024 |
| Diploma in Computer Engineering | GTU, India (CGPA 8.92/10, High Distinction) | 2018 – 2021 |

---

Open to roles, research positions and collaboration in **agentic AI, LLM infrastructure and autonomous systems**. The best way to reach me is [email](mailto:patnisiddharth1311@gmail.com).

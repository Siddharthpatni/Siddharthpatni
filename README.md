# Siddharth Patni

**AI & Autonomous Systems Engineer** · Agentic AI · Computer Vision · Robotics & IoT

Braunschweig, Germany · [patnisiddharth1311@gmail.com](mailto:patnisiddharth1311@gmail.com)

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://siddharth-portfolio-pi.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/siddharth-divyang-patni-644857185)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Siddharthpatni)

---

## About

I build production-grade LLM infrastructure, computer vision pipelines, and robotics integrations. My focus is on systems that act rather than only respond: agentic web automation with self-learning fallback cascades, LLM observability tooling, multi-robot orchestration, and visual workflow engines.

Currently pursuing an M.Sc. in Digital Technologies at TU Clausthal and Ostfalia University, Germany, alongside AI research and development work at Ciconia Systems GmbH.

**Working languages:** English (C1), German (A2–B1)

---

## Experience

| Role | Organisation | Focus | Period |
| --- | --- | --- | --- |
| AI Software Engineer (R&D) | Ciconia Systems GmbH, CORE Research Group | Vergabepilot.AI, autonomous procurement document extraction | 2026 – Present |
| Open Source Developer | Independent | Spidey, Sentinel, Cereforge, Workflow Engine | 2025 – Present |
| Research Assistant | Academic Labs, IoT Prototyping | Robotics and embedded systems (ShopMate-R, AI Driver Safety) | 2024 – 2025 |
| Software Developer Intern | L&T Technology Services | React and Flask services, Docker CI/CD, ~30% latency reduction | Dec 2023 – Apr 2024 |
| Data Analyst Intern | Snapfix Ltd. | SQL automation and workflow auditing | Jun 2023 – Jul 2023 |

---

## Selected Projects

### Vergabepilot.AI

*Private research project, CORE Research Group / Ciconia Systems*

Autonomous agentic system for extracting structured data from public procurement portals across 30+ portal families. Uses a seven-stage fallback cascade (cached, deterministic, adaptive, LLM code generation, learned route, computer-use agent, manual) with replayable self-learned routes, Redis-backed circuit breakers, 32-field deep extraction, and a suite of 262 tests.

`Python` · `FastAPI` · `Celery` · `Redis` · `PostgreSQL` · `MinIO` · `Playwright` · `browser-use` · `Docker`

### [Spidey](https://github.com/Siddharthpatni/Spidey)

Self-hosted autonomous agent platform with a live React Flow reasoning graph, offline speech recognition via Vosk, local model execution through Ollama, and a two-stage SFT to DPO fine-tuning pipeline spanning 17 modules. Runs entirely offline.

`Python` · `FastAPI` · `React` · `React Flow` · `Vosk` · `Ollama` · `Unsloth` · `TRL`

### [Sentinel](https://github.com/Siddharthpatni/Sentinel)

LLM observability proxy featuring span-tree request waterfalls, judge-model evaluations, and a SHA-256 hash-chained audit ledger designed against EU AI Act record-keeping requirements.

`FastAPI` · `Celery` · `Next.js`

### [Cereforge](https://github.com/Siddharthpatni/Cereforge)

Competitive AI engineering platform with 24 curated tasks, automated evaluation via Gemini, and an XP and leaderboard progression system.

`FastAPI` · `React` · `PostgreSQL`

### [Workflow Engine](https://github.com/Siddharthpatni/Workflow_Engine)

Distributed low-code automation platform in the spirit of n8n, built on Bull workers with sandboxed Node VM and containerised Python runtimes.

`Node.js` · `React Flow` · `Redis`

### [ShopMate-R](https://github.com/Siddharthpatni/ShopMate-R)

Multi-robot grocery assistant combining Pepper for dialogue, Temi for autonomous navigation, and M5Stack IoT shelf sensors for inventory awareness.

`Python` · `Flask` · `Robotics`

---

## Additional Projects

| Project | Description |
| --- | --- |
| [AI Driver Safety](https://github.com/Siddharthpatni/ai-driver-safety) | ADAS prototype: CNN traffic sign recognition, YOLOv4 pedestrian detection, dlib drowsiness monitoring, Arduino and OBD-II braking interface |
| [Digital Inventory](https://github.com/Siddharthpatni/Digital_Inventory) | Retail SaaS with QR-based lookup, audit logging, hardened access control, and investor pitch materials |
| [LLM Chatbot](https://github.com/Siddharthpatni/LLM_chatbot) | Self-hosted DialoGPT deployment optimised for Apple Silicon (MPS), containerised with Docker |
| [SmartBot](https://github.com/Siddharthpatni/Chatbot) | Offline-first FAQ assistant built with Flask and React, requiring no external API calls |
| Multi-Disease Diagnostic | Medical image classification pipeline reaching approximately 85% accuracy and reducing per-case review from 30 minutes to 10 seconds |

---

## Technical Skills

**Languages:** Python, TypeScript, JavaScript, SQL

**AI & Machine Learning:** PyTorch, TensorFlow, Unsloth, TRL, SFT and DPO fine-tuning, Ollama, computer vision (CNN, YOLO, dlib)

**Agentic Systems:** browser-use (computer-use agents), Playwright automation, cascade orchestration, self-healing scrapers

**Backend:** FastAPI, Flask, Node.js, Celery, Bull, Redis, PostgreSQL, MinIO

**Frontend:** React, Next.js, React Flow, Tailwind CSS

**Infrastructure:** Docker, GitHub Actions, Prometheus, Vercel

**Robotics & IoT:** Pepper, Temi, Arduino, OBD-II, M5Stack

---

## Education

| Qualification | Institution | Period |
| --- | --- | --- |
| M.Sc. Digital Technologies | TU Clausthal & Ostfalia University, Germany | Mar 2025 – Present |
| B.Tech Computer Engineering | CHARUSAT, India (CGPA 7.6/10) | 2021 – 2024 |
| Diploma in Computer Engineering | GTU, India (CGPA 8.92/10, High Distinction) | 2018 – 2021 |

---

## Contact

- **Email:** [patnisiddharth1311@gmail.com](mailto:patnisiddharth1311@gmail.com)
- **LinkedIn:** [siddharth-divyang-patni](https://www.linkedin.com/in/siddharth-divyang-patni-644857185)
- **Portfolio:** [siddharth-portfolio-pi.vercel.app](https://siddharth-portfolio-pi.vercel.app)

Open to roles and collaboration in agentic AI, LLM infrastructure, and autonomous systems.

---

## About This Repository

The portfolio site is a single-page Next.js 15 application (App Router) written in TypeScript with Tailwind CSS v4, deployed on Vercel.

```bash
npm install     # install dependencies
npm run dev     # start dev server at http://localhost:3000
npm run build   # create a production build
```

**Structure**

- `app/` — layout, page, and global styles
- `components/` — page sections, UI primitives, and visual effects
- `lib/data/` — typed content for projects, experience, skills, and education

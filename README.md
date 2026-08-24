**Jose Oliveros** 🚀
================

Founding Engineer 💡 — 0→1 AI Products · Real-Time Voice · LLM Agents · Full-Stack

Engineer who builds AI products from an empty repo to production — most recently as first engineer, then technical lead, behind a real-time AI voice platform. Fourteen years shipping systems where failure is expensive: emergency-response infrastructure, Twilio's developer platform, and an 8M-user crypto wallet. Owned cloud infrastructure and DevOps (Kubernetes, Docker, Terraform, CI/CD) across regulated domains — FERPA, GDPR, ISO 9001, public safety.

📍 Brentwood, CA

### Tech Skills 🛠️
* **AI / ML:** LangChain, LangGraph, RAG · PyTorch, TensorFlow · fine-tuning (SFT, LoRA, RLHF/DPO) · reinforcement learning, Gymnasium, Optuna · ViT, ConvNeXt, OpenCV
* **Languages:** Python, TypeScript, Rust, Go, Kotlin, Ruby
* **Backend & Frontend:** FastAPI, Django, Rails, Next.js, React Native, WebRTC
* **Data:** Postgres, Redis, Trino, Elasticsearch · Kafka, Airflow, Celery
* **Infra / DevOps:** AWS, GCP, Kubernetes, Docker, Terraform, CI/CD

### Experience 🎯
* **Founding Engineer** — [Addie](https://getaddie.com) (AI-first education technology) · Oct 2024 – Present
  - First engineer for six months, then technical lead of a team of four — building hands-on across chat, voice, infra, CI/CD, and SRE, plus scoping and review. Architected a LangGraph agent system, backed by a fine-tuned model, across web, SMS, voice, and WhatsApp; 100 hrs of student conversations in month one, architected for 100K+ hrs/year. Built real-time voice on WebRTC + OpenAI Realtime API at sub-200ms latency, shipped across three Next.js web apps and a native Kotlin mobile app. Built the retrieval layer on self-hosted Qdrant for grounded, citable RAG. Owned the GCP infrastructure and cost per conversation, scaling to thousands of voice sessions daily; implemented FERPA and GDPR controls for student data across 10+ countries.
* **Generative AI Engineer** — Rubercubic · Jan 2024 – Oct 2024
  - Built LLM agents turning plain-language questions into Python, SQL, and charts, grounded by pgvector semantic search over the warehouse. Cut ad-hoc analysis from a full analyst day to under 8 seconds by fine-tuning models (SFT + LoRA) for accurate Python/Pandas and SQL generation. Designed the AWS data platform (billions of rows across Trino, Parquet on S3, Postgres, Redis, Celery) with custom SQL transforms and scraping — the clients' primary analytics interface.
* **AI Engineer** (contract) — adcopy.ai · Oct 2022 – Dec 2023
  - Built the Facebook ads integration with GDPR PII anonymization and deletion; fine-tuned PyTorch models (SFT + LoRA), lifting ad performance 30%. Designed streaming/batch ETL (SQS, RabbitMQ), pgvector semantic search, and the REST APIs behind rapid growth and a 20% retention lift.
* **Fullstack & Data Engineer** — International Public Safety Data Institute · Jan 2022 – May 2023
  - Led a small team building emergency-response systems for NIST, FEMA, and NIOSH under an ISO 9001 process. Built streaming and batch pipelines (Kafka, Airflow, Celery) over hundreds of millions of NEMSIS 911 and NFIRS records, plus a custom warehouse (S3, Trino, Elasticsearch) and PostGIS drive-time and fire-risk models powering [statengine.io](https://statengine.io) dashboards across ~27,000 fire departments.
* **Lead Fullstack Engineer** — Prominent Edge · Jan 2020 – Jan 2022
  - Led engineers on geospatial and public-safety apps for NASA, Maxar, and [firecares.org](https://firecares.org) under an ISO 9001–certified process; built Django/PostGIS APIs, owned OAuth2 access control and IAM, and ran code review.
* **Software Engineer** (contract) — Twilio · Nov 2016 – Nov 2019
  - Core contributor to Yoyodyne, a six-language code-generation tool that made tutorials 3x faster to produce; built the Rails/Django documentation platform serving 250K accounts and led TwilioQuest.
* **Frontend & Mobile Engineer** — Mycelium · Jan 2012 – Nov 2016
  - Built the native mobile apps (Java/Android, Objective-C/iOS) and the APIs for a cryptocurrency wallet serving 8M users, plus the Angular web app; contributed to the unit, integration, and e2e test suite.

### Selected Project 🔬
* **Order-Book Reinforcement-Learning Trading System** — independent research platform · 2017 – Present
  - Built solo, end to end: Rust ingest, time-series platform, RL training, backtesting, live execution, dashboard. Rewrote the market-data hot path from Python to Rust, cutting CPU and memory ~8x and shrinking the production host by two instance sizes. Trained distributional-RL agents (IQN over an axial-attention encoder, CVaR risk shaping, prioritized replay) on OpenCV-preprocessed order-book images, in a custom Gymnasium environment modeling fees, slippage, and maker fills. Ran walk-forward validation behind a deploy gate, with Optuna hyperparameter search across a self-hosted GPU cluster bursting to GCP, AWS, and RunPod; Docker Swarm, Grafana, and 80%+ CI coverage. Concluded from out-of-sample results that order-book microstructure yielded no robust edge — the validation discipline is what surfaced it.
  - Write-up: [chinnno15.github.io/work/orderbook-rl](https://chinnno15.github.io/work/orderbook-rl/)

### Education 🎓
* **M.S., Artificial Intelligence** — The University of Texas at Austin · expected 2026 — Deep Learning, Reinforcement Learning, NLP
* **B.A., Computer Science** — University of California, Berkeley · 2012

### Get in Touch 🌐
* **Website:** [chinnno15.github.io](https://chinnno15.github.io)
* **LinkedIn:** [jose-oliveros](https://www.linkedin.com/in/jose-oliveros-42a48b306/)
* **Email:** chinnno15@gmail.com

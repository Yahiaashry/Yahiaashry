# Yahia Ashry

**Software Engineer** | Full-Stack Engineer (React/Node) & AI-Enhanced Tooling

Full-stack developer focused on clean architecture, state management, and practical AI integration. I build products with a focus on data flow integrity and offline-first resilience.

· [LinkedIn](https://www.linkedin.com/in/yahia-ashry-8b4472313/) · [Email](mailto:Yahia.ashryy@gmail.com)

---

## 🛠️ Tech Stack

### Web Full-Stack
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-90C53F?style=for-the-badge&logo=express&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwind-css&logoColor=white)

### Data & Persistence
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-13AA52?style=for-the-badge&logo=mongodb&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

### Infra & Workflow
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

### Data Engineering & Scripting
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

---

## 🚀 Featured Projects

### RecruiterPro — AI-Augmented Hiring Pipeline
*React, Node.js, TypeScript, Supabase, Python (psycopg2), OpenAI API*

- **Architecture:** Designed a service-layer abstraction connecting a React frontend with a Python/Node.js backend, utilizing Supabase and `psycopg2` for robust database initialization and environment configuration.
- **Data Flow:** Streamlined the ingestion of unstructured resume data via the OpenAI API into a strict TypeScript schema, reducing manual entry by ~90% and efficiently managing large repository footprints across the pipeline.
- **Trade-offs:** Opted for a managed Supabase architecture over local database initialization to eliminate directory state conflicts and speed up deployment, accepting vendor lock-in for significantly higher database reliability during concurrent recruiter sessions.
- [View on GitHub](https://github.com/Yahiaashry/Recruiter-Pro)

### EasySpend — Offline-First Budget Tracker
*Flutter, Supabase, PostgreSQL, BLoC, SQLite*

- **Architecture:** Structured as an offline-first mobile client using the BLoC pattern to strictly separate UI events from core business logic, ensuring highly deterministic unit testing for complex monthly rollover calculations.
- **Data Flow:** Engineered a custom write-ahead log (WAL) utilizing local SQLite to queue transaction states during network partitions. Resolves merge conflicts deterministically upon reconnection via timestamped vector clocks.
- **Trade-offs:** Migrated from a schema-less Firebase implementation to a normalized PostgreSQL schema with Row-Level Security in Supabase. Traded initial client-side flexibility for a highly structured relational model, achieving a ~40% reduction in client-side JSON payload through server-side aggregation.
- [View Project](https://easy-spend-123.web.app/)

### OS System Metrics Monitor
*Python, Linux Internals, DevOps*

- **Architecture:** Built a lightweight, dependency-free daemon in Python relying strictly on native OS interfaces.
- **Data Flow:** Parses the `/proc` filesystem to continuously monitor CPU steal time and memory pressure, emitting threshold-based triggers to system notification pipelines.
- **Trade-offs:** Chose manual filesystem parsing over heavy external monitoring libraries to maintain an absolute minimal memory footprint, sacrificing out-of-the-box external integrations for pure performance.
- [View on GitHub](https://github.com/Yahiaashry/Os_System_metrics)

### AlgoLab — ML Workflow Web Interface
*Python, Flask, scikit-learn, Seaborn*

- **Architecture:** Designed a Flask-based programmatic generation service that outputs dynamic visualization figures and machine learning pipeline code.
- **Data Flow:** Ingests user-selected preprocessing parameters to dynamically compile and execute `scikit-learn` logic on structured CSV datasets.
- **Trade-offs:** Prioritized rapid boilerplate generation and UI simplicity over granular model hyperparameter tuning, optimizing for speed-to-insight in hypothesis testing rather than deep-level model customization.
- [View on GitHub](https://github.com/Yahiaashry/AlgoLab)

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yahia-ashry-8b4472313/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Yahia.ashryy@gmail.com)

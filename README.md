# Unai Pastor Martínez — Backend & Distributed Systems Engineer

> Building resilient backend architectures, offline-first systems, and scalable distributed services.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-unaipma-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/unaipma)
[![GitHub](https://img.shields.io/badge/GitHub-unaipma-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/unaipma)
[![Email](https://img.shields.io/badge/Email-unaipastormartinez3%40gmail.com-blue?style=flat-square&logo=gmail&logoColor=white)](mailto:unaipastormartinez3@gmail.com)
[![Status](https://img.shields.io/badge/Status-Eligible%20for%20J--1%20Trainee%20%2F%20Sponsorship-10b981?style=flat-square)](#)
[![Location](https://img.shields.io/badge/Location-Logro%C3%B1o%2C%20Spain%20(Open%20to%20U.S.%20Relocation)-64748b?style=flat-square)](#)

---

## 📌 Profile Overview

I design and implement high-availability distributed systems, offline-first applications, and scalable RESTful APIs. Focused on clean domain boundaries, robust data synchronization under network instability, and high-performance backend services that solve concrete operational bottlenecks.

- 📍 **Location**: Logroño, Spain (Open to U.S. Relocation)
- 🛂 **Sponsorship**: J-1 Trainee / Intern Eligible
- 🎯 **Specialization**: Distributed Backends &bull; Offline-First Systems &bull; Cloud & REST APIs

---

## 🚀 Featured Projects

### 1. [CryptoDash: Real-Time Financial Analytics Engine](https://github.com/unaipma/cryptodashboard)
*Production Platform &bull; Financial Analytics &bull; Next.js 15*

- **GitHub Repository**: [github.com/unaipma/cryptodashboard](https://github.com/unaipma/cryptodashboard)
- **Architecture Highlights**:
  - **Compute Layer**: Algorithmic Server Actions for real-time market calculations, automated technical indicators, and automated Buy/Hold/Sell signal evaluations.
  - **Runtime & Rendering**: Built on Next.js 15 App Router with React Server Components (RSC) to maintain a minimal client-side bundle footprint.
  - **Feed & Strategy**: Integrated with CoinGecko API with an aggressive in-memory caching layer to prevent rate-limiting bottlenecks.
  - **Data Visualization**: Responsive time-series charts powered by Recharts with sub-second update cycles.
- **Technologies**: Next.js 15, TypeScript, Server Actions, Real-Time Data, Recharts, Tailwind CSS.

---

### 2. [Triptoyou: Distributed Travel Management System](https://github.com/unaipma/travel-agency)
*Capstone Project &bull; Distributed Architecture &bull; Angular &amp; Laravel*

- **Live Demo**: [triptoyou.vercel.app](https://triptoyou.vercel.app)
- **GitHub Repository**: [github.com/unaipma/travel-agency](https://github.com/unaipma/travel-agency)
- **Architecture Highlights**:
  - **Distributed Topology**: Decoupled microservice-inspired architecture separating an Angular SPA (hosted on Vercel) from a stateless Laravel REST API (hosted on Railway).
  - **Storage Engine**: Serverless PostgreSQL cluster running on Neon.tech.
  - **Payments & Webhooks**: Live Stripe Checkout integration with cryptographically signed webhook reconciliation and automated state recovery.
  - **Asynchronous Workers**: Laravel background queue workers handling transactional customer emails and automated PDF booking voucher generation.
  - **Authentication**: Stateful and tokenized authentication via Laravel Sanctum.
- **Technologies**: Angular, Laravel (PHP 8.2), PostgreSQL (Neon), Stripe Gateway, Laravel Sanctum, Queue Workers.

---

### 3. [Retail POS: Hybrid Cloud Architecture & Dual-DB Sync](https://github.com/unaipma/hybrid-sync-pos-architecture)
*Enterprise System &bull; Offline-First POS &bull; C# .NET &amp; SQLite*

- **GitHub Repository**: [github.com/unaipma/hybrid-sync-pos-architecture](https://github.com/unaipma/hybrid-sync-pos-architecture)
- **Architecture Highlights**:
  - **Data Resilience & Dual-DB Sync**: Industrial-grade desktop Point of Sale (POS) engineered for retail terminals operating over unreliable WAN connections. Uses zero-latency local embedded SQLite storage with two-way conflict-resolution background synchronization against a remote PostgreSQL cluster on Neon.tech.
  - **Security & Cryptography**: SHA-256 data tamper verification and cryptographic audit logging using BouncyCastle, complemented by role-based access control (RBAC).
  - **Layered Design**: Strict N-Tier architecture (.NET / C#) enforcing separation of presentation, business logic, data access, and sync workers.
  - **Document Generation**: Automated transactional receipt and invoice generation via iText7 PDF engine.
- **Technologies**: C# (.NET), SQLite Embedded, PostgreSQL (Neon), BouncyCastle Cryptography, iText7 PDF Engine, Conflict Resolution.

---

## 💼 Work Experience

### **Software Engineer / Backend & Web Solutions** — [Hiberus](https://www.hiberus.com)
*Logroño, Spain | February 2026 – June 2026*
- Architected and implemented enterprise search and knowledge retrieval systems to efficiently query corporate documentation repositories.
- Integrated vector databases and backend services to optimize semantic retrieval, indexing pipelines, and query throughput.
- Evaluated retrieval precision, query latency, and response consistency, ensuring reliability for enterprise-scale deployment.
- Developed custom Drupal modules and automated business logic pipelines, improving operational workflows through Drupal ECA.
- **Key Skills**: Enterprise Search, Vector DBs, Backend APIs, Drupal / ECA, System Integration.

### **Backend Developer** — Globant Gut
*Logroño, Spain | February 2025 – June 2025*
- Developed modular backend components and integrated third-party RESTful APIs to optimise database performance.
- Collaborated with engineering teams using agile methodologies to produce clean, scalable code that supported project goals.
- Engineered custom architectural and functional WordPress plugins tailored to client business specifications.
- **Key Skills**: Backend APIs, RESTful Architecture, Custom Plugins, Agile / Scrum, Database Optimization.

### **Mobile QA Automation Tester** — Wunder App
*Logroño, Spain | May 2024 – June 2024*
- Executed automated testing on mobile applications across devices using Appium to enhance quality assurance.
- Tracked, documented, and reported functional bugs and regressions, contributing to production release stability.
- **Key Skills**: Appium, Test Automation, Mobile QA, Regression Testing, CI Quality Gates.

---

## 🛠️ Technical Competence & Tooling

| Domain | Technologies & Architectural Patterns |
| :--- | :--- |
| **Backend & Architecture** | PHP 8+, Laravel, Symfony, Node.js / NestJS, C# / .NET, RESTful APIs, Laravel Sanctum, JWT, Clean Architecture |
| **API Engineering & Distributed Services** | RESTful APIs, Webhooks, Queue Workers, Stripe API, API Rate-Limiting, Microservices |
| **Data & Infrastructure** | PostgreSQL (Neon.tech), SQLite Embedded, MySQL, Redis, Docker, DDEV, Git / GitHub Actions, Linux |
| **Client, QA & Testing** | TypeScript, Next.js 15, Angular, PHPUnit, Appium QA, BouncyCastle Cryptography |

---

## 🌐 Interactive Portfolio (`index.html`)

The accompanying [`index.html`](./index.html) is a production-grade interactive portfolio featuring:
- **Spotlight Lighting Engine**: Real-time cursor-following radial spotlight with reactive card-surface illumination.
- **Infinite Marquee**: Seamless marquee displaying active core technologies.
- **Bilingual Engine (ES / EN)**: Instant client-side switching with local preference persistence.
- **Direct AJAX Contact Form**: FormSubmit integration (`unaipastormartinez3@gmail.com`) with instant feedback, clipboard copy fallback, and one-click direct Gmail compose launch.

---

## 📬 Contact & Links

- 💼 **LinkedIn**: [linkedin.com/in/unaipma](https://www.linkedin.com/in/unaipma)
- 🐙 **GitHub**: [github.com/unaipma](https://github.com/unaipma)
- 📧 **Email**: [unaipastormartinez3@gmail.com](mailto:unaipastormartinez3@gmail.com)
- 🌍 **Relocation Status**: Open to U.S. relocation & J-1 Trainee / Intern Sponsorship

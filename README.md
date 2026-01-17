# Hi, I'm Anatolii 👋

**Senior Systems Architect & Full‑Stack Rust Engineer**  
Designing **high‑performance**, **mission‑critical**, and **memory‑safe** systems in **FinTech** and **DefenseTech**.

I build end‑to‑end Rust platforms: from async backends and secure storage engines to WASM frontends and infrastructure tooling. My focus is on **zero‑downtime**, **type‑safe**, and **operationally simple** systems that can run as **single binaries** in **air‑gapped** or restricted environments.

---

## 🧠 What I Do

- **Systems Architecture**
  - Event‑driven, modular Rust workspaces
  - DDD / vertical slice architectures
  - Async runtime orchestration (Tokio) and runtime profiling
  - Observability: structured logging, tracing, and self‑healing routines

- **Backend & Distributed Systems**
  - Low‑latency APIs (Axum, Hyper, Tower, Tonic/gRPC)
  - Runtime tuning: worker orchestration, stack sizing, resource isolation
  - Storage engines & sandboxed filesystems
  - Licensing & crypto flows for offline / air‑gapped deployments

- **Full‑Stack Rust / WASM**
  - Rust‑first product architecture: shared types across backend & WASM
  - Frontend with Dioxus, Tailwind, and WASM‑friendly design
  - Tight coupling between domain model and UI flows

---

## 🛠 Tech Stack

**Languages**
- Rust (primary), C#, C/C++, SQL (PL/SQL, T‑SQL, SurQL)

**Backend**
- Axum, Hyper, Tower, Tower‑HTTP  
- Tokio (custom runtime configs, tuning & orchestration)  
- Tonic (gRPC), Wasmtime  

**Frontend / WASM**
- Dioxus (Rust/WASM UI)
- Tailwind CSS
- Angular 2

**Data & Storage**
- SurrealDB (embedded & distributed)
- PostgreSQL, Oracle, MSSQL
- RocksDB, Redis
- Custom namespaced, sharded, and compressed storage layers

**Infrastructure & Systems**
- Linux systems programming
- Docker, CI‑friendly Rust workspace setups
- LLVM, CMake
- Tracing, structured logging, and operational tooling

---

## 🚀 Selected Projects

### [MusterHub](https://github.com/AnatoliiShliakhto/muster-hub)
**High‑performance personnel coordination platform** built as a **full‑stack Rust workspace**.

- **Architecture**
  - Domain‑driven, modular Rust workspace (apps, features, infra, shared domain)
  - Unified async runtime layer with tuned profiles (high‑performance vs memory‑efficient)
  - Strong typing and shared models between backend and WASM frontend

- **Key Features**
  - **Shared type safety** between WASM UI and Rust backend
  - **Embedded SurrealDB** for offline/edge deployment
  - Self‑healing storage routines and atomic write guarantees
  - Centralized logging & tracing infrastructure

- **Tech**
  - Rust, Axum, Dioxus, SurrealDB, Tokio, tracing  
  - Multi‑crate workspace with infra crates (runtime, logging, storage, licensing, DB, events, vault, etc.)

---

### [MAES – Military Aptitude & Evaluation System](https://github.com/AnatoliiShliakhto/maes)
**Offline‑first assessment and survey platform** designed for **military and enterprise environments**, optimized for **mobile devices** and **air‑gapped use**.

- **Mission Profile**
  - Full functionality **without Internet** (offline‑first)
  - Local data storage with **secure synchronization** and **encrypted backups**
  - Native installer for Windows, browser‑based client with PWA support

- **Core Capabilities**
  - Flexible tests and surveys: single/multiple choice, open answers, image‑based questions
  - **Anonymous questionnaires** with one‑time tokens/QR codes and separation of identities from responses
  - **Image‑rich tests** with offline media caching and import/export of media bundles
  - Role‑based access (administrator, manager, instructor, participant), groups and testing sessions

- **Security & Reliability**
  - **Encrypted local storage** for results and item banks
  - Encrypted export/import containers, key rotation and access policies
  - Backup/restore flows with integrity checks

- **Analytics**
  - Dashboards, filters, and statistics across tests, groups, and sessions
  - Aggregated reporting for both anonymous and identified cohorts
  - Exportable, encrypted result archives

- **Use Cases**
  - Military units: aptitude testing, field surveys, structured questionnaires in disconnected environments  
  - Education & corporate: offline exams, compliance checks, training assessments

---

### [MTC‑CMS](https://github.com/AnatoliiShliakhto/mtc-cms)
**Military Training Center Management System** designed for **air‑gapped deployments** and **operational robustness**.

- Focus on **reliability**, **simple operations**, and **minimal external dependencies**
- Architecture favors **single‑binary deployments** and deterministic behavior
- Suited for constrained environments with strict security posture

---

## 🔭 Current Focus

- **Zero‑Dependency, Single‑Binary Apps**
  - Minimize operational surface area
  - Build systems that are easy to deploy and reason about

- **Performance & Throughput**
  - Profile‑guided optimization (PGO)
  - Custom async runtime profiles (worker/thread tuning, stack sizing)
  - Low‑latency I/O and backpressure‑aware APIs

- **Security & Safety**
  - Type‑driven design to eliminate whole classes of runtime errors
  - Cryptographic licensing and secure storage primitives
  - Defensive sandboxing and path‑traversal protections

---

## 💼 What I’m Looking For

- **Roles**
  - Senior / Staff Rust Engineer
  - Systems Architect / Platform Engineer

- **Domains**
  - FinTech / Banking Platforms
  - DefenseTech, GovTech, Critical Infrastructure
  - High‑throughput, low‑latency backend systems

- **Location**
  - Remote‑first  
  - Based in **Ukraine** – open to **worldwide** collaborations

- **Status**
  - 🟢 **Open to Work**

---

## 📫 Contact

- **LinkedIn:** [anatolii-shliakhto](https://www.linkedin.com/in/anatolii-shliakhto/)
- **GitHub:** [AnatoliiShliakhto](https://github.com/AnatoliiShliakhto)
- **Email:** a.shlyakhto@gmail.com

---

## 📊 GitHub Stats

![Anatolii's GitHub stats](https://github-readme-stats.vercel.app/api?username=AnatoliiShliakhto&show_icons=true&theme=radical)  
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=AnatoliiShliakhto&layout=compact&theme=radical)

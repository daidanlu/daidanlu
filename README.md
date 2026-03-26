# Daidan Lu

I build backend services, systems-level applications, and the infrastructure around them. My work emphasizes schema design, clear API contracts, and making systems straightforward to run and operate. With a dual background in Computer Sciences and Mathematics, I also enjoy translating theoretical models into working, memory-safe software.

- **Focus:** Backend architecture, systems programming, simulation engines, API design
- **Languages:** Python, Rust, Java, C, C++, SQL, TypeScript, JavaScript
- **Frameworks:** Django, Spring Boot, React, Streamlit, Tauri
- **Ops & Datastores:** PostgreSQL, MySQL, Redis, SQLite, Qdrant, Docker, Git, Bash/Shell, GitHub Actions

---

## Featured Work

### Evolutio: Game Theory Simulation Engine (Recent)
A high-performance desktop application built with Rust, Tauri, and React for simulating evolutionary game theory and spatial cellular automata. It uses a thread-safe Rust backend to manage concurrent states via `std::sync::Mutex` and features a zero-copy HTML5 Canvas rendering pipeline, capable of running continuous stochastic simulations of tens of thousands of interacting agents with zero UI lag. This framework incorporates stochastic perturbations and replicator dynamics to analyze evolutionary stability, utilizing a memory-safe Rust core for real-time visualization of population dynamics.

### Epistemic Logic & Math Implementations (Recent)
A repository dedicated to the mathematical proof and computational simulation of classic common-knowledge logic puzzles (such as the Blue-Eyed Islanders puzzle), focusing on the algorithmic formalization of recursive reasoning and knowledge states.

### ERP Inventory & Order System (Completed / Maintained)
A full-stack platform for warehouse and order management, supporting multi-role access, ~5k SKUs, and 500+ orders/month. Designed and developed a scalable ERP system with robust relational schema design and integrated business workflow orchestration.
- **Stack:** Django REST, PostgreSQL, React, Docker Compose
- **What I did:** Designed the product and order schema, built idempotent APIs to ensure data consistency, implemented comprehensive audit logging, and structured a fully dockerized setup for seamless dev/prod deployment. 

### Local RAG QA System (Completed / Maintained)
A lightweight, privacy-focused full-stack Retrieval-Augmented Generation (RAG) system for offline document Q&A, designed for easy reproducibility.
- **Stack:** Python, Django REST, Streamlit, Qdrant (Docker), sentence-transformers, llama-cpp-python
- **What I did:** Implemented pluggable vector storage (NumPy or Qdrant), optimized local inference for consumer hardware, and built reliable frontend utilities including system health monitors and multi-file chunking pipelines. Developed modular ingestion, chunking, and vector indexing pipelines with citation-aligned context reconstruction.

---

## Other Work

I also maintain several private projects.
- **Access:** Please reach out if you’d like to see details, walkthroughs, or code snippets from these private repositories.

---

## Contact

daidan.lu.cs@gmail.com

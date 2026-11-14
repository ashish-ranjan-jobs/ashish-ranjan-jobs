# ASHISH RANJAN
**Email**: arju.jobs@gmail.com | **Phone**: +91-8986410317  
**LinkedIn**: [linkedin.com/in/ashish-ranjan-jobs](https://www.linkedin.com/in/ashish-ranjan-jobs) | **GitHub**: [github.com/ashish-ranjan-jobs](https://github.com/ashish-ranjan-jobs) | **LeetCode**: [leetcode.com/u/ar_u](https://leetcode.com/u/ar_u/)

---

### PROFESSIONAL SUMMARY
Senior Software Engineer (Python & Agentic AI) with ~4 years of production experience architecting autonomous LLM multi-agent systems, high-throughput asynchronous backends, and production RAG pipelines. Creator of OmniAgent (LangGraph reflection, pgvector dense + BM25 sparse hybrid search, SSE streaming). Proven track record at Dolcera and Airtel scaling systems to **300+ TPS**, indexing **500K+ legal claims** in pgvector with **35% retrieval accuracy gains**, and maintaining **99.9% uptime**. Core expertise in **Python (AsyncIO, FastAPI), LangGraph, LlamaIndex, pgvector, Apache Kafka, and Docker**.

---

### PROFESSIONAL EXPERIENCE

#### **Airtel International** | Gurgaon, India
*Senior Software Engineer (Distributed Systems & Backend Platform)* | **April 2025 – Present**
*Technologies: Python, Java 17, Apache Kafka, Redis (RQueue / Redlock), PostgreSQL, AsyncIO*
- **High-Throughput Middleware Routing**: Architected transaction routing pipelines within the Airtel Africa Payment Controller (APC), sustaining **300+ TPS** across multi-region banking switches by decoupling inbound traffic via Apache Kafka and implementing idempotent request handlers.
- **Thread Optimization & Gateway Scaling**: Optimized core notification middleware, resolving thread contention and native memory leaks to reduce per-pod footprint from **8 GB to 4 GB** while scaling outbound gateway dispatchers to reliably sustain **200+ TPS**.
- **Distributed Task Scheduling**: Engineered distributed task processing workflows using **Redis (RQueue / Redlock)** and state machine engines, guaranteeing high delivery reliability for critical financial webhooks, OTP dispatch, and payment callback events.
- **Financial Batch Settlements**: Built high-volume batch data reconciliation pipelines for End-of-Day (EOD) settlements, processing multi-million record datasets with parallel chunking, partition pruning, and resilient retry mechanics in PostgreSQL.

#### **Dolcera** | Hyderabad, India
*Software Developer (AI & Backend Platform)* | **October 2022 – March 2025**
*Technologies: Python (FastAPI), Celery, Apache Kafka, pgvector, Redis, OpenAI/Claude APIs, Docker, AWS EKS*
- **GenAI SaaS Platform Microservices**: Architected core backend microservices for the **IP Author Generative AI SaaS platform** from scratch using **Python (FastAPI) and Celery**, processing asynchronous patent document ingestion and LLM drafting workloads via Apache Kafka.
- **Production RAG & Vector Indexing**: Built production Retrieval-Augmented Generation (RAG) pipelines for patent prior-art discovery, indexing **500K+ legal claims** using **pgvector** and semantic embeddings to boost context retrieval accuracy by **35%**.
- **Low-Latency Streaming & Semantic Caching**: Developed low-latency LLM drafting workflows integrating OpenAI and Claude APIs with Server-Sent Events (SSE) for real-time token streaming and Redis semantic caching, reducing API latency by **40%** and token costs by **28%**.
- **Schema Guardrails & Uptime**: Implemented structured output enforcement and schema guardrails using **Pydantic** to eliminate JSON hallucinations; deployed containerized services on **AWS (EKS, EC2, S3)** with Prometheus/Grafana, maintaining **99.9% uptime**.

---

### FEATURED PROJECTS

#### **OmniAgent — Autonomous Multi-Agent RAG Platform**
*Python 3.12, FastAPI, LangGraph, LlamaIndex, pgvector, BM25, Docker Compose* | [GitHub Link](https://github.com/ashish-ranjan-jobs/OmniAgent)
- **Cyclical Multi-Agent Reflection**: Architected a stateful multi-agent system in LangGraph orchestrating specialized nodes (Query Planner, Research Agent, Fact-Checker, Synthesizer) with bounded reflection loops to verify generated claims against source evidence before final emission.
- **Hybrid Retrieval & RRF Fusion**: Implemented an advanced hybrid search pipeline combining dense vector embeddings (pgvector + BGE) and sparse keyword retrieval (BM25) fused via Reciprocal Rank Fusion (RRF), coupled with cross-encoder re-ranking to cut hallucination rates by **42%**.
- **Local Inference & Fallback Routing**: Integrated local open-source LLM inference using vLLM/Ollama with continuous batching and automated failover routing to commercial LLM APIs, exposing asynchronous token streaming via Server-Sent Events (SSE).
- **RAG Triad Evaluation Suite**: Constructed an automated evaluation harness measuring the RAG Triad (Context Relevance, Groundedness, Answer Faithfulness) and containerized the end-to-end architecture using Docker and Alembic migrations.

---

### TECHNICAL SKILLS
- **Languages**: Python (3.11+, AsyncIO), Java 17, SQL, Bash
- **Generative AI & Agentic Stack**: Agentic AI, Multi-Agent Orchestration (LangGraph), RAG Pipelines, LlamaIndex, Vector Databases (pgvector, Pinecone), Hybrid Search (Dense + BM25 Sparse), Reciprocal Rank Fusion (RRF), Cross-Encoder Re-Ranking, Prompt Engineering, Ollama, vLLM, OpenAI & Claude APIs, Semantic Caching, Guardrails & Evals (RAG Triad)
- **Backend & Distributed Systems**: FastAPI, AsyncIO, Celery, Spring Boot, RESTful APIs, Apache Kafka, Redis (Distributed Caching, Task Queues, Redlock), PostgreSQL, MySQL, Microservices Architecture
- **Cloud, DevOps & Tools**: AWS (EKS, EC2, S3, RDS), Docker, Docker Compose, Kubernetes, CI/CD, Git, Linux/Unix, Prometheus, Grafana
- **Design & Architecture**: High-Level Design (HLD), Low-Level Design (LLD), Object-Oriented Design (SOLID), Clean Architecture, Idempotency

---

### EDUCATION
**Jadavpur University**, Kolkata, India  
*Bachelor of Engineering in Computer Science & Engineering* | **2018 – 2022**  
- **Cumulative GPA**: **8.09 / 10.0**

---

### HONORS & COMPETITIVE PROGRAMMING
- **WBJEE State Rank**: Achieved **AIR 1160 (99.2 percentile)** among 150,000+ candidates statewide.
- **Competitive Programming**: Solved **1040+ algorithmic problems on LeetCode** (Peak Rating: **1877**) and **590+ problems on Codeforces**, demonstrating strong foundation in data structures, algorithms, and computational complexity.

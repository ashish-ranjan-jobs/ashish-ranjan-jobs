# ASHISH RANJAN
**Email**: arju1936@gmail.com | **Phone**: +91-7542971093  
**LinkedIn**: [linkedin.com/in/ashish-ranjan-jobs](https://www.linkedin.com/in/ashish-ranjan-jobs) | **GitHub**: [github.com/ashish-ranjan-jobs](https://github.com/ashish-ranjan-jobs) | **LeetCode**: [leetcode.com/u/ar_u](https://leetcode.com/u/ar_u/)

---

### PROFESSIONAL SUMMARY
Senior Backend & Distributed Systems Engineer with ~4 years of production experience architecting high-throughput, fault-tolerant microservices, event-driven pipelines, and transactional payment middleware. Proven track record at Airtel Africa Payment Bank and Dolcera, scaling core banking systems to **300+ TPS**, eliminating critical JVM memory leaks, and building production vector retrieval engines. Core expertise in **Java 17/21, Spring Boot 3, Apache Kafka, Redis, PostgreSQL, and Concurrency Control**.

---

### PROFESSIONAL EXPERIENCE

#### **Airtel International** | Gurgaon, India
*Software Engineer (Middleware Platform — Airtel Africa Payment Bank)* | **April 2025 – Present**
*Technologies: Java 17/21, Spring Boot, Spring Batch, Apache Kafka, Redis (RQueue), PostgreSQL, Spring State Machine, FreeMarker*
- **High-Throughput Transaction Routing**: Engineered the core transaction routing layer within the Airtel Payment Controller (APC), sustaining **300+ TPS** across multi-region banking switches by decoupling inbound traffic with Apache Kafka and enforcing idempotent request processing.
- **JVM Leak Resolution & SMPP Scaling**: Diagnosed and resolved a critical native-heap JVM memory leak in the `mfs-notify` middleware, reducing per-pod memory footprint from **8 GB to 4 GB**. Integrated the Kamex SMS gateway to scale outbound SMPP traffic, enabling application pods to sustain **200+ TPS**.
- **State Machine & Notification Delivery**: Built transaction and notification lifecycle management using **Spring State Machine** and **FreeMarker** for dynamic SMS/Email template rendering. Designed automated retry and fallback workflows using **Redis (RQueue)** to guarantee high-reliability OTP and payment callback delivery.
- **Batch Financial Reconciliation**: Developed high-throughput End-of-Day (EOD) financial reconciliation and merchant disbursement workflows using **Spring Batch**. Implemented partitioned chunking and custom skip listeners to process large settlement files with stable resource utilization.

#### **Dolcera** | Hyderabad, India
*Software Developer (Backend Systems & AI Platform)* | **October 2022 – March 2025**
*Technologies: Java, Spring Boot, FastAPI, Apache Kafka, Docker, Kubernetes, AWS EKS, Redis, PostgreSQL, pgvector*
- **Platform Architecture from Scratch**: Designed and developed backend microservices for the **IP Author SaaS platform** from inception using **Spring Boot and FastAPI**, integrating Kafka event streams for asynchronous patent document ingestion and background processing.
- **Scalable Semantic Search & Vector Indexing**: Engineered high-volume data ingestion and vector search pipelines for the Prior Art module, indexing **500K+ legal claims** using **pgvector** and semantic embeddings to boost similarity search retrieval accuracy by **35%**.
- **LLM Service Integration & Redis Caching**: Implemented backend services for automated patent drafting and prior-art analysis using LLM APIs with Server-Sent Events (SSE) streaming and Redis-based caching, reducing redundant database queries and latency.
- **Cloud Infrastructure & Reliability**: Containerized microservices using Docker and orchestrated deployments on **AWS EKS**. Built automated CI/CD deployment pipelines with Prometheus and Grafana monitoring, maintaining **99.9% service uptime**.

---

### FEATURED PROJECTS

#### **WalletDesign — Production Digital Wallet & Payment Transfer Engine**
*Java 21, Spring Boot 3.3, PostgreSQL, Spring Data JPA, Bean Validation, Lombok, Postman* | [GitHub Link](https://github.com/ashish-ranjan-jobs/WalletDesign)
- **Deadlock-Free Concurrency Control**: Implemented high-concurrency fund transfers using `PESSIMISTIC_WRITE` database locks, strictly acquiring locks in ascending wallet ID order to eliminate deadlock risks during bidirectional concurrent transactions ($A \leftrightarrow B$).
- **Domain Invariants & Ledger Auditing**: Enforced strict financial domain invariants (non-negative balances, balance ceilings, debit guards) and maintained an immutable, transactional transaction history ledger (`TxnHistory`) recording both successful and failed transfer states.
- **API Engineering**: Designed clean RESTful endpoints for user registration, wallet top-up, withdrawal, fund transfer, and paginated transaction history, complete with automated Postman test suites and global exception handling.

---

### TECHNICAL SKILLS
- **Core Languages**: Java (8, 17, 21), Python 3.12, SQL, C++
- **Backend & Frameworks**: Spring Boot 3.x, Spring Batch, Spring Data JPA, Spring State Machine, FastAPI, Hibernate, RESTful APIs, gRPC, FreeMarker, Quartz Scheduler
- **Distributed Systems & Storage**: Apache Kafka (Event Streaming, Partitioning, DLQ), Redis (RQueue, Caching, Distributed Locks), PostgreSQL, MySQL, pgvector, Microservices Architecture, Concurrency & Multithreading
- **Cloud, DevOps & Tools**: AWS (EKS, EC2, S3, RDS), Docker, Kubernetes, Linux/Unix, CI/CD, Git, Prometheus, Grafana, JVM Profiling (HikariCP tuning)
- **Design & Architecture**: High-Level Design (HLD), Low-Level Design (LLD), Object-Oriented Design (SOLID), Clean Architecture, Idempotency, Transactional Outbox

---

### EDUCATION
**Jadavpur University**, Kolkata, India  
*Bachelor of Engineering in Computer Science & Engineering* | **2018 – 2022**  
- **Cumulative GPA**: **8.09 / 10.0**

---

### HONORS & COMPETITIVE PROGRAMMING
- **WBJEE State Rank**: Achieved **AIR 1160 (99.2 percentile)** among 150,000+ candidates statewide.
- **Competitive Programming**: Solved **1040+ algorithmic problems on LeetCode** (Peak Rating: **1877**) and **590+ problems on Codeforces**, demonstrating deep mastery of advanced data structures, algorithms, and computational complexity.

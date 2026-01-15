# Hi there, I'm Violet! 👋

## 🎓 About Me
I'm a Software Engineer with a focus on **Backend & Distributed Systems & Secure AI & Cloud Infrastructure**.

- 🏆 **Top 17 / 3,761** — AWS Global Competition  
- 🧠 Engineering mindset: solve **real bottlenecks** with **explicit trade-offs**
- 🛠️ Hands-on with **high QPS, low p95, serverless, and Kubernetes systems**

**Core stack:** Java, Go, TypeScript, React · AWS · Kubernetes · PostgreSQL · DynamoDB · Redis

## 🚀 Featured Work

### 🛡️ Secure AI Inference Platform (AWS Global Competition • Top 17/3,761)
High-throughput, low-latency LLM inference gateway  
- ⚡ **Throughput:** Sustained **700 QPS** with SQS-buffered fan-out execution  
- ⏱️ **Latency:** Enforced **sub-200ms** inference with semantic filtering & fail-fast routing  
- 🔒 **Security:** Scoped JWT + short TTL + KMS rotation; prompt-injection defense  
- 🔁 **Reliability:** <3ms Bloom filter dedup for DynamoDB eventual-consistency replay attacks  
- 📉 **Cost-Effective:** Cut token usage **41%** with Redis ANN + SHA-256 dedup  

### 🧩 CogniShield Labs — Intelligent AI Content Filtering 
End-to-end Chrome extension and serverless backend for optimized digital consumption.
- 🌐 **Frontend:** Reduced cognitive overload by **28%** for 1K+ daily readers using a **React** extension with semantic chunking.
- ⚡ **Serverless Ops:** Designed REST API with **SQS buffering & Lambda autoscaling**, handling 3× traffic spikes at **94% lower compute cost**.
- ⏱️ **Performance:** Cut **p95 latency 28%** via distributed tracing and reduced Lambda cold-starts by **32%** using pre-warmed provisioned concurrency.
- 🏗️ **Infrastructure:** Built **AWS CDK (IaC)** backend, cutting deployment time **80%** while ensuring 99.8% uptime via blue-green traffic shifting.

### 🔍 Distributed Auto-Grading & Code Execution Platform (Teaching Assistant)
A production-grade distributed pipeline for 200+ concurrent student runs  
- ⚙️ **Distributed Execution:** Sharded Redis Streams consumer groups → **5× ingestion throughput** - ⏱️ **Queue Latency:** Sub-second queue depth with Kubernetes autoscaling based on stream lag  
- 🧪 **Code Safety:** Static analysis + Semgrep taint flow → **57% false alert reduction** - 🗄️ **Database Optimization:** Cut PostgreSQL load **61%** with batch reads, selective indexing & hot-row caching  
- 🛡️ **Sandbox Security:** Hardened Docker sandbox with seccomp + cgroup isolation for **2K+ untrusted runs**

### 🔒 Privacy Detection & Compliance Platform (Internship)
High-throughput PII scanning and remediation system  
- 📂 **Scale:** Processed **100K+ files/day** via streaming I/O + worker pools with **0% OOM** - 🎯 **Precision:** Achieved **95% detection precision** using NFA regex + trie-ranked token filters  
- 🗄️ **Policy Engine:** Externalized GDPR/CCPA rules into PostgreSQL → updates from days → **minutes** - 🤖 **LLM Safety:** Blocked **90% unsafe code edits** via Bedrock + RAG + AST validation  

## 🔧 Tech Stack

### Languages
Java • Go • Python • TypeScript • JavaScript (React) • C++ • SQL

### Distributed Systems
Redis Streams • Kafka • Amazon SQS • EventBridge • Microservices

### Cloud & Infra
AWS (Lambda, API Gateway, Bedrock, EC2, S3, VPC, IAM, CDK) • Docker • Kubernetes • Terraform

### Databases
PostgreSQL • DynamoDB • MySQL • MongoDB • Redis • Faiss/Milvus

### Security & DevOps
Semgrep • JWT • Bloom Filters • ANN Vector Search • RAG • GitHub Actions • CI/CD

## 🤝 Let's Connect!
📧 Email: violetfu0212@gmail.com  
💼 LinkedIn: [linkedin.com/in/violet-fu](https://linkedin.com/in/violet-fu)  
🐙 GitHub: [github.com/iamziqian](https://github.com/iamziqian)  

⚡ *"Building reliable, scalable systems — one commit at a time."*

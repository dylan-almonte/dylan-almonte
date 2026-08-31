<!-- Dylan Cabahug-Almonte | GitHub Profile README -->

<h1 align="center">👋 Hey, I'm Dylan Cabahug-Almonte</h1>
<p align="center">
  <b>B.S. Electrical & Computer Engineering @ Carnegie Mellon University</b><br/>
  <i>Minor in Machine Learning | December 2026</i><br/><br/>
  <a href="mailto:dcabahug@andrew.cmu.edu">
    <img src="https://img.shields.io/badge/Email-dcabahug%40andrew.cmu.edu-red?logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/dcalmonte">
    <img src="https://img.shields.io/badge/LinkedIn-Dylan%20Cabahug--Almonte-blue?logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/dylapi">
    <img src="https://img.shields.io/badge/GitHub-dylan--almonte-black?logo=github" />
  </a>
  <a href="https://maps.google.com/?q=Carnegie+Mellon+University">
    <img src="https://img.shields.io/badge/Location-Pittsburgh%2C%20PA-orange?logo=google-maps&logoColor=white" />
  </a>
</p>

---

## ⚡ About Me

I'm a **systems and ML engineer** passionate about building efficient, scalable, and intelligent infrastructure — from **distributed protocols** and **real-time kernels** to **deep learning frameworks** and **agentic AI systems**.

Currently building a **personalized agent harness** and continuing research at CMU on **efficient LLM fine-tuning** and **dynamic model routing**.

💼 Industry experience:
- **Capital One (Summer 2026)** – led design of a full-stack KMS policy risk assessment tool on Capital One's GenAI Platform; built an agentic AI solution for automated compliance remediation, scaling to 500+ applications
- **Capital One (Summer 2025)** – engineered performance-testing infrastructure for Customer Relationships APIs across 15+ microservices (10K+ TPS, 5ms latency) serving 185M+ users
- **Ansys (Spring 2025)** – migrated Visual Studio solutions to CMake, improving cross-platform builds and CI for a large-scale C++ codebase

🔬 Research:
- **CMU Research Assistant** – LoRA fine-tuning pipelines for LLaMA 3 8B, contextual bandit model routing, and multi-adapter architecture benchmarking

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/Code-Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Code-C/C++-00599C?logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/Code-Go-00ADD8?logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Code-Java-ED8B00?logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/Code-TypeScript-3178C6?logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/Code-SQL-4479A1?logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Code-Bash-4EAA25?logo=gnubash&logoColor=white" /><br/>
  <img src="https://img.shields.io/badge/Framework-PyTorch-EE4C2C?logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/Framework-React-61DAFB?logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Framework-LangChain-1C3C3C?logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Framework-Spring_Boot-6DB33F?logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Tools-CUDA-76B900?logo=nvidia&logoColor=white" /><br/>
  <img src="https://img.shields.io/badge/Tools-Docker-2496ED?logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Tools-AWS-232F3E?logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Tools-Linux-FCC624?logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Tools-Jenkins-D24939?logo=jenkins&logoColor=white" />
  <img src="https://img.shields.io/badge/Tools-CMake-064F8C?logo=cmake&logoColor=white" />
  <img src="https://img.shields.io/badge/DB-Cassandra-1287B1?logo=apachecassandra&logoColor=white" />
  <img src="https://img.shields.io/badge/DB-DuckDB-FFF000?logo=duckdb&logoColor=black" />
</p>

---

## 🚀 Featured Projects

<details>
<summary><b>🧠 Mini Deep Learning Framework (Python, C++, CUDA)</b></summary>

- Built a minimal deep learning framework from scratch with tensor operations, reverse-mode automatic differentiation, and dynamic computation graphs
- Implemented optimized GPU kernels using CUDA for matrix multiplication, convolution, and gradient propagation — **20x speedup** over CPU
- Integrated modular components for end-to-end training of MLPs and CNNs with performance profiling

🧩 *Technologies:* Python, C++, CUDA, NumPy
</details>

<details>
<summary><b>🗄️ Query Execution Engine (C++)</b></summary>

- Designed a row-based vectorized query execution engine supporting sequential scans, inserts, updates, deletes, and B+Tree index scans with dynamic key-size template dispatching
- Architected hash join with Grace partitioning, nested loop/index joins, aggregation, external merge sort, and window functions
- Implemented optimizer rules to convert sequential scans into index scans and nested loop joins into hash joins

🧩 *Technologies:* C++, Database Internals
</details>

<details>
<summary><b>🌲 Concurrent B+Tree Index (C++)</b></summary>

- Implemented a concurrent B+Tree index with thread-safe search, insertion, and deletion supporting node splitting, merging, and key redistribution
- Designed a tombstone buffer on leaf pages for deferred deletions as a simplified Bε-tree optimization
- Applied optimistic latch crabbing with read/write page guards for high-throughput parallel operations without a global latch

🧩 *Technologies:* C++, Concurrency, Data Structures
</details>

<details>
<summary><b>🔄 Raft Consensus Algorithm (Go)</b></summary>

- Developed the Raft replicated state machine protocol with leader election, log replication, and commitment across concurrent peers via RPC
- Engineered AppendEntries and RequestVote RPCs with election timeouts, heartbeats, and election restriction for consistent leader election under network partitions
- Handled log consistency with conflict detection, nextIndex backtracking, and majority-based commit advancement

🧩 *Technologies:* Go, Distributed Systems, Concurrency
</details>

<details>
<summary><b>🎨 Text-to-Image Generation with Q-Former (PyTorch)</b></summary>

- Trained a Q-Former adapter bridging a frozen GPT-2 and a frozen Diffusion Transformer (DiT) for text-conditioned image generation on CIFAR-10 with classifier-free guidance
- Constructed learnable query embeddings with multi-layer self-attention, cross-attention over GPT-2 hidden states, and per-layer projection to DiT conditioning vectors

🧩 *Technologies:* PyTorch, Diffusion Models, Generative AI
</details>

<details>
<summary><b>⛏️ Distributed Bitcoin Miner (Go)</b></summary>

- Designed the **Live Sequence Protocol (LSP)** for reliable UDP communication with sliding window, exponential backoff, and checksum-based integrity
- Built a client-server architecture with load balancing, fault tolerance, and task redistribution
- Achieved concurrency using goroutines and channels for scalable, efficient shared computing

🧩 *Technologies:* Go, Networking, UDP, Distributed Systems
</details>

<details>
<summary><b>⏱️ Real-Time Operating System (C, ARM Assembly)</b></summary>

- Built a real-time kernel with context switching, task scheduling, and mutex synchronization on ARM Cortex-M
- Implemented **rate-monotonic scheduling (RMS)** with Utilization Bound schedulability checks
- Designed thread control blocks (TCBs) for priority-based multi-threading management

🧩 *Technologies:* C, ARM Cortex-M, Embedded Systems, RTOS Design
</details>

<details>
<summary><b>📊 Fast Fourier Transform (Python, CUDA)</b></summary>

- Implemented FFT from first principles using the recursive Cooley-Tukey algorithm, reducing complexity from O(N²) to O(N log N)
- Validated correctness against NumPy's backend and benchmarked performance vs. naive DFT to demonstrate scalability

🧩 *Technologies:* Python, CUDA, Signal Processing
</details>

---

## 📊 GitHub Stats

[![GitHub Streak](https://streak-stats.demolab.com?user=dylan-almonte&theme=github-dark-blue&hide_border=true)](https://git.io/streak-stats)

## 🎯 What I'm Working On

- 🤖 Building a **personalized agent harness** for customizable AI workflows
- 🔬 Research on **efficient LoRA fine-tuning** and dynamic model routing at CMU
- 🧠 Exploring **agentic AI systems** and LLM-powered tooling

---

## 💬 Let's Connect!

If you're interested in **ML systems**, **agentic AI**, or **systems engineering**,
feel free to reach out — I love collaborating and discussing new ideas!

📫 [dcabahug@andrew.cmu.edu](mailto:dcabahug@andrew.cmu.edu)
💼 [linkedin.com/in/dcalmonte](https://www.linkedin.com/in/dcalmonte)

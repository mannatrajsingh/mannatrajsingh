<div align="center">

# Mannat Raj Singh

B.Tech Computer Science & Social Sciences · IIIT-Delhi

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/mannat-raj-singh-a49a163b6)
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/mannatrajsingh)
[![Codeforces](https://img.shields.io/badge/Codeforces-1200%2B-1F8ACB?logo=codeforces&logoColor=white)](https://codeforces.com)
[![Email](https://img.shields.io/badge/Email-mannat24333@iiitd.ac.in-EA4335?logo=gmail&logoColor=white)](mailto:mannat24333@iiitd.ac.in)

</div>

I build across three tracks: low-level systems and networking in C, machine learning with honest leakage-free evaluation, and full-stack software engineering. I care about code that respects how the machine actually works — and models measured against baselines that actually prove value.

---

## Tracks

| ![Systems](https://img.shields.io/badge/Track_1-Systems_%26_Networking-1D9E75?style=flat) | ![ML](https://img.shields.io/badge/Track_2-AI_%2F_ML-7F77DD?style=flat) | ![SDE](https://img.shields.io/badge/Track_3-Software_Engineering-D85A30?style=flat) |
|:---:|:---:|:---:|
| C · C++ · POSIX · pthreads | Python · XGBoost · PyTorch | Java · Spring Boot · Node.js |
| Raw sockets · HTTP · LRU cache | Transformers · scikit-learn · NLP | React · MySQL · MongoDB |
| CPU scheduling · RISC-V · OS internals | Time series · Recommender systems | REST APIs · Docker · System design |

---

## Projects

### ![Systems](https://img.shields.io/badge/-Systems_%26_Networking-1D9E75?style=flat-square) &nbsp;Systems & Networking

**[HTTP/1.1 Server with LRU Web Cache](https://github.com/mannatrajsingh)** &nbsp;·&nbsp; `C` `POSIX Sockets` `pthreads`

Multithreaded HTTP/1.1 server built from scratch — raw POSIX sockets, manual request parsing, content-type detection, thread-per-connection model. Custom mutex-protected LRU cache (doubly-linked list, 10-item capacity) serving repeated requests from memory; exposes `X-Cache HIT/MISS` headers and a `/stats` endpoint. No HTTP library used.

---

**[OS Component Suite — Scheduler + Shell](https://github.com/mannatrajsingh)** &nbsp;·&nbsp; `C` `POSIX APIs`

Five CPU scheduling algorithms (FCFS, SJF, SRTF, Priority, Round Robin) in a modular C framework, evaluated across 1,000+ randomized workloads on waiting time, turnaround, fairness, and starvation. SRTF cut average waiting time ~20–30% vs FCFS. Paired with a Unix shell supporting 10+ external commands, 3 built-ins, background jobs, and signal handling. `Aug–Dec 2025 · Individual`

---

**[Multithreaded File Search Engine](https://github.com/mannatrajsingh)** &nbsp;·&nbsp; `C` `POSIX Threads` `Mutexes` `File I/O`

Concurrent word-search engine using POSIX threads and a mutex-protected work queue for thread-safe, balanced file processing across distributed file systems. PDF support via poppler and a live Tkinter results view. `Nov–Dec 2025 · Team of 2`

---

**[RISC-V Assembler & Simulator](https://github.com/mannatrajsingh)** &nbsp;·&nbsp; `Python` `RISC-V RV32I ISA`

Custom assembler converting RV32I assembly into 32-bit binary — 20+ instructions across R/I/S/B/J formats. Paired with an instruction-level simulator modeling 32 registers, the program counter, and memory. Validated on 50+ test cases with accurate control-flow for branches, jumps, and virtual halt. `Jan–Apr 2025 · Team of 4`

---

### ![ML](https://img.shields.io/badge/-AI_%2F_ML-7F77DD?style=flat-square) &nbsp;AI / ML

**[Sales Demand Forecasting](https://github.com/mannatrajsingh)** &nbsp;·&nbsp; `Python` `XGBoost` `pandas` `scikit-learn`

Daily store-sales forecasting on the real Rossmann dataset (1M+ records, 1,115 stores) with leakage-free lag/rolling/promo/calendar features and a time-aware validation split. XGBoost vs seasonal-naive baseline — **RMSE down ~69%, MAPE 37.6% → 10.0%**. Rolling averages, promotions, and day-of-week identified as top drivers. `Jan–Mar 2026 · Individual`

---

**[Amazon Review Sentiment Classifier](https://github.com/mannatrajsingh)** &nbsp;·&nbsp; `Python` `scikit-learn` `Hugging Face Transformers`

Interpretable TF-IDF baselines (~77% accuracy) vs fine-tuned DistilBERT (91% / 0.91 F1) on real Amazon reviews — a ~14-point gain via transfer learning. Measures the accuracy-vs-interpretability trade-off and quantifies uncertainty from small test-set evaluation, rather than assuming the bigger model wins. `Jun 2026 · Individual`

---

**[Movie Recommendation System](https://github.com/mannatrajsingh)** &nbsp;·&nbsp; `Python` `NumPy` `scikit-learn`

Evaluated on MovieLens 100K (100K ratings, 943 users, 1,682 movies) with a leakage-free 80/20 split. Baseline ladder (global-mean → bias → user-based CF) plus from-scratch Funk SVD matrix factorization — **RMSE 1.124 → 0.922 (~18%)**. Includes an honest top-N ranking analysis (popularity beats rating-optimized MF on Precision@10). `May–Jul 2025 · Individual`

---

### ![SDE](https://img.shields.io/badge/-Software_Engineering-D85A30?style=flat-square) &nbsp;Software Engineering

**[SpaceSync — Coworking Space Booking Platform](https://github.com/mannatrajsingh)** &nbsp;·&nbsp; `Java` `Spring Boot` `Spring Data JPA` `MySQL`

Multi-role booking platform with geo-aware space search (Haversine formula) and a fairness-score ranking system to balance member commute distances. Pessimistic locking and 6 MySQL triggers prevent double-booking and enforce constraints with full audit logging. `Jan–Apr 2026 · Team of 3`

---

**[Academic ERP System](https://github.com/mannatrajsingh)** &nbsp;·&nbsp; `Java` `Swing` `JDBC` `MySQL`

Role-based university ERP for Admin / Instructor / Student workflows — secure authentication, session management, course enrollment, grading, and CSV transcript generation for 100+ records. Separate Auth and ERP databases for access safety. `Sep–Nov 2025 · Team of 2`

---

## Experience

**Software Engineer Intern** — Kar Pragati Technologies, Gurugram &nbsp;·&nbsp; *May–Jun 2026*
- Built and deployed a Decision Tree-based predictive maintenance system for EV fleets with real-time health scoring and live analytics, monitoring 500+ vehicles.
- Automated fleet reporting pipeline (Node.js, Nodemailer, MongoDB Atlas), reducing manual reporting effort by 80%.

**Undergraduate Researcher** — IIIT-Delhi (Advisor: Dr. Sujay Deb) &nbsp;·&nbsp; *May 2026–Present*
- Researching Dynamic Voltage and Frequency Scaling (DVFS) and energy efficiency in modern processors.
- Investigating LLM inference optimization via phase-aware frequency scaling for speculative decoding.
- Analyzing hardware side-channel leakage from energy-driven frequency scaling in parallel graph processing.

---

## Skills

| | |
|---|---|
| **Languages** | C, C++, Python, Java, JavaScript, HTML/CSS |
| **ML & Data** | scikit-learn, XGBoost, PyTorch, Hugging Face Transformers, pandas, NumPy, Matplotlib |
| **Systems** | POSIX APIs, pthreads, raw sockets, HTTP, memory management, CPU scheduling, RISC-V |
| **Web & Backend** | Flask, FastAPI, Node.js, React, Spring Boot, Spring Data JPA |
| **Tools** | Git, Linux, MySQL, MongoDB, Docker, Google Colab, VS Code, LaTeX |
| **Concepts** | TCP/IP, concurrency, system design, DBMS, distributed systems, network protocols |
| **Coursework** | Probability & Statistics, Linear Algebra, Convex Optimization, Algorithm Design, Econometrics |

---

## Highlights

- 🏆 **Rank 663 / 16,000+** — Goldman Sachs India Hackathon 2026
- 🔑 **Round 1 qualifier** — Google India Big Code Challenge 2026
- ⚡ **1200+ Codeforces rating**
- 📜 Google AI Essentials certified · JP Morgan Chase Advanced SWE (Forage)
- 🎓 B.Tech CSSS @ IIIT-Delhi · 2024–2028
- 🤝 Core Member @ Cyfuse · PR Team @ ESYA · Vidyanjali volunteer (85 hours)

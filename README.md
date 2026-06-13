# Hey! I'm Mannat Raj Singh

Welcome to my GitHub profile!
I'm a Computer Science & Social Sciences undergrad at **IIIT-Delhi**, working across **Machine Learning, LLMs, and Systems Programming**. I like building things that are measured honestly — leakage-free evaluation, baselines that actually prove a model adds value, and low-level code that respects how the machine really works.

---

## 🛠️ Skills & Tools

**Programming Languages:**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34F26?logo=html5&logoColor=white)

**Frameworks & Libraries:**

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Transformers-FFD21E?logoColor=black)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Java Swing](https://img.shields.io/badge/Java%20Swing-5382A1?logoColor=white)

**Tools & Platforms:**

![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?logo=googlecolab&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?logo=intellijidea&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?logo=visualstudiocode&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white)

---

## 📊 Domains & Specializations

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-2E8B57?logoColor=white)
![NLP](https://img.shields.io/badge/Natural%20Language%20Processing-8A2BE2?logoColor=white)
![LLMs](https://img.shields.io/badge/LLMs%20%26%20Transformers-FF8C00?logoColor=white)
![Time Series](https://img.shields.io/badge/Time%20Series%20Forecasting-1E90FF?logoColor=white)
![Recommender Systems](https://img.shields.io/badge/Recommender%20Systems-C71585?logoColor=white)
![Operating Systems](https://img.shields.io/badge/Operating%20Systems-556B2F?logoColor=white)
![Systems Programming](https://img.shields.io/badge/Systems%20Programming-696969?logoColor=white)
![Concurrency](https://img.shields.io/badge/Concurrency%20%26%20Threads-B22222?logoColor=white)
![DSA](https://img.shields.io/badge/Data%20Structures%20%26%20Algorithms-4682B4?logoColor=white)
![Computer Architecture](https://img.shields.io/badge/Computer%20Architecture-800000?logoColor=white)
![DBMS](https://img.shields.io/badge/Database%20Design-CD853F?logoColor=white)
![Econometrics](https://img.shields.io/badge/Econometrics-2F4F4F?logoColor=white)
![Convex Optimization](https://img.shields.io/badge/Convex%20Optimization-FF4500?logoColor=white)

- **Machine Learning** — XGBoost | Random Forest | Decision Trees | SVM | Logistic Regression | Funk SVD
- **NLP & LLMs** — TF-IDF baselines | DistilBERT fine-tuning | transfer learning | inference optimization
- **Systems & OS** — POSIX threads | CPU scheduling | a Unix shell | memory & process management | RISC-V
- **Evaluation** — leakage-free splits | honest baselines | reporting % improvement that actually proves value

---

## 🧠 Projects

### Sales Demand Forecasting
> Daily store-sales forecasting on the real **Rossmann** dataset (1M+ records, 1,115 stores) with leakage-free lag/rolling/promo/calendar features and a time-aware split. An **XGBoost** model beats a seasonal-naive baseline — **~69% lower RMSE**, MAPE cut from 37.6% → 10.0%.
>
> **Tech Stack:** Python, XGBoost, pandas, scikit-learn

### Movie Recommendation System
> Evaluated recommender on **MovieLens 100K** (100K ratings, 943 users, 1,682 movies) with a leakage-free 80/20 split. Baseline ladder (global-mean → bias → user-based CF) plus a from-scratch **Funk SVD** matrix factorization — **RMSE 1.124 → 0.922 (~18%)** — with an honest top-N ranking analysis.
>
> **Tech Stack:** Python, NumPy, scikit-learn

### Amazon Review Sentiment Classifier
> Sentiment classifier for real Amazon reviews: interpretable **TF-IDF** baselines (~77% accuracy) vs a fine-tuned **DistilBERT** (91% / 0.91 F1, ~14-point gain), measuring the accuracy-vs-interpretability trade-off instead of assuming the bigger model wins.
>
> **Tech Stack:** Python, scikit-learn, Hugging Face Transformers

### Operating Systems Component Suite — Scheduler + Shell
> Five CPU scheduling algorithms (FCFS, SJF, SRTF, Priority, Round Robin) in a modular C framework, evaluated over 1000+ randomized workloads on waiting time, turnaround, fairness, and starvation (SRTF cut avg waiting ~20–30% vs FCFS). Paired with a **Unix shell** supporting 10+ external commands, 3 built-ins, background jobs, and signal handling.
>
> **Tech Stack:** C, POSIX APIs

### Multithreaded File Search Engine
> Concurrent word-search engine in C using **POSIX threads** and a mutex-protected work queue for thread-safe, balanced file processing, with PDF support and a live Tkinter results view.
>
> **Tech Stack:** C, POSIX Threads, Mutexes, File I/O

### Escape the Maze — AI Maze Runner
> Java Swing maze game with real-time enemy AI driven by **A\*** pathfinding — ~40–60% fewer node expansions than BFS/Dijkstra via heuristic-guided search, with BFS connectivity checks guaranteeing 100% solvable mazes.
>
> **Tech Stack:** Java, Java Swing, A\*, BFS

### Academic ERP System
> Role-based university ERP for Admin / Instructor / Student workflows with secure authentication, session management, course enrollment, grading, CSV transcript generation, and Auth–ERP database separation.
>
> **Tech Stack:** Java, Swing, JDBC, MySQL

### RISC-V Assembler & Simulator
> A custom assembler converting RV32I assembly into 32-bit binary (20+ instructions across R/I/S/B/J formats) and an instruction-level simulator modeling 32 registers, the program counter, and memory — validated on 50+ test cases.
>
> **Tech Stack:** Python, RISC-V RV32I ISA, File I/O

---

## 📚 Education

**B.Tech, Computer Science & Social Sciences (CSSS)** @ IIIT-Delhi
2024 – 2028

---

## 💼 Experience

- **Software Engineer Intern @ Kar Pragati Technologies** — built a Decision Tree-based predictive maintenance system for EV fleets with live health scoring, plus an automated reporting pipeline (Node.js, Nodemailer, MongoDB Atlas).
- **Undergraduate Researcher @ IIIT-Delhi** — researching DVFS and energy efficiency, including phase-aware frequency scaling for LLM speculative decoding and hardware side-channel leakage in parallel graph processing.

---

## 🏅 Highlights

- **1200+ Codeforces rating**
- **Rank 663 / 16,000+** in the Goldman Sachs India Hackathon 2026
- Qualified for **Round 1 of Google India's Big Code Challenge 2026**
- **Google AI Essentials** certified
- Core Member @ Cyfuse · PR Team @ ESYA
- Vidyanjali community teaching volunteer (85 hours)

---

## 📫 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/YOUR_LINKEDIN)
[![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white)](https://github.com/mannatrajsingh)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?logo=leetcode&logoColor=black)](https://leetcode.com/YOUR_LEETCODE)

📧 mannat24333@iiitd.ac.in

---

*"Measuring honestly beats claiming loudly."*

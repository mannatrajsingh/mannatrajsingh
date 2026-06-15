<div align="center">

<h1>Mannat Raj Singh</h1>

<p>CS & Social Sciences @ IIIT-Delhi &nbsp;·&nbsp; 2024–2028</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/mannat-raj-singh-a49a163b6)&nbsp;
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/mannatrajsingh)&nbsp;
[![Email](https://img.shields.io/badge/mannat24333@iiitd.ac.in-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mannat24333@iiitd.ac.in)&nbsp;
[![Codeforces](https://img.shields.io/badge/Codeforces-1200%2B-1F8ACB?style=flat-square&logo=codeforces&logoColor=white)](https://codeforces.com/profile/mannatrajsingh)

</div>

<br>

I build across three tracks: **low-level systems & networking** in C, **ML pipelines** with leakage-free evaluation and honest baselines, and **full-stack software** that actually ships. I care about code that respects how the machine works — and models measured against baselines that prove they add value.

<br>

---

## 🏆 &nbsp;Quick stats

<div align="center">

| 663 / 16,000+ | 1200+ | Round 1 qualifier |
|:---:|:---:|:---:|
| Goldman Sachs India Hackathon 2026 | Codeforces rating | Google Big Code Challenge 2026 |

</div>

---

## ⚡ &nbsp;Tracks & skills

<table>
<tr>
<td width="33%" valign="top">

### 🟢 &nbsp;Systems & Networking
*Low-level C, OS internals, raw networking from scratch*

`C / C++` `POSIX APIs` `pthreads` `mutexes`
`raw sockets` `HTTP/1.1` `LRU cache`
`CPU scheduling` `memory management`
`RISC-V RV32I`

</td>
<td width="33%" valign="top">

### 🟣 &nbsp;AI / Machine Learning
*Leakage-free evaluation, honest baselines, real datasets*

`Python` `XGBoost` `scikit-learn` `PyTorch`
`Hugging Face Transformers` `DistilBERT`
`TF-IDF` `time series` `Funk SVD`
`recommender systems`

</td>
<td width="33%" valign="top">

### 🟠 &nbsp;Software Engineering
*Full-stack products, databases, backend systems*

`Java` `Spring Boot` `Node.js` `React`
`Flask` `FastAPI` `MySQL` `MongoDB`
`Docker` `system design` `REST APIs`
`Git` `Linux`

</td>
</tr>
</table>

---

## 🧠 &nbsp;Projects

<table>
<tr>
<td width="50%" valign="top">

#### 🟢 &nbsp;[HTTP/1.1 Server with LRU Web Cache](https://github.com/mannatrajsingh)
`C` `POSIX Sockets` `pthreads` &nbsp;·&nbsp; *Jun 2026 · Individual*

Multithreaded HTTP/1.1 server built entirely from scratch — raw POSIX sockets, manual request parsing, content-type detection, thread-per-connection. Custom mutex-protected LRU cache (doubly-linked list, 10-item) with `X-Cache HIT/MISS` headers and a `/stats` endpoint. Zero libraries.

</td>
<td width="50%" valign="top">

#### 🟣 &nbsp;[Sales Demand Forecasting](https://github.com/mannatrajsingh)
`Python` `XGBoost` `pandas` `scikit-learn` &nbsp;·&nbsp; *Jan–Mar 2026 · Individual*

Daily forecasting on real Rossmann data (1M+ records, 1,115 stores). Leakage-free time-aware split with lag, rolling-window, promo & calendar features. XGBoost vs seasonal-naive baseline.

> **RMSE −69% · MAPE 37.6% → 10.0%**

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🟠 &nbsp;[SpaceSync — Coworking Booking Platform](https://github.com/mannatrajsingh)
`Java` `Spring Boot` `Spring Data JPA` `MySQL` &nbsp;·&nbsp; *Jan–Apr 2026 · Team of 3*

Multi-role booking with geo-aware space search (Haversine formula), fairness-score ranking to balance commute distances, pessimistic locking, and 6 MySQL triggers preventing double-booking with full audit logging.

</td>
<td width="50%" valign="top">

#### 🟣 &nbsp;[Amazon Review Sentiment Classifier](https://github.com/mannatrajsingh)
`Python` `scikit-learn` `Hugging Face Transformers` &nbsp;·&nbsp; *Jun 2026 · Individual*

TF-IDF baselines (~77% accuracy) vs fine-tuned DistilBERT (91% / 0.91 F1). Measures the accuracy-vs-interpretability trade-off rather than assuming the bigger model wins.

> **+14 points over the best classical baseline**

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🟢 &nbsp;[OS Component Suite — Scheduler + Shell](https://github.com/mannatrajsingh)
`C` `POSIX APIs` &nbsp;·&nbsp; *Aug–Dec 2025 · Individual*

Five CPU scheduling algorithms (FCFS, SJF, SRTF, Priority, Round Robin) evaluated across 1,000+ randomized workloads. Paired with a Unix shell: 10+ external commands, 3 built-ins, background jobs, signal handling.

> **SRTF avg wait time −20–30% vs FCFS**

</td>
<td width="50%" valign="top">

#### 🟣 &nbsp;[Movie Recommendation System](https://github.com/mannatrajsingh)
`Python` `NumPy` `scikit-learn` &nbsp;·&nbsp; *May–Jul 2025 · Individual*

MovieLens 100K with leakage-free 80/20 split. Baseline ladder (global-mean → bias → user CF) plus from-scratch Funk SVD. Honest top-N finding: popularity beats rating-optimized MF on Precision@10.

> **RMSE 1.124 → 0.922 (~18%)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 🟢 &nbsp;[Multithreaded File Search Engine](https://github.com/mannatrajsingh)
`C` `POSIX Threads` `Mutexes` `File I/O` &nbsp;·&nbsp; *Nov–Dec 2025 · Team of 2*

Concurrent word-search engine with mutex-protected work queue for thread-safe, balanced file processing across distributed file systems. PDF support via poppler and a live Tkinter results view.

</td>
<td width="50%" valign="top">

#### 🟠 &nbsp;[Academic ERP System](https://github.com/mannatrajsingh)
`Java` `Swing` `JDBC` `MySQL` &nbsp;·&nbsp; *Sep–Nov 2025 · Team of 2*

Role-based ERP for Admin / Instructor / Student workflows. Secure auth, session management, course enrollment, grading, CSV transcript generation, and Auth–ERP database separation for access safety.

</td>
</tr>
</table>

---

## 💼 &nbsp;Experience

**Software Engineer Intern** &nbsp;·&nbsp; Kar Pragati Technologies, Gurugram &nbsp;·&nbsp; *May–Jun 2026*
- Built & deployed a Decision Tree-based predictive maintenance system for EV fleets — real-time health scoring, live analytics, 500+ vehicles monitored.
- Automated fleet reporting pipeline (Node.js, Nodemailer, MongoDB Atlas), reducing manual effort by **80%**.

**Undergraduate Researcher** &nbsp;·&nbsp; IIIT-Delhi · Advisor: Dr. Sujay Deb &nbsp;·&nbsp; *May 2026–Present*
- Researching Dynamic Voltage and Frequency Scaling (DVFS) and energy efficiency in modern processors.
- Investigating LLM inference optimization via phase-aware frequency scaling for speculative decoding.
- Analyzing hardware side-channel leakage from energy-driven frequency scaling in parallel graph processing.

---

## 📚 &nbsp;Coursework

`Probability & Statistics` `Linear Algebra` `Multivariate Calculus` `Convex Optimization` `Algorithm Design & Analysis` `Database Management Systems` `Econometrics` `Discrete Mathematics` `Digital Circuits`

---

<div align="center">

*Google AI Essentials certified &nbsp;·&nbsp; JP Morgan Chase Advanced SWE (Forage)*
*Core Member @ Cyfuse (Tech Club, IIIT-Delhi) &nbsp;·&nbsp; PR Team @ ESYA (Annual Tech Fest)*
*Vidyanjali community teaching volunteer — 85 hours*

</div>

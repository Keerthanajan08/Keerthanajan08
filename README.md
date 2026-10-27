
# Hey, I'm Keerthana Sasidaran! 👋

### 💻 Software Engineer | 🤖 AI/ML | 🧠 LLMs & Agentic Systems

I build practical software at the intersection of **AI, backend engineering, and intelligent systems** — from LLM security gateways and semantic caching to multimodal machine learning and predictive maintenance.

I enjoy turning complex technical ideas into **measurable, testable, real-world solutions**.

📍 Bengaluru, India  
🔬 IEEE Xplore Published Research  
🛠️ Open-Source Contributor @ Lamatic AgentKit  
🎓 M.Tech in Computer Science & Engineering

---

## 🚀 What I Work On

🤖 **AI/ML Engineering** — Machine learning, NLP, multimodal AI, anomaly detection  
🧠 **LLM Systems** — RAG, semantic caching, prompt security, agentic workflows  
⚙️ **Backend Engineering** — Python, FastAPI, REST APIs, PostgreSQL  
📊 **Data & Analytics** — SQL, dbt, Snowflake, Tableau

---

## 🧩 Featured Projects

### 🛡️ [LLM Prompt-Security Gateway](https://github.com/Keerthanajan08/LLM-Prompt-Security-Gateway)

A security layer for LLM applications that detects sensitive information, semantic data leakage, and prompt injection.

- 🔍 Scans both prompts and model responses.
- 🧬 Combines pattern-based detection with embedding-based semantic search.
- ⚡ Includes Redis-backed verdict caching and an OpenAI-compatible API.
- 🧪 Uses automated tests to validate security-related behavior.

**Stack:** `Python` `FastAPI` `NLP` `Embeddings` `Redis` `LangChain` `pytest`

### ⚡ [Semantic Cache Gateway](https://github.com/Keerthanajan08/Semantic-Cache-Gateway)

A FastAPI gateway that reuses responses for semantically similar queries, reducing redundant LLM calls, with a RAG fallback when no suitable cache match is found.

📈 **Benchmark highlights — 15 paraphrased support queries**

| Similarity threshold | Cache-hit rate | Avg. hit latency | Avg. miss latency |
|---|---:|---:|---:|
| 0.90 | 6.7% | 13.0 ms | 64.9 ms |
| 0.85 | 6.7% | 13.8 ms | 65.2 ms |
| 0.80 | 6.7% | 15.8 ms | 66.2 ms |
| 0.75 | 20.0% | 17.3 ms | 66.8 ms |
| 0.70 | 40.0% | 13.6 ms | 65.4 ms |

🎯 The benchmark explores the trade-off between cache reuse and the risk of incorrect semantic matches at different similarity thresholds.

**Stack:** `Python` `FastAPI` `Sentence Transformers` `Redis` `RAG` `pytest`

### 📊 [AI Data Analysis & ML Agent](https://github.com/Keerthanajan08/AI_Data_Analysis_ML_Agent)

An interactive Streamlit application that turns raw datasets into actionable analysis and machine-learning workflows.

- 🔎 Automated profiling, missing-value checks, duplicate detection, and data-quality scoring.
- 📈 Visualizations, correlations, and ML task suggestions.
- 🤖 Baseline classification and regression model training and comparison.
- 📦 Exportable scikit-learn pipelines and single-sample predictions.
- 📄 Downloadable Markdown, Word, and PDF reports.
- ✨ Optional AI-powered insights using OpenAI and Gemini.

**Stack:** `Python` `Streamlit` `Pandas` `NumPy` `scikit-learn` `OpenAI` `Gemini`

### 🎙️ [Multimodal Hate Speech Detection](https://github.com/Keerthanajan08/MultiLingualHateSpeech)

An IEEE Xplore research project exploring hate-speech detection across text, audio, and video.

- 🦙 Fine-tuned LLaMA 2 for hate-speech classification.
- 🎧 Integrated Whisper and Google Speech API for audio transcription.
- 🎬 Developed a multimodal processing pipeline.
- 🏆 The existing project profile reports an F1 score of **0.96**.

**Stack:** `Python` `LLaMA 2` `Hugging Face` `Whisper` `ASR` `PEFT`

### 💳 [Credit Risk & Loan Portfolio Analytics](https://github.com/Keerthanajan08/Credit_Risk_Loan_Portfolio_Analysis)

An end-to-end analysis of **2.26 million LendingClub loans**, examining default risk and portfolio-level loss concentration.

- 🔍 Analyzes risk across loan grades, borrower profiles, geography, and loan vintages.
- 📉 Identifies Grade F–G loans as the highest-default-risk segment, with reported default rates of 37–41%.
- 💰 Examines loss concentration in high-volume Grade B–C segments.
- 🗃️ Includes SQL analysis, dbt models, exploratory data analysis, and a five-page Tableau dashboard.

**Stack:** `Python` `Pandas` `SQL` `dbt` `Snowflake` `Tableau`

---

## 🌱 Open Source

### 🛡️ [Lamatic AgentKit — PII Sovereign Guardrail]([https://github.com/Lamatic/AgentKit/pull/335](https://github.com/Lamatic/AgentKit/tree/main/kits/pii-sovereign-guardrail))

Contributed TypeScript middleware for protecting personally identifiable information in LLM workflows.

- 🔐 Implemented sensitive-data handling with fail-closed behavior.
- 🧩 Focused on protecting sensitive values during external LLM interactions.
- ✅ Contribution merged into Lamatic AgentKit.

**Stack:** `TypeScript` `LLM Security` `Agent Systems`

---

## 💼 Experience

### ⚙️ Software Engineer Intern — Phoenix Wireless Systems Pvt. Ltd.
📅 *Oct 2025 – Aug 2026* · 📍 Bengaluru, India

- 🔧 Built Python/FastAPI backend services for RF equipment testing, including REST APIs, validation, PostgreSQL persistence, and test-run management.
- ⚡ Reduced RF test-analysis time from **2 hours to 20 minutes — an 83% reduction**.
- 📡 Developed diagnostic workflows integrating test history, live measurements, and maintenance records.
- 🤖 Achieved **0.89 F1** for anomaly detection and **0.91 macro-F1** across five fault categories.
- 🛠️ Developed predictive-maintenance workflows combining equipment test, service, and failure data to generate equipment-risk scores.

**Stack:** `Python` `FastAPI` `REST APIs` `PostgreSQL` `SQL` `Pandas` `Machine Learning`

### 🩻 Intern — Philips Innovation Campus
📅 *Nov 2023 – Sep 2024* · 📍 Bengaluru, India

- 🔬 Worked on ML-driven predictive maintenance for early defect detection in diagnostic devices.
- ⚡ Reduced validation time by **over 95%** using Postman API workflows and PowerShell automation.
- 🐛 Investigated memory, installation, and platform-stability issues through log analysis and backend debugging.
- 🖥️ Prototyped a virtualized diagnostic testing environment using Hyper-V and Windows PE.
- 🌐 Developed a PXE-bootable diagnostics framework for remote troubleshooting and recovery.

🏆 **Recognition:** First Place — Philips IGT Bangalore Hackathon

**Stack:** `Machine Learning` `Python` `Postman` `PowerShell` `Hyper-V` `Windows PE` `PXE`

---

## 🧰 Tech Stack

**Languages**  
`Python` `SQL` `JavaScript` `TypeScript` `C#`

**AI / Machine Learning**  
`PyTorch` `scikit-learn` `Pandas` `NumPy` `NLP` `LLMs` `Transformers` `Embeddings` `Multimodal AI` `ASR` `Anomaly Detection` `Predictive Maintenance`

**LLM Engineering**  
`RAG` `Semantic Caching` `LangChain` `LangGraph` `MCP` `Prompt Engineering` `LLM Security` `Agentic Systems` `Hugging Face` `LLaMA 2`

**Backend & Databases**  
`FastAPI` `Flask` `Django` `REST APIs` `PostgreSQL` `MySQL` `Redis`

**Data & Analytics**  
`SQL` `dbt` `Snowflake` `Tableau` `Power BI` `Data Pipelines` `Feature Engineering`

**Developer Tools**  
`Git` `GitHub` `Docker` `pytest` `Postman` `PowerShell` `Hyper-V` `Windows PE`

---

## 🎓 Education

🎓 **M.Tech — Computer Science & Engineering**  
Ramaiah Institute of Technology (MSRIT) · 2022–2024  
🏅 CGPA: **8.57/10** · First Class with Distinction

🎓 **B.Tech — Computer Science & Engineering**  
M.S. Ramaiah University of Applied Sciences (MSRUAS) · 2018–2022  
🏅 CGPA: **8.88/10**

---

## 🏅 Publications & Recognition

- 📚 Research publication in IEEE Xplore
- 📖 Book chapter published by IGI Global
- 🥇 First Place — Philips IGT Bangalore Hackathon
- ☁️ AWS AI & ML Scholars program
- 🤝 Merged open-source contribution to Lamatic AgentKit

---

## 🤝 Let's Connect!

💼 **LinkedIn:** [Keerthana Sasidaran](https://www.linkedin.com/in/keerthana-sasidaran-64ba24368/)  
💻 **GitHub:** [@Keerthanajan08](https://github.com/Keerthanajan08)  
📧 **Email:** [keerthana08sasidaran@gmail.com](mailto:keerthana08sasidaran@gmail.com)

✨ *Always interested in building useful software, exploring AI systems, and solving interesting engineering problems.*

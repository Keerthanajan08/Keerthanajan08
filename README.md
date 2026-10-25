# Hi, I'm Keerthana Sasidaran

### Software Engineer \| AI/ML Systems · LLM Infrastructure · Backend Engineering

I build practical software at the intersection of AI and backend
engineering, spanning LLM security, semantic caching, multimodal machine
learning, data analytics, and predictive maintenance.

My focus is on building testable systems, evaluating model performance,
and turning AI capabilities into usable applications and backend
services.

-   **Focus areas:** Software Engineering, AI/ML, LLM Infrastructure,
    Backend Systems
-   **Research:** Published work in IEEE Xplore
-   **Open source:** Contributor to Lamatic AgentKit
-   **Location:** Bengaluru, India

------------------------------------------------------------------------

## Featured Projects

### 1. [LLM Prompt-Security Gateway](https://github.com/Keerthanajan08/LLM-Prompt-Security-Gateway)

A security gateway for LLM traffic designed to detect sensitive
information, semantic data leakage, and prompt injection.

-   Scans prompts and model responses for sensitive information.
-   Combines pattern-based detection with embedding-based semantic
    search.
-   Includes a Redis-backed verdict cache and an OpenAI-compatible API
    interface.
-   Uses automated tests to validate security-related behavior.

**Technologies:** Python, FastAPI, NLP, Embeddings, Redis, LangChain,
pytest

### 2. [Semantic Cache Gateway](https://github.com/Keerthanajan08/Semantic-Cache-Gateway)

A FastAPI gateway that caches semantically similar queries to reduce
redundant LLM calls and latency. When a suitable cache match is
unavailable, it falls back to retrieval-augmented generation (RAG).

**Benchmark:** 15 paraphrased support queries

  ------------------------------------------------------------------------
  Similarity   Cache-hit rate       Avg. hit      Avg. miss      LLM calls
  threshold                          latency        latency        avoided
  ------------ -------------- -------------- -------------- --------------
  0.90                   6.7%        13.0 ms        64.9 ms           1/15

  0.85                   6.7%        13.8 ms        65.2 ms           1/15

  0.80                   6.7%        15.8 ms        66.2 ms           1/15

  0.75                  20.0%        17.3 ms        66.8 ms           3/15

  0.70                  40.0%        13.6 ms        65.4 ms           6/15
  ------------------------------------------------------------------------

The benchmark illustrates the trade-off between cache reuse and the risk
of incorrect semantic matches as the similarity threshold changes.

**Technologies:** Python, FastAPI, Sentence Transformers, Redis, RAG,
pytest

### 3. [AI Data Analysis & ML Agent](https://github.com/Keerthanajan08/AI_Data_Analysis_ML_Agent)

An end-to-end Streamlit application for analyzing CSV and Excel datasets
and completing a first-pass machine-learning workflow.

-   Automates dataset profiling, column detection, missing-value checks,
    duplicate checks, and data-quality scoring.
-   Generates visualizations, correlation summaries, and ML task
    suggestions.
-   Trains and compares baseline classification and regression models.
-   Exports trained scikit-learn pipelines and supports single-sample
    predictions.
-   Generates downloadable Markdown, Word, and PDF reports.
-   Supports optional AI-assisted insights through OpenAI and Gemini.

**Technologies:** Python, Streamlit, Pandas, NumPy, scikit-learn, OpenAI
API, Gemini API

### 4. [Multimodal Hate Speech Detection](https://github.com/Keerthanajan08/MultiLingualHateSpeech)

An IEEE Xplore research project exploring hate-speech detection across
text, audio, and video.

-   Fine-tuned LLaMA 2 for hate-speech classification.
-   Integrated Whisper and Google Speech API for audio transcription.
-   Developed a multimodal processing pipeline for text, audio, and
    video inputs.
-   The existing project profile reports an **F1 score of 0.96**.

**Technologies:** Python, LLaMA 2, Hugging Face, Whisper, ASR, PEFT

### 5. [Credit Risk & Loan Portfolio Analytics](https://github.com/Keerthanajan08/Credit_Risk_Loan_Portfolio_Analysis)

An end-to-end credit-risk analytics project examining **2.26 million
LendingClub loans** using Python, SQL, dbt, Snowflake, and Tableau.

-   Analyzes default risk across loan grades, borrower profiles,
    geography, and loan vintages.
-   Distinguishes default frequency from total dollar-loss
    concentration.
-   Identifies Grade F--G loans as the highest-default-risk segment,
    with reported default rates of 37--41%.
-   Highlights concentration risk in high-volume Grade B--C segments,
    with reported losses of approximately \$452M--\$592M per segment.
-   Includes SQL analysis, dbt data models, exploratory analysis, and a
    five-page Tableau dashboard.

**Technologies:** Python, Pandas, SQL, dbt, Snowflake, Tableau

------------------------------------------------------------------------

## Open-Source Contributions

### [Lamatic AgentKit --- PII Sovereign Guardrail](https://github.com/Lamatic/AgentKit/pull/335)

Contributed TypeScript middleware for protecting personally identifiable
information in LLM workflows.

-   Implemented sensitive-data handling with fail-closed behavior.
-   Focused on protecting sensitive values during external LLM
    interactions.
-   Contributed through a merged pull request.

**Technologies:** TypeScript, LLM Security, Agent Systems

------------------------------------------------------------------------

## Professional Experience

### Software Engineer Intern --- Phoenix Wireless Systems Pvt. Ltd.

*Oct 2025 -- Aug 2026 · Bengaluru, India*

-   Developed Python/FastAPI backend services for RF equipment testing,
    including REST APIs, input validation, PostgreSQL persistence,
    test-run management, and equipment-history retrieval.
-   Automated RF test analysis by transforming raw measurements into
    standardized results, applying engineering validation rules,
    flagging out-of-limit conditions, and generating reports ---
    reducing analysis time from **2 hours to 20 minutes (83%
    reduction)**.
-   Built equipment diagnostics workflows integrating test history, live
    measurements, and maintenance records to investigate abnormal
    readings.
-   Integrated ML fault detection, achieving **0.89 F1 for anomaly
    detection** and **0.91 macro-F1 across five fault categories**.
-   Developed predictive-maintenance workflows using SQL and Pandas to
    combine equipment test, service, and failure data and generate
    equipment-risk scores.

**Technologies:** Python, FastAPI, REST APIs, PostgreSQL, SQL, Pandas,
Machine Learning, RF Analytics

### Intern --- Philips Innovation Campus

*Nov 2023 -- Sep 2024 · Bengaluru, India*

-   Worked on ML-driven predictive maintenance for early defect
    detection in diagnostic devices.
-   Automated functional and integration validation using Postman-based
    API workflows and PowerShell, reducing validation time by **over
    95%**.
-   Investigated hard-to-reproduce defects involving memory consumption,
    installation behavior, and platform stability through log analysis
    and backend debugging.
-   Prototyped a virtualized diagnostic testing environment using
    Hyper-V and Windows PE to validate installation workflows across
    production-like configurations.
-   Developed a PXE-bootable diagnostics framework for remote
    troubleshooting and system recovery.

**Recognition:** First Place --- Philips IGT Bangalore Hackathon.

**Technologies:** Machine Learning, Python, Postman, PowerShell,
Hyper-V, Windows PE, PXE, Software Validation

------------------------------------------------------------------------

## Technical Skills

-   **Languages:** Python, SQL, JavaScript, TypeScript, C#
-   **AI/ML:** PyTorch, scikit-learn, Pandas, NumPy, NLP, LLMs,
    Transformers, Embeddings, Multimodal AI, ASR, Anomaly Detection,
    Predictive Maintenance
-   **LLM Engineering:** RAG, Semantic Caching, LangChain, LangGraph,
    MCP, Prompt Engineering, LLM Security, Agentic Systems, Hugging
    Face, LLaMA 2
-   **Backend & APIs:** FastAPI, Flask, Django, REST APIs, PostgreSQL,
    MySQL, Redis
-   **Data & Analytics:** SQL, dbt, Snowflake, Tableau, Power BI, Data
    Pipelines, Feature Engineering
-   **Engineering Tools:** Git, GitHub, Docker, pytest, Postman,
    PowerShell, Hyper-V, Windows PE

------------------------------------------------------------------------

## Education

### M.Tech --- Computer Science & Engineering

**Ramaiah Institute of Technology (MSRIT)**\
CGPA: 8.57/10 · First Class with Distinction · 2022--2024

### B.Tech --- Computer Science & Engineering

**M.S. Ramaiah University of Applied Sciences (MSRUAS)**\
CGPA: 8.88/10 · 2018--2022

------------------------------------------------------------------------

## Publications & Recognition

-   Research publication in IEEE Xplore
-   Book chapter published by IGI Global
-   First Place --- Philips IGT Bangalore Hackathon
-   AWS AI & ML Scholars program
-   Merged open-source contribution to Lamatic AgentKit

------------------------------------------------------------------------

## Connect

-   **GitHub:** [@Keerthanajan08](https://github.com/Keerthanajan08)
-   **LinkedIn:** [Keerthana
    Sasidaran](https://www.linkedin.com/in/keerthana-sasidaran-64ba24368/)
-   **Email:** [keerthana08sasidaran@gmail.com](mailto:keerthana08sasidaran@gmail.com)

Interested in software engineering, AI/ML engineering, backend systems, and LLM infrastructure.

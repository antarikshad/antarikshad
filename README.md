## Antariksha Dhanure

**AI/ML Engineer** · M.S. Computer Science (AI/ML) at the University at Buffalo, graduating Dec 2026 · New York

I build AI systems and the evals that keep them honest: multi-agent pipelines, retrieval over text and images, and ML models measured against real production traces rather than only demo cases.

**Now:** AI Systems Intern at [Circular.eco](https://circular.eco), where I test and tune production multi-agent workflows (MCP servers, A2A communication) across a discover → validate → review → serve pipeline. I also evaluate the platform's multimodal embedding model and design the retrieval experiments that guide which model replaces it.

**Before:** As a Graduate Research Assistant at UB, I built anomaly and fault detection pipelines for CGM sensor time-series data that catch sensor faults within 3–6 hours of onset. Earlier, I was a Data Analyst Intern at AB Infinity Soft Solution, building SQL and Power BI reporting and NLP sentiment analysis.

Open to full-time AI/ML engineering roles starting February 2027.

---

### Toolbox

**LLMs and Retrieval**<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black">
<img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white">
<img src="https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white">
<img src="https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square">
<img src="https://img.shields.io/badge/CLIP-555555?style=flat-square">

**Classical ML and Evaluation**<br>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white">
<img src="https://img.shields.io/badge/XGBoost-337AB7?style=flat-square">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white">
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white">
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white">

**Data, Backend and Infra**<br>
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white">
<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white">
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black">

---

### Selected Work

#### [Multimodal RAG for Research Papers](https://github.com/antarikshad/Multimodal-RAG)
This system answers questions over ArXiv deep learning papers using both their text and their figures. It indexes 2,746 text chunks and 306 CLIP image vectors in a dual-collection ChromaDB store, with hybrid sparse and dense retrieval feeding a local LLM served through Ollama.<br>
`Python` `PyTorch` `CLIP` `ChromaDB` `Ollama`<br>
**Outcome:** query latency down 95%, image retrieval adds only about 160 ms, and a tuned CLIP threshold recovers the image hit rate across every benchmark query.

#### [Voice-Controlled Desktop Assistant](https://github.com/antarikshad/AI-Desktop-Assistant)
A desktop assistant driven by spoken commands. It uses an audio classifier built on MFCC features and a CNN, with signal preprocessing for real-world noise and an LLM layer that interprets conversational commands.<br>
`PyTorch` `CNN` `MFCC` `LLM integration`<br>
**Outcome:** 25–35% better command recognition than baseline models in noisy conditions.

#### [TrustNova: Loan Approval Modeling](https://github.com/antarikshad/TrustNova)
An automated loan-approval and credit-scoring model. I compared Logistic Regression, Random Forest and gradient boosting on accuracy, fairness and interpretability, not accuracy alone.<br>
`scikit-learn` `XGBoost` `Feature engineering`<br>
**Outcome:** accuracy up 18% over baseline, with an estimated 40% reduction in manual review effort.

---

### What I'm Digging Into
- Evaluating LLM agents in production: judge models, escalation behavior and catching silent failures
- Running smaller open models locally for agent workloads, and measuring the trade-off between cost and quality
- Selecting embedding models for multimodal retrieval using logged traces instead of leaderboard scores

### Get in Touch
<a href="mailto:antarikshadhanure@gmail.com"><img src="https://img.shields.io/badge/Email-333333?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
<h1 align="center">Antariksha Dhanure</h1>

<p align="center">
  <b>AI/ML Engineer</b> &nbsp;|&nbsp; M.S. Computer Science (AI/ML), University at Buffalo &nbsp;|&nbsp; New York
</p>

<p align="center">
  <a href="mailto:antarikshadhanure@gmail.com"><img src="https://img.shields.io/badge/Email-333333?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

### About

I build and evaluate AI systems, including multi-agent pipelines, retrieval-augmented generation and ML models built to hold up in production. I focus on measuring what models actually do: designing evals, finding failure modes and turning the findings into better systems.

### Experience

| Role | Organization | Period |
|---|---|---|
| **AI Systems Intern** | Circular.eco | Jul 2026 – Present |
| **Graduate Research Assistant** | University at Buffalo | Oct 2025 – Jan 2026 |
| **Data Analyst Intern** | AB Infinity Soft Solution | May 2023 – Jul 2023 |

- **Circular.eco:** I test and tune production multi-agent workflows built on MCP servers and A2A communication, and evaluate multimodal embedding models for text and image retrieval.
- **University at Buffalo:** I built anomaly and fault detection pipelines for CGM sensor time-series data that flag faults within 3–6 hours of onset.
- **AB Infinity:** I built SQL and Power BI dashboards and NLP sentiment analysis, which cut manual reporting time by 30%.

### Featured Projects

| Project | Description | Stack |
|---|---|---|
| [**Multimodal RAG**](https://github.com/antarikshad/Multimodal-RAG) | A RAG system that retrieves both text and images from ArXiv papers. Hybrid search reduced query latency by 95%. | Python, PyTorch, CLIP, ChromaDB, Ollama |
| [**AI Desktop Assistant**](https://github.com/antarikshad/AI-Desktop-Assistant) | Speech command recognition with CNN and MFCC features, 25–35% more accurate than baseline models in noisy settings. | PyTorch, CNN, LLM integration |
| [**TrustNova**](https://github.com/antarikshad/TrustNova) | A loan approval and credit scoring model, compared across Logistic Regression, Random Forest and XGBoost. It reduced manual review effort by 40%. | Python, XGBoost, scikit-learn |
| [**Portfolio**](https://github.com/antarikshad/Portfolio) | A full-stack personal site with reusable React components and Flask REST APIs. | React, TypeScript, Flask |

### Tech Stack

**Languages**<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
<img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white">

**ML / AI**<br>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white">
<img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black">
<img src="https://img.shields.io/badge/XGBoost-337AB7?style=flat-square">
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white">
<img src="https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white">

**Data, Web and Tools**<br>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white">
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB">
<img src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black">
<img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white">

### GitHub Stats

<p align="left">
  <img height="160" src="https://github-readme-stats.vercel.app/api?username=antarikshad&show_icons=true&hide_border=true&theme=default&count_private=true" alt="GitHub stats">
  <img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=antarikshad&layout=compact&hide_border=true" alt="Top languages">
</p>

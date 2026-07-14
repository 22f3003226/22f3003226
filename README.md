<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="light.svg">
  <img alt="Shibashish Banerjee" src="dark.svg" width="100%">
</picture>

<br><br>

![IIT Madras](https://img.shields.io/badge/IIT%20Madras-BS%20Data%20Science-0078D4?style=flat-square)&nbsp;
![CGPA](https://img.shields.io/badge/CGPA-8.86%20%2F%2010-2EA44F?style=flat-square)&nbsp;
![WorldQuant](https://img.shields.io/badge/WorldQuant%20Brain-AIR%2017-F4A261?style=flat-square)&nbsp;
![Graduating](https://img.shields.io/badge/Graduating-2027-9B59B6?style=flat-square)

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/shibashish-banerjee-iitm)&nbsp;
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:shibashishbanerjee89@gmail.com)&nbsp;
[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-FFD21E?logoColor=black)](https://huggingface.co/xytan2022)

</div>

<br>

---

Third-year at IIT Madras. The projects here aren't demos — they're shipped. CivicSync won first place at an Anthropic hackathon and processes 23,000+ legislative documents in production. Messy Mashup hits 0.95 macro F1 and runs live on Hugging Face. I'm focused on the parts of AI that break in practice: retrieval that doesn't hallucinate, models that hold up on edge cases, systems that don't quietly fail in production.

**Open to ML / AI Engineering internships.**

<br>

---

## ⚙️ Projects

<br>

### 🏆 [CivicSync](https://github.com/22f3003226/Civic-Sync) &nbsp;·&nbsp; *1st Place — Anthropic Hackathon @ IIT Madras*

AI-powered Q&A and summarization tool for Indian parliamentary legislation. Routes 23,000+ documents through a dual-model Claude pipeline — Haiku handles classification and routing, Sonnet handles synthesis — backed by hybrid BM25 + Voyage AI retrieval. Hallucination control is deterministic: every response is grounded in retrieved document chunks, not model memory. That distinction matters when the source material is legal text. Ranked #1 nationally.

![Claude API](https://img.shields.io/badge/Claude%20API%20(Haiku%20+%20Sonnet)-CC785C?style=flat)&nbsp;
![Voyage AI](https://img.shields.io/badge/Voyage%20AI-7C3AED?style=flat)&nbsp;
![BM25](https://img.shields.io/badge/BM25-6B7280?style=flat)&nbsp;
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white&style=flat)&nbsp;
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black&style=flat)

[→ GitHub](https://github.com/22f3003226/Civic-Sync) &nbsp;·&nbsp; [→ Live Demo](https://xytan2022-civicsync.hf.space/)

<br>

---

### 🎵 [Messy Mashup](https://huggingface.co/spaces/xytan2022/messy-mashup) &nbsp;·&nbsp; *0.95 Macro F1 · Deployed*

Multi-class audio genre classifier. An ensemble of four architectures — AST, EfficientNetB0, AudioResNet34, and a custom CNN — all trained on mel spectrograms, merged via soft-vote ensemble. The gap between single-model and ensemble F1 was about 4 points — not massive, but consistent across every class. Deployed and running on Hugging Face Spaces.

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white&style=flat)&nbsp;
![torchaudio](https://img.shields.io/badge/torchaudio-EE4C2C?style=flat)&nbsp;
![HuggingFace Transformers](https://img.shields.io/badge/%F0%9F%A4%97%20Transformers-FFD21E?style=flat)&nbsp;
![HF Spaces](https://img.shields.io/badge/HF%20Spaces-FFD21E?logo=huggingface&logoColor=black&style=flat)

[→ GitHub](https://github.com/22f3003226/DL_Messy_Mashup) &nbsp;·&nbsp; [→ Live Demo](https://huggingface.co/spaces/xytan2022/messy-mashup)

<br>

---

### 📈 WorldQuant India — Quantitative Alpha Research &nbsp;·&nbsp; *All India Rank 17*

Research Consultant role architecting quantitative trading alphas — statistical arbitrage, multi-factor models, and ensemble methods — analyzing 120,000+ financial data fields on the BRAIN platform to surface market inefficiencies with optimized Sharpe ratios. Production-grade ML pipelines in Python for real-time forecasting, feature engineering, and backtesting, validated across bull, bear, and high-volatility regimes.

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white&style=flat)&nbsp;
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white&style=flat)&nbsp;
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white&style=flat)&nbsp;
![Time Series](https://img.shields.io/badge/Time--Series%20Forecasting-6B7280?style=flat)

<br>

---

### 🎬 [Cinema Audience Forecasting](https://github.com/22f3003226/Cinema_Audience_Forecasting_ML)

Regression pipeline for predicting cinema attendance. The more useful work was in the feature engineering — unpacking how day-of-week effects, seasonal patterns, and release cycles compound before the model even runs. Analysis and EDA done in Pandas, NumPy, matplotlib, and seaborn. Achieved ~0.4 $R^2$, which ended up ranking within top 50 in the competition.

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white&style=flat)&nbsp;
![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white&style=flat)&nbsp;
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white&style=flat)&nbsp;
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat)&nbsp;
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat)

[→ GitHub](https://github.com/22f3003226/Cinema_Audience_Forecasting_ML)

<br>

---

## 🛠️ Skills

**ML & AI**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)&nbsp;
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikit-learn&logoColor=white)&nbsp;
![HuggingFace Transformers](https://img.shields.io/badge/%F0%9F%A4%97%20Transformers-FFD21E)&nbsp;
![Keras](https://img.shields.io/badge/Keras-D00000?logo=keras&logoColor=white)&nbsp;
![Claude API](https://img.shields.io/badge/Claude%20API-CC785C?style=flat)&nbsp;
![RAG](https://img.shields.io/badge/RAG-7C3AED?style=flat)

**Web & Backend**

![Python](https://img.shields.io/badge/Python-3670A0?logo=python&logoColor=ffdd54)&nbsp;
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)&nbsp;
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)&nbsp;
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?logo=vue.js&logoColor=white)&nbsp;
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)

**Data & Databases**

![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)&nbsp;
![NumPy](https://img.shields.io/badge/NumPy-013243?logo=numpy&logoColor=white)&nbsp;
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat)&nbsp;
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql&logoColor=white)

**Infrastructure & Deployment**

![Bash](https://img.shields.io/badge/Bash-4EAA25?logo=gnu-bash&logoColor=white)&nbsp;
![AWS](https://img.shields.io/badge/AWS-FF9900?logo=amazon-aws&logoColor=white)&nbsp;
![Git](https://img.shields.io/badge/Git-F05033?logo=git&logoColor=white)&nbsp;
![Docker](https://img.shields.io/badge/Docker-0db7ed?logo=docker&logoColor=white)&nbsp;
![HF Spaces](https://img.shields.io/badge/HF%20Spaces-FFD21E?logo=huggingface&logoColor=black)

<br>

---

## 📊 Contribution Activity

![Contributions](https://img.shields.io/badge/Contributions-Active-brightgreen?style=for-the-badge)&nbsp;
![Repositories](https://img.shields.io/badge/Open%20Source-Multiple-blue?style=for-the-badge)&nbsp;
![Focus](https://img.shields.io/badge/Focus-ML%20%2F%20AI%20Engineering-orange?style=for-the-badge)

Consistent shipping across production ML systems, backend infrastructure, and data pipelines.

# Brandon Behring

**Lead Data Scientist · Causal Inference · Production AI/ML Systems**

---

## What I Build

I build interconnected research infrastructure for causal inference and AI — a RAG system that ingests 478 papers, implementations of 26 causal method families in two languages, an evaluation framework to validate the RAG, and temporal cross-validation libraries to validate the models. Then I deploy it all.

**Core thesis**: Production ML requires statistical rigor at every layer — from the research pipeline that discovers methods, to the implementations that encode them, to the evaluation frameworks that test them.

---

## Ecosystem

```
research-kb ──→ causal_inference_mastery ──→ double_ml_time_series
  (ingest)         (implement)                 (apply)
     │                   │
     ▼                   ▼
  llm-eval          temporalcv
  (validate RAG)    (validate models)
                         │
                         ▼
                    causal_crew
                    (orchestrate)
```

| Repository | What It Does | Scale |
|-----------|-------------|-------|
| **[research-kb](https://github.com/brandonmbehring-dev/research-kb)** | Production RAG pipeline — hybrid vector + graph search | 12 packages · 2,026 tests · 478 sources ingested |
| **[causal_inference_mastery](https://github.com/brandonmbehring-dev/causal_inference_mastery)** | 26 causal method families in Python + Julia | 98K LOC · 8,975 assertions · 184 dev sessions |
| **[double_ml_time_series](https://github.com/brandonmbehring-dev/double_ml_time_series)** | DML textbook + code — Chernozhukov methods, temporal validation | 10 chapters · 796 tests · 180 pages |
| **[llm-eval](https://github.com/brandonmbehring-dev/llm-eval)** | Statistical RAG evaluation — McNemar, bootstrap CIs, drift detection | 142 tests · zero-dep core |
| **[temporalcv](https://github.com/brandonmbehring-dev/temporalcv)** | Temporal cross-validation with gap enforcement | scikit-learn compatible · embargo/purge splits |
| **[causal_crew](https://github.com/brandonmbehring-dev/causal_crew)** | Multi-agent causal analysis via LangGraph + Claude | 4 agents · Streamlit UI · automated method selection |

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Julia](https://img.shields.io/badge/Julia-9558B2?style=flat&logo=julia&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

**Languages**: Python · Julia · LaTeX · SQL
**ML/Stats**: EconML · DoWhy · statsmodels · PyMC · scikit-learn
**Infrastructure**: FastAPI · Docker · PostgreSQL + pgvector · Prometheus · GitHub Actions
**AI**: LangGraph · Claude API · sentence-transformers · Ollama

---

## Current Focus

- Deploying research-kb as a public API with seed corpus
- Temporal cross-validation contributions to scikit-learn
- Causal inference methods for pricing optimization

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brandon-behring/)
[![Upwork](https://img.shields.io/badge/Upwork-6FDA44?style=flat&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/brandonbehring)

# Weldesilassie R. Hailu

**Data & ML Engineer** — I build end-to-end data products: ingestion pipelines, warehouses, RAG systems, and the models that sit on top of them. Most of my recent work is in financial risk and analytics.

📍 Ethiopia · 💼 [LinkedIn](https://www.linkedin.com/in/weldesilassie-redae)

---

## What I work on

- **RAG & LLM systems** — vector stores (FAISS, ChromaDB), semantic chunking, sentence-transformer embeddings, retrieval evaluation, Streamlit interfaces
- **Data engineering** — ELT pipelines, dbt star schemas, Dagster orchestration, PostgreSQL warehouses
- **Financial ML** — credit scoring, fraud detection, insurance risk, time-series forecasting, portfolio optimization
- **Backend** — Python, FastAPI, Django
- **Computer vision** — YOLOv8 for detection and tracking

---

## Selected projects

### 🔍 [Intelligent Complaint Analysis — RAG Chatbot](https://github.com/halafiCodes/Intelligent_Complaint_Analysis_for_Financial_Service-updated)
End-to-end Retrieval-Augmented Generation system over CFPB financial complaint narratives. Chunks and embeds complaint text into a FAISS index, serves retrieval-grounded Q&A through a Streamlit app, and includes a reusable retrieval pipeline with an evaluation runner. Built for CrediTrust Financial to let product teams query thousands of complaints in natural language.

**Stack:** Python · FAISS · sentence-transformers · LangChain text splitters · Streamlit · OpenAI API

### 🗂️ [Complaint Vector Store & Preprocessing](https://github.com/halafiCodes/Consumer_Complaint_Analysis)
The ingestion phase behind the RAG chatbot. EDA over the full CFPB dataset, filtering to four product categories, narrative cleaning, recursive overlapping chunking, and batched embedding into a persistent ChromaDB store with complaint metadata attached.

**Stack:** Python · ChromaDB · sentence-transformers (all-MiniLM-L6-v2) · pandas

### 🏥 [Medical Telegram Data Warehouse](https://github.com/halafiCodes/Medical_telegram_warehouse)
End-to-end ELT product over public Ethiopian medical Telegram channels. Telethon ingestion → PostgreSQL → dbt star schema → YOLOv8 image enrichment → FastAPI analytical API, orchestrated with Dagster and containerized with Docker.

**Stack:** Python · dbt · Dagster · PostgreSQL · FastAPI · YOLOv8 · Docker

### 💳 [Credit Risk Model](https://github.com/halafiCodes/credit-risk-model)
Basel II–oriented credit scoring model. Builds an RFM-based proxy target where no default label exists, then weighs WoE + logistic regression against gradient boosting to trade predictive performance against the interpretability regulators require.

**Stack:** Python · scikit-learn · WoE/IV · gradient boosting

### 🤖 [Project Chimera — Agentic Infrastructure](https://github.com/halafiCodes/Agentic_Infrastructure_26)
Spec-driven foundation for an autonomous agent system: functional and technical SRS, MCP server inventory and tool schemas, and architecture decision records — with implementation deliberately held until the specs are ratified.

**Stack:** Python · MCP · spec-first architecture

### 🎨 [AI Content Generator](https://github.com/halafiCodes/Ai_generation_-pro2)
Multi-provider framework for generating music, video, and images. Plugin architecture lets new providers drop in without touching core code; async-first with Pydantic config, SQLite job tracking, duplicate detection, and cost management behind a CLI.

**Stack:** Python · asyncio · Pydantic · SQLite · Google Lyria/Veo/Imagen · KlingAI

### 🚨 [Fraud Detection](https://github.com/halafiCodes/fraud-detection)
Classification pipeline for fraudulent transactions on heavily imbalanced data.

**Stack:** Python · scikit-learn · imbalanced-learn

---

## Stack

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)](https://www.djangoproject.com/)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io/)

[![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)](https://www.langchain.com/)
[![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)](https://faiss.ai/)
[![ChromaDB](https://img.shields.io/badge/ChromaDB-FFDE57?style=for-the-badge&logo=chromatic&logoColor=black)](https://www.trychroma.com/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/)

[![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)](https://www.getdbt.com/)
[![Dagster](https://img.shields.io/badge/Dagster-4F43DD?style=for-the-badge&logo=dagster&logoColor=white)](https://dagster.io/)
[![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)

[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=for-the-badge&logo=yolo&logoColor=white)](https://docs.ultralytics.com/)
[![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)](https://isocpp.org/)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)

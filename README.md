<div align="center">

# Alejandro Camerlengo

**Data Engineer**

[![Personal Observatory](https://img.shields.io/badge/Observatory-alejandrocamerlengo.com-10b981?style=flat-square&logo=googlechrome&logoColor=white)](https://alejandrocamerlengo.com)
[![QuantLambda Platform](https://img.shields.io/badge/Flagship_Platform-quantlambda.dev-38bdf8?style=flat-square&logo=googlecloud&logoColor=white)](https://quantlambda.dev)
[![Macro Research](https://img.shields.io/badge/Empirical_Research-macro.alejandrocamerlengo.com-f59e0b?style=flat-square)](https://macro.alejandrocamerlengo.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-alejandro--camerlengo-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alejandro-camerlengo/)
[![Email](https://img.shields.io/badge/Gmail-alejandrocamerlengo%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:alejandrocamerlengo@gmail.com)

</div>

---

### Overview

Data Engineer with an academic and professional foundation in **Quantitative Finance, Capital Markets, and Econometrics** (M.Sc. in Finance, Postgraduate Specialization in Data Science, B.Sc. in Economics & Administration).

I design and operate end-to-end production systems spanning **distributed data engineering** (Apache Spark, Kafka, Airflow, dbt, BigQuery), **quantitative portfolio & risk modeling** (CVaR, Hierarchical Risk Parity, Black-Litterman, regime detection), and **multi-agent AI architectures** with deterministic guardrails.

---

### Live Production Ecosystem

Every system and research observatory below is deployed in production on Google Cloud Run and updated via automated pipelines:

| Platform / Observatory | Live URL | Source Repository | Architecture & Scope |
| :--- | :--- | :--- | :--- |
| **Personal Engineering Hub** | [**`alejandrocamerlengo.com`**](https://alejandrocamerlengo.com) | [`personal_website`](https://github.com/ale-camer/personal_website) | 100% keyboard-navigable AI CLI terminal, interactive project hub, empirical macro research, and dual-axis career DAG (`2011–2026`) across 56 languages. |
| **QuantLambda** *(Flagship)* | [**`quantlambda.dev`**](https://quantlambda.dev) | [`market-intelligence-dashboard`](https://github.com/ale-camer/market-intelligence-dashboard) | End-to-end quantitative market intelligence, cross-asset regime telemetry, portfolio optimization (`HRP` / `CVaR`), and a 6-agent investment committee across 13 GCP microservices. |
| **Macroeconomics & Labor Research** | [**`macro.alejandrocamerlengo.com`**](https://macro.alejandrocamerlengo.com) | [`argentina-macro-pipeline`](https://github.com/ale-camer/argentina-macro-pipeline) | Automated monthly pipeline ingesting 7 official Argentine statistical sources (`1961–Present`) with deterministic structural analysis and SARIMAX forecasting. |
| **Spark Learning & Decision Graph** | [**`spark.alejandrocamerlengo.com`**](https://spark.alejandrocamerlengo.com) | [`spark-encyclopedia-pro`](https://github.com/ale-camer/spark-encyclopedia-pro) | Interactive visual guide to Apache Spark 3.5 distributed execution, shuffle/skew bottlenecks, and 30 engineering reference guides. |
| **Global Quality of Life Explorer** | [**`explorer.alejandrocamerlengo.com`**](https://explorer.alejandrocamerlengo.com) | [`global-qol-explorer`](https://github.com/ale-camer/global-qol-explorer) | Historical cross-country observatory comparing 44 socioeconomic, health, education, and purchasing-power indicators across 240 nations. |
| **Geospatial World Map** | [**`worldmap.alejandrocamerlengo.com`**](https://worldmap.alejandrocamerlengo.com) | [`geospacial_projects`](https://github.com/ale-camer/geospacial_projects) | Interactive cartographic engine with live continental telemetry and custom vector map styling. |

---

### Repository Architecture Index — QuantLambda (`P-01` – `P-11`)

Live at [**`quantlambda.dev`**](https://quantlambda.dev) · Frontend UI in [**`market-intelligence-dashboard`**](https://github.com/ale-camer/market-intelligence-dashboard) · Infrastructure orchestrated via [**`portfolio-infra`**](https://github.com/ale-camer/portfolio-infra) (Terraform IaC & GitHub Actions CI/CD).

| Module | Repository | Engineering Layer & Core Stack |
| :--- | :--- | :--- |
| **`UI`** | [**`market-intelligence-dashboard`**](https://github.com/ale-camer/market-intelligence-dashboard) | Unified quantitative terminal, portfolio lab & multi-agent workspace · *React 19, Vite 8, Cloud Run* |
| **`P-01`** | [**`financial-markets-pipeline`**](https://github.com/ale-camer/financial-markets-pipeline) | Daily OHLCV & macro batch ingestion · *Airflow, PostgreSQL, Pydantic, GCS* |
| **`P-02`** | [**`crypto-analytics-platform`**](https://github.com/ale-camer/crypto-analytics-platform) | High-throughput crypto analytics lakehouse · *Polars, BigQuery, Airflow, Terraform* |
| **`P-03`** | [**`real-time-market-events`**](https://github.com/ale-camer/real-time-market-events) | Low-latency streaming event processor · *Kafka, Faust, TimescaleDB, FastAPI* |
| **`P-04`** | [**`financial-news-intelligence-api`**](https://github.com/ale-camer/financial-news-intelligence-api) | Financial news ingestion, FinBERT sentiment & NER · *FastAPI, Transformers, spaCy, MongoDB* |
| **`P-05`** | [**`market-intelligence-hub`**](https://github.com/ale-camer/market-intelligence-hub) | Unified analytical warehouse & serving API · *Kafka, dbt, BigQuery, FastAPI* |
| **`P-06`** | [**`asset-anomaly-detection`**](https://github.com/ale-camer/asset-anomaly-detection) | Cross-asset statistical & ML anomaly detection · *Isolation Forest, Z-Score, FastAPI* |
| **`P-07`** | [**`financial-documents-rag`**](https://github.com/ale-camer/financial-documents-rag) | Hybrid semantic + lexical RAG over SEC filings & macro reports · *Qdrant, MongoDB, FastAPI* |
| **`P-08`** | [**`ai-powered-market-intelligence`**](https://github.com/ale-camer/ai-powered-market-intelligence) | Vector-enriched market intelligence & synthesis pipeline · *pgvector, Airflow, FastAPI* |
| **`P-09`** | [**`financial-research-agent`**](https://github.com/ale-camer/financial-research-agent) | Tool-calling quantitative & fundamental research agent · *LangGraph, FastAPI, GCP* |
| **`P-10`** | [**`autonomous-trading-analyst`**](https://github.com/ale-camer/autonomous-trading-analyst) | ReAct trading analyst with deterministic risk guardrails & episodic memory · *Python, FastAPI* |
| **`P-11`** | [**`multi-agent-market-intelligence`**](https://github.com/ale-camer/multi-agent-market-intelligence) | Multi-agent investment committee orchestrator with consensus & risk veto · *FastAPI, Cloud Run* |
| **`IaC`** | [**`portfolio-infra`**](https://github.com/ale-camer/portfolio-infra) | Centralized GCP Terraform infrastructure, serverless scheduling & health keepalives |

---

### Core Technical Stack

- **Data Engineering & Streaming:** Python, SQL, Apache Spark (PySpark), Apache Kafka, Apache Airflow, dbt, Polars, DuckDB
- **Cloud & Infrastructure:** Google Cloud Platform (BigQuery, Cloud Run, GCS, Cloud Scheduler, Artifact Registry), AWS, Docker, Terraform, GitHub Actions
- **AI & Quantitative Systems:** Multi-Agent Orchestration (LangGraph / ReAct), Hybrid RAG (`pgvector`, Qdrant), Time-Series Econometrics (SARIMAX, GARCH), Portfolio Optimization (`CVaR`, `HRP`), FastAPI, React

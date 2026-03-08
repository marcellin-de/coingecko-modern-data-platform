# Coingecko data platform

An enterprise-grade end-to-end data platform ingesting cryptocurrency market data from CoinGecko, storing it in ClickHouse, transforming it with dbt, validating it with Great Expectations, enriching it using Hugging Face models, and orchestrating everything through Dagster asset-based pipelines.

The platform follows Modern Data Engineering best practices (2026): asset orchestration, incremental ingestion, declarative pipelines, observability-first architecture, CI/CD-native workflows, and reproducible Docker environments powered by uv.

---
Stack:
- DLT ingestion
- Dagster orchestration (SDA)
- ClickHouse warehouse
- dbt transformations
- Great Expectations data quality
- Hugging Face AI enrichment
- Metabase analytics
- Dockerized infrastructure
- uv Python environments
- CI/CD validation pipelines

---

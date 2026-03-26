# Data Engineering Projects

A collection of hands-on data engineering projects focused on building scalable, production-style data systems.

---

## 🚀 What This Repo Covers

This repository demonstrates core data engineering concepts through practical implementations:

- ETL / ELT pipeline design
- Data lakehouse architecture (Bronze → Silver → Gold)
- Schema evolution & data contracts
- Spark & PySpark transformations
- Databricks-style workflows
- Data validation and ingestion patterns

---

## 🧠 Engineering Focus

The goal of this repo is not just code — but **real-world patterns used in production systems**:

- Building reusable ingestion pipelines
- Handling schema drift safely
- Structuring data layers correctly
- Writing scalable transformation logic

---

## 📁 Projects

### ⭐ Contract-Driven Lakehouse Framework (Flagship)

A modular, contract-driven data platform inspired by modern lakehouse architectures.

**Overview:**
This project implements a reusable data pipeline framework where datasets are defined via contracts (schemas + rules), enabling scalable and consistent data ingestion and transformation.

**Key Features:**
- Source → Landing → Bronze → Silver → Gold pipeline design  
- Contract-based schema enforcement  
- Schema evolution handling (type changes, new columns)  
- Data validation and rejected records handling  
- Partitioning and optimisation strategies  

**Tech Stack:**
- PySpark  
- Delta Lake  
- Python  

---

### 🔹 API Ingestion Framework

Reusable ingestion system for extracting and loading data from external APIs into a structured data lake.

**Overview:**
Designed to simulate real-world ingestion scenarios such as pulling data from SaaS platforms or public APIs.

**Key Features:**
- REST API ingestion with pagination support  
- Incremental loading (date-based / cursor-based)  
- Retry logic and rate limit handling  
- Schema mapping and normalisation  
- Config-driven ingestion pipelines  

**Tech Stack:**
- Python  
- Requests  
- PySpark  

---

### 🔹 Data Observability & Validation System

A monitoring and validation layer for ensuring data pipeline reliability and quality.

**Overview:**
Provides visibility into pipeline runs and detects data quality issues early in the pipeline lifecycle.

**Key Features:**
- Row count and null value checks  
- Schema drift detection  
- Data quality rules engine  
- Logging and pipeline run tracking  
- Error reporting and alert simulation  

**Tech Stack:**
- Python  
- PySpark  
- Logging frameworks  

---

## 🎯 Purpose

This repository is part of my portfolio to demonstrate **data engineering capabilities in real-world scenarios**, not just isolated scripts.

---

More projects will be added as I build production-ready patterns.

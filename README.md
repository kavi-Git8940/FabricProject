# 🚀 Microsoft Fabric Learning Projects

> A hands-on repository documenting my learning journey and experiments with Microsoft Fabric — including Lakehouse, Data Pipelines, Notebooks, and Power BI.

---

## 📂 Table of Contents

- [Overview](#overview)
- [Learning Goals](#learning-goals)
- [Fabric Components Used](#fabric-components-used)
- [Setup](#setup)
- [Project Structure](#project-structure)
- [Screenshots](#screenshots)
- [Resources](#resources)
- [License](#license)

---

## 📖 Overview

This repository includes a collection of self-paced projects and labs using Microsoft Fabric. It covers:

- Building a Lakehouse and managing Delta Tables
- Creating and executing Notebooks (PySpark, SQL)
- Designing Data Pipelines for ETL/ELT workflows
- Developing Power BI reports connected to Fabric datasets
- Using OneLake as a unified storage layer

---

## 🎯 Learning Goals

- Understand the core building blocks of Microsoft Fabric
- Implement data ingestion, transformation, and visualization pipelines
- Integrate Power BI with Lakehouse and Warehouse
- Store and version code for reproducibility and collaboration

---

## 🧱 Fabric Components Used

| Component       | Description                                      |
|-----------------|--------------------------------------------------|
| Lakehouse       | Centralized Delta Lake storage                   |
| Data Pipelines  | Orchestrate ETL/ELT flows                        |
| Notebooks       | Run Spark-based data transformations             |
| Power BI        | Build visuals and dashboards                     |
| OneLake         | Unified storage for all Fabric workloads         |

---

## 🛠️ Setup

> This repo contains project assets only. Execution happens in the Fabric UI.

1. Sign in to [https://app.fabric.microsoft.com](https://app.fabric.microsoft.com)
2. Create or open a workspace
3. Import relevant files (e.g., notebooks, sample data)
4. Assign Fabric capacity (trial or F2 SKU) if needed
5. Run and test the workflows following the examples in this repo

---

## 📁 Project Structure

```bash
fabric-learning/
│
├── notebooks/           # Fabric Notebooks (.ipynb or exported .json)
├── pipelines/           # Pipeline configs or screenshots
├── powerbi/             # PBIX files or embedded visuals
├── lakehouse/           # Sample data or Lakehouse schema
├── screenshots/         # UI snapshots for documentation
├── notes.md             # Tips, issues, and learning notes
└── README.md

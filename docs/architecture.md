# Architecture Design

## Objective

Design an end-to-end People Analytics platform that integrates HR data sources, processes them in Databricks, and enables executive analytics through Tableau and a GenAI Advisor.

## Data Flow

```text
Raw HR Data
    ↓
Databricks Raw Layer
    ↓
Staging Layer
    ↓
Business Layer
    ↓
People Analytics Mart
    ↓
Tableau Dashboard + GenAI Advisor
```
---

## Layers
- Raw Layer:
Stores original HR datasets without transformations.
- Staging Layer:
Standardizes column names, data types, and business entities.
- Business Layer:
Applies KPI logic and workforce analytics rules.
- Mart Layer:
Creates final curated table for Tableau and GenAI consumption.

# People Analytics Intelligence Platform

## Overview

The People Analytics Intelligence Platform is an end-to-end analytics solution designed to centralize Human Resources data, generate actionable workforce insights, and support executive decision-making through dashboards and Generative AI.

The platform integrates multiple HR domains including employee information, attendance, performance evaluations, and attrition indicators into a single source of truth.

---

## Business Problem

Organizations often struggle with fragmented HR data distributed across multiple systems, making it difficult to:

- Monitor workforce health
- Identify attrition risks
- Analyze absenteeism trends
- Measure employee performance
- Support strategic talent decisions

This project addresses these challenges through a modern cloud-based analytics architecture.

---

## Objectives

- Build a centralized People Analytics data model
- Create executive-level HR dashboards
- Develop workforce KPIs and metrics
- Implement predictive workforce analytics
- Build a GenAI Workforce Advisor capable of answering business questions

---

## Architecture

```text
HR Datasets
    ↓
Databricks (ETL & Data Processing)
    ↓
Staging Layer
    ↓
Business Layer
    ↓
People Analytics Mart
    ↓
 ┌─────────────┬─────────────┐
 │             │             │
 ▼             ▼             ▼
Tableau    Executive KPIs   GenAI Advisor
```

## Technology Stack

- Databricks
- Delta Tables
- PySpark
- SQL
- Tableau
- Python
- OpenAI API
- GitHub

---

## Planned KPIs

### Workforce

- Headcount
- Active Employees
- Employee Distribution

### Talent Retention

- Attrition Rate
- Turnover Risk Score
- High-Risk Employees

### Attendance

- Absenteeism Rate
- Overtime Hours
- Attendance Compliance

### Performance

- Average Performance Score
- High Performers
- Performance Distribution

---

## Project Roadmap

### Phase 1
- Data acquisition
- Data exploration

### Phase 2
- ETL development
- Data modeling

### Phase 3
- KPI generation
- Tableau dashboards

### Phase 4
- GenAI Workforce Advisor

### Phase 5
- Predictive analytics

---

## Author

Mabel Álvarez

Data Analytics | Business Intelligence | AI & Decision Intelligence

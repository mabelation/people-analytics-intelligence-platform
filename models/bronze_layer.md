# Bronze Layer

## Objective

The Bronze Layer preserves the original source data with minimal transformation.

Its purpose is to maintain traceability, reproducibility and a clear connection between the analytical platform and the original HR datasets.

---

## Source Tables

### extended_employee_performance_and_productivity_data

Primary workforce dataset used for performance, workload, satisfaction, promotion and resignation analysis.

### mfg_employees_4

Employee dataset used for organizational, business unit and absenteeism context.

### wa_fn_use_c_hr_employee_attrition

IBM HR Attrition dataset used for attrition modeling, feature importance and explainable AI analysis.

---

## Design Principles

- Preserve original columns
- Avoid business logic in this layer
- Use this layer as the source of truth for raw ingestion
- Enable auditability and reproducibility

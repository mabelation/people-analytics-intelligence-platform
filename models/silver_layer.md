# Silver Layer

## Objective

The Silver Layer standardizes, cleans and prepares workforce data for analytical modeling.

This layer transforms raw source tables into consistent entities that can be reused across dashboards, machine learning models and AI applications.

---

## Planned Tables

### stg_workforce_performance

Standardized employee performance and productivity information.

Main fields:
- employee_id
- department
- gender
- age
- job_title
- years_at_company
- performance_score
- monthly_salary
- work_hours_per_week
- projects_handled
- overtime_hours
- sick_days
- remote_work_frequency
- training_hours
- promotions
- satisfaction_score
- resigned_flag

---

### stg_employee_absenteeism

Standardized employee absenteeism and organizational context.

Main fields:
- employee_number
- gender
- city
- job_title
- department
- store_location
- division
- age
- length_service
- absent_hours
- business_unit

---

### stg_attrition_modeling

Standardized IBM Attrition dataset for predictive modeling.

Main fields:
- employee_number
- age
- attrition_flag
- department
- job_role
- monthly_income
- overtime_flag
- job_satisfaction
- work_life_balance
- performance_rating
- years_at_company
- years_since_last_promotion
- years_with_current_manager

---

## Design Principles

- Standardize column names
- Convert categorical flags into analytical formats
- Preserve modeling variables
- Separate workforce analytics from attrition modeling when datasets are not directly joinable

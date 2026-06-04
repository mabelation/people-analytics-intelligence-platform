# Data Dictionary

## dim_employee

| Field | Type | Description |
|---|---|---|
| employee_id | integer | Unique employee identifier |
| age | integer | Employee age |
| gender | string | Employee gender |
| department | string | Business department |
| job_role | string | Employee role |
| monthly_income | double | Monthly salary |
| hire_date | date | Employee hire date |
| attrition_flag | integer | 1 if employee left, 0 otherwise |

## fact_attendance

| Field | Type | Description |
|---|---|---|
| employee_id | integer | Unique employee identifier |
| absent_hours | double | Total absent hours |
| overtime_hours | double | Overtime hours |
| absenteeism_rate | double | Absence indicator |

## fact_performance

| Field | Type | Description |
|---|---|---|
| employee_id | integer | Unique employee identifier |
| performance_score | double | Employee performance score |
| job_satisfaction | integer | Job satisfaction level |
| work_life_balance | integer | Work-life balance level |

## mart_people_analytics

| Field | Type | Description |
|---|---|---|
| employee_id | integer | Unique employee identifier |
| department | string | Business department |
| job_role | string | Employee role |
| attrition_flag | integer | Employee attrition status |
| attrition_risk_score | double | Estimated attrition risk |
| absenteeism_rate | double | Absence rate |
| performance_score | double | Performance score |
| workforce_health_status | string | Overall employee risk category |

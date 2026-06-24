# Business Metrics

## Workforce Intelligence Framework

The objective of this framework is to measure workforce performance, wellbeing, retention risk and employee development through data-driven indicators.

Initial scores will be defined using business rules and subsequently refined using Machine Learning explainability techniques such as Random Forest Feature Importance and SHAP analysis.

---

## Performance Index

### Objective

Measure employee productivity and contribution.

### Candidate Variables

* Performance Score
* Projects Handled
* Training Hours
* Promotions

---

## Burnout Risk Score

### Objective

Identify employees potentially exposed to excessive workload or declining wellbeing.

### Candidate Variables

* Overtime Hours
* Work Hours Per Week
* Sick Days
* Employee Satisfaction Score
* Work Life Balance

### Methodology

Initial business-rule based score.

Future versions will use Machine Learning and explainability models to identify the most important burnout drivers.

---

## Attrition Intelligence

The attrition module is based on a supervised Machine Learning framework using the IBM HR Analytics dataset.

Preliminary exploratory analysis identified:

- Lower Job Satisfaction
- Lower Work-Life Balance
- Lower Monthly Income

as potential attrition drivers.

These hypotheses will be validated through Random Forest Feature Importance and SHAP explainability analysis.

---

## Promotion Readiness Score

### Objective

Identify employees with strong promotion potential.

### Candidate Variables

* Performance Score
* Training Hours
* Projects Handled
* Years At Company
* Promotions

### Methodology

Initial business-rule framework.

Future versions may incorporate supervised learning models and talent segmentation techniques.

---

## Explainable AI Layer

The platform will incorporate explainability techniques including:

### Random Forest Feature Importance

Used to identify the most influential workforce factors.

### SHAP (SHapley Additive Explanations)

Used to explain individual employee predictions and provide transparent business recommendations.

---

## GenAI Workforce Advisor

The AI Advisor will leverage:

* Workforce KPIs
* Attrition predictions
* Burnout predictions
* SHAP explanations

Example questions:

* Which department has the highest attrition risk?
* Which employees should be considered for promotion?
* Which teams show signs of burnout?
* What actions should HR prioritize next quarter?


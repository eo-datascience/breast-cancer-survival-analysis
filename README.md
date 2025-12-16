# Breast Cancer Survival Analysis

## Project Overview

This project applies survival analysis techniques to investigate clinical factors influencing breast cancer patient outcomes. Using time-to-event data with censoring, I estimated survival probabilities and identified significant predictors of mortality.

The analysis focuses on interpretability and clinical relevance, not just model performance.



## Dataset
 • Source: Public breast cancer dataset (Kaggle)
 
 • Observations: 686 patients
 
 • Outcome: Time to recurrence or death (censored survival data)

### Key Variables
- Age
- Menopausal status
- Tumor size
- Tumor grade
- Estrogen receptor (ER)
- Progesterone receptor (PGR)
- Hormone therapy
- Recurrence-free survival time
- Event status (censored vs event)


## Methodology

1. Kaplan–Meier Survival Estimation
- Estimated overall survival probability over time
- Visualized confidence intervals
- Computed median survival time

2. Log-Rank Tests
- Compared survival curves across clinical subgroups
- Identified variables with statistically different survival patterns

3. Cox Proportional Hazards Regression
- Modeled the effect of multiple covariates on hazard
- Reported hazard ratios with 95% confidence intervals
- Assessed proportional hazards assumptions using Schoenfeld residuals


## Key Findings
- Tumor size significantly increases risk of death
- Tumor grade is strongly associated with worse survival
- Hormone therapy is protective and reduces mortality risk
- Progesterone receptor (PGR) shows a statistically significant association
- Age, menopausal status, and estrogen receptor (ER) were not significant predictors

The Kaplan–Meier curve shows survival probability declining from 1.0 to approximately 0.35, with the median survival time clearly reached.


## Model Diagnostics
- Most variables satisfied the proportional hazards assumption
- Tumor grade showed mild deviation, but not enough to invalidate the model
- Visual diagnostics showed no severe time-dependent effects


## Tools & Technologies
- Python
- pandas, numpy
- lifelines
- matplotlib


## Why This Project Matters
Survival analysis is widely used in healthcare, clinical research, and public health.
This project demonstrates:
- Handling censored time-to-event data
- Interpreting survival curves and hazard ratios
- Applying statistically sound models with real-world relevance



## Author

Emmanuel Olusolade

Data Scientist

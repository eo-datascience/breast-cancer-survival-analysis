🧬 Breast Cancer Survival Analysis

📌 Overview

This project applies survival analysis techniques to study factors influencing breast cancer patient survival. Kaplan–Meier estimation and Cox Proportional Hazards regression were used to quantify survival probabilities and identify significant predictors of risk.


📊 Dataset

 • Source: Public breast cancer dataset (Kaggle)
 
 • Observations: 685 patients
 
 • Outcome: Time to event (recurrence or death)
 
 • Censoring included


🛠 Methods

 • Kaplan–Meier survival estimation
 
 • Log-rank tests for group comparison
 
 • Cox Proportional Hazards regression
 
 • Proportional hazards assumption checks
 
 • Residual diagnostics


🔑 Key Findings

 • Tumor size and tumor grade significantly increase hazard
 
 • Hormone therapy significantly reduces risk
 
 • Progesterone receptor levels are significant predictors
 
 • Age, menopausal status, and estrogen receptor were not significant


📈 Visualizations

 • Overall Kaplan–Meier survival curve
 
 • Survival curves stratified by tumor grade
 
 • Schoenfeld residual plots


📦 Tools

 • Python
 
 • pandas, numpy
 
 • lifelines
 
 • matplotlib


📌 Conclusion


This project demonstrates practical application of survival analysis techniques in healthcare data science and highlights clinically meaningful predictors of breast cancer outcomes.


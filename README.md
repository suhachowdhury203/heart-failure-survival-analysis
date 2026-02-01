# heart-failure-survival-analysis
Survival Analysis on UCI Heart Failure Clinical Records Dataset

**Project Overview**

This project applies survival analysis methods to evaluate time-to-mortality outcomes in heart failure patients using clinical data from the UCI Heart Failure Clinical Records dataset. The goal of this analysis was to identify clinical variables associated with mortality risk over time and to demonstrate practical application of survival modeling techniques commonly used in clinical research.

**Methods**

*  The following survival analysis approaches were implemented:
*  Kaplan–Meier survival estimation to evaluate overall survival probability
*  Kaplan–Meier stratified by ejection fraction groups
*  Log-rank test to statistically compare survival curves
*  Cox Proportional Hazards modeling to evaluate multivariable risk associations
*  Proportional hazards assumption testing using Schoenfeld residual-based methods
*  Sensitivity analysis including feature scaling and penalized Cox regression

**Key Findings**

*  Survival differed significantly between ejection fraction groups (log-rank p < 0.005)
*  Increased mortality risk was associated with:
*  Older age
*  Anaemia
*  High blood pressure
*  Higher serum creatinine levels
*  Higher ejection fraction was protective
*  Model discrimination was good (Concordance ≈ 0.74)
*  Model refinement approaches did not meaningfully improve performance, suggesting baseline model stability
  
**Limitations**
  
* Small sample size
* Limited clinical variable availability
* Mild proportional hazards deviation observed for ejection fraction
* No external validation dataset available
  
**Dataset** -- UCI Machine Learning Repository – Heart Failure Clinical Records Dataset

**Future Work**
* Larger clinical datasets
* Additional clinical and treatment variables
* Time-varying survival modeling approaches 

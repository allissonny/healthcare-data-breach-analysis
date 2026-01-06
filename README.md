# Do Business Associates Affect Healthcare Data Breach Impact?

This project analyzes U.S. healthcare data breach records to examine whether breaches involving business associates affect more individuals than breaches without third-party involvement.

---

## Research Question
Do breaches involving a business associate tend to affect more individuals than breaches without business associate involvement?

---

## Methods
- Data cleaning and exploratory data analysis  
- Distribution analysis using log-scaled visualizations  
- Permutation testing on median breach size  
- Bootstrap confidence intervals for effect size  
- Log-linear regression controlling for breach type and breach location  

---

## Key Findings
- Breaches involving business associates have a higher median number of individuals affected.  
- The observed median difference is approximately **1,184 individuals**.  
- A permutation test shows this difference is statistically significant (**p < 0.001**).  
- Regression results indicate breaches with business associate involvement affect about **32% more individuals**, even after controlling for breach characteristics.

---

## Files
- `EvanichDSC530FinalProject_Git.ipynb` — main analysis notebook  
- `cleaned_data.csv` — dataset  

---

## Tools
Python · pandas · NumPy · Matplotlib · statsmodels

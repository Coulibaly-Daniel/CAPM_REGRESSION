# 📊 CAPM & Fama-French Regression Analysis

## Project Overview
This project analyzes stock excess returns using two fundamental asset pricing models:

- Capital Asset Pricing Model (CAPM)
- Fama-French 3-Factor Model

The analysis is conducted using monthly data over a long-term period (1980–2024).

---

## 📈 Models

### CAPM
The CAPM explains asset returns based on market risk:

R_i - R_f = α + β (R_m - R_f) + ε

### Fama-French 3-Factor Model
This model extends CAPM by including size and value factors:

R_i - R_f = α + β (R_m - R_f) + s·SMB + h·HML + ε

---

## Key Results

### CAPM
- R² ≈ 0.15 → Limited explanatory power
- Market beta (β) is highly significant
- Alpha is not statistically significant

### Fama-French Model
- R² improves to ≈ 0.19
- SMB factor is significant
- HML factor is not significant
- Alpha remains insignificant

---

## Interpretation

- The CAPM explains part of the variation in returns but is incomplete.
- The Fama-French model improves the fit, confirming that additional risk factors matter.
- The insignificance of alpha suggests no strong abnormal returns, consistent with market efficiency.

---

## 📉 Visualization

The project includes a regression plot showing the relationship between asset excess returns and market excess returns, along with the fitted CAPM line.

---

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Statsmodels
- Matplotlib

---

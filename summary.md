# Loan Default Prediction Project Summary

## 🔍 Project Overview
This project uses XGBoost to predict loan default using a high-dimensional financial dataset. SHAP is applied for global and local interpretability.

## ⚙️ Methodology
- Feature engineering: handled missing values and encoded categorical variables
- Model: trained XGBoost with class imbalance tuning
- Evaluation: optimized for AUC and Recall
- Interpretability: used SHAP summary and force plots

## 📊 Findings
- Top 5 global features: income, loan_amount, credit_score, employment_status, previous_defaults
- Correct prediction: driven by low income and poor credit score
- Misclassified case: underweighted previous defaults despite moderate income

## 🧭 Strategic Implications
Credit policy should emphasize income-to-loan ratio, credit history, and employment length. SHAP revealed interactions that suggest refining risk thresholds.

## ✅ Deliverables
- Python code: model, SHAP analysis
- SHAP plots: summary + force plots
- Evaluation metrics: AUC and Recall
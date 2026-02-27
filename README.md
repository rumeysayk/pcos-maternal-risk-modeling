# PCOS & Maternal Clinical Risk Modeling

Machine learning project for predicting PCOS and maternal risk factors using clinical, hormonal, and demographic features.

---

## Project Overview

This project develops robust machine learning pipelines for:

- PCOS risk prediction
- Maternal health modeling
- Clinical feature importance analysis
- Model interpretability using SHAP
- Hyperparameter tuning and validation

The objective is to build interpretable and generalizable clinical prediction models.

---

## Models Implemented

- Logistic Regression (Baseline)
- Random Forest
- Hyperparameter-tuned Logistic Regression
- SHAP Explainability Analysis
- Calibration Analysis

---

## Key Results (PCOS Model)

- Logistic Regression ROC-AUC ≈ 0.95
- Random Forest ROC-AUC ≈ 0.94
- Tuned Logistic Regression ROC-AUC ≈ 0.90

SHAP analysis identified clinically meaningful predictors:

- Follicle count
- Hair growth
- Skin darkening
- Weight gain
- Hormonal indicators

---

## Project Structure

pcos-maternal-clinical-modeling/
│
├── data/ # Raw and processed datasets
├── notebooks/ # Modeling notebooks
├── models/ # Saved trained models
├── reports/ # Analysis reports and figures
├── README.md
└── requirements.txt

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- SHAP
- Matplotlib / Seaborn

---

## Future Work

- Integrated maternal & PCOS feature analysis
- External validation
- Deployment-ready API
- Clinical research narrative

---

## Authors

Rümeysa Yavuzkanat - Computer Engineering  
Emine Sena Top - Computer Engineering

Machine Learning & Clinical Data Modeling

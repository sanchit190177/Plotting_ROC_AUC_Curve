# ROC-AUC Curve Visualization — Logistic Regression

## Overview
This project demonstrates how to evaluate a binary classification model
using ROC-AUC curve analysis. A Logistic Regression model with
ElasticNet regularization is trained to predict obesity based on body
weight, with detailed threshold-based confusion matrix analysis.

## Concepts Covered
- Binary Classification using Logistic Regression
- ElasticNet Regularization (L1 + L2 combined)
- Confusion Matrix — TP, TN, FP, FN
- True Positive Rate (Sensitivity) & False Positive Rate
- Multi-threshold decision boundary analysis
- ROC Curve plotting & AUC Score

## Tech Stack
- Python
- NumPy
- Scikit-learn
- Matplotlib

## How to Run
```bash
pip install numpy scikit-learn matplotlib
jupyter notebook Plot_AUC_ROC_Curve.ipynb
```

## Dataset
Small synthetic dataset — body weights (30–90 kg) with binary
obesity labels (0 = Not Obese, 1 = Obese).

## Key Results
- Model evaluated at 3 thresholds: 0.40, 0.50, 0.61
- ROC-AUC Score computed using sklearn's roc_auc_score
- ROC Curve plotted against random guess baseline (dotted line)

## Project Structure

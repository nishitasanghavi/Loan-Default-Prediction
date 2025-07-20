# Loan Default Prediction

This project simulates a real-world Business Analyst task for a lending platform predicting loan defaults using applicant data and extracting insights to support risk-based lending decisions.

## Problem Statement

Given historical loan data, predict whether a new applicant is likely to default or not. Also, identify key drivers behind loan approval and risk of default.

## Key Highlights

- Built and compared three models: Logistic Regression, Decision Tree, and Random Forest
- Best model: Random Forest with 0.77 AUC
- Credit History had the strongest impact on approvals (correlation = 0.54)
- Performed EDA and visualized feature correlations
- Model Evaluation: Confusion matrix, ROC curves, F1 score

## Tech Stack

- Python, Pandas, NumPy
- Scikit-learn
- Seaborn, Matplotlib
- Jupyter Notebook

## Files

| File | Description |
|------|-------------|
| `Loan Default Prediction using Logistic Regression.ipynb` | Full code notebook including preprocessing, training, evaluation |
| `feature_correlation.png` | Correlation heatmap (EDA insight) |
| `roc_comparison.png` | ROC comparison of all models |
| `loan_data.csv` | Dataset from Kaggle: [Kaggle Link](https://www.kaggle.com/datasets/ninzaami/loan-predication) |

## Insights

- Credit history is the strongest predictor of loan approval – more than income or loan amount
- Applicant income showed low correlation with loan status
- Logistic Regression provided transparency; Random Forest outperformed in predictive power

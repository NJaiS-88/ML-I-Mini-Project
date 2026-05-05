# ML-I-Mini-Project
This repository contains a complete machine learning pipeline to predict student performance using academic and personal factors. The project demonstrates end‑to‑end workflow: from problem definition and data preprocessing to model training, evaluation, feature importance analysis, and deployment via model serialization.

# Problem Statement
The goal is to estimate student outcomes based on features such as previous scores, hours studied, attendance, motivation level, tutoring sessions, and access to resources. By identifying the most influential predictors, the model supports better educational planning and student support strategies.

# Repository Contents
1) Dataset: Raw student performance data with multiple academic and lifestyle features.
2) Notebook (.ipynb): End‑to‑end pipeline including preprocessing, model training, evaluation, visualization, and final model selection.
3) Pickle File (.pkl): Serialized trained pipeline for direct reuse and prediction without retraining.

# Methodology
1) Data Preprocessing – Cleaning and preparing dataset for modeling.
2) Model Training – Linear Regression, Ridge, Lasso, and Linear SVM compared.
3) Evaluation – Metrics: R², MAE, RMSE; residual and prediction plots.
4) Feature Importance – Lasso highlights key predictors (Previous Scores, Hours Studied, Motivation Level).
5) Model Selection – Lasso chosen for accuracy and interpretability.
6) Serialization – Final pipeline retrained on full dataset and saved using Pickle.
7) Deployment – Demonstration of loading pickle file and predicting new outcomes.

# Results
Lasso Regression achieved strong generalization (~0.79 R²).
Residuals showed no major bias.
Feature selection improved interpretability by shrinking irrelevant coefficients to zero.

# Conclusion
This project provides a reproducible and deployment‑ready solution for predicting student performance. It highlights the value of regularized linear models in balancing accuracy and interpretability, making it a practical example of applying machine learning to educational analytics.

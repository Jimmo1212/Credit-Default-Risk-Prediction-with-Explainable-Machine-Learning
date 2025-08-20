# Credit-Default-Risk-Prediction-with-Explainable-Machine-Learning
This repository contains the research paper and implementation code for “Credit Default Risk Prediction with Explainable Machine Learning: Integrating Socioeconomic Interaction Effects”. The project evaluates both traditional and modern machine learning methods for predicting credit default risk, with a focus on model interpretability and socioeconomic interaction effects.
## Project Overview
Accurately predicting credit default risk is critical for lenders, regulators, and policymakers.
This project benchmarks six supervised learning algorithms on a real-world loan dataset of 28,638 applicants:

#·Logistic Regression

Decision Tree

Random Forest

Gradient Boosting

AdaBoost

K-Nearest Neighbors

Key contributions:

Performance Comparison: Ensemble-based models (Random Forest, Gradient Boosting) outperform Logistic Regression in accuracy, recall, and AUC-ROC
.

Explainability: SHapley Additive exPlanations (SHAP) are applied to reveal the most influential risk drivers such as loan-to-income ratio, interest rate, income, and housing tenure.

Socioeconomic Insights: Interaction effects between renter status and loan purpose (e.g., debt consolidation, home improvement) emerge as critical differentiators of default risk
.

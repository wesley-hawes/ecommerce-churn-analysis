
# Ecommerce Customer Churn Analysis

## Overview
This project analyzes customer churn behavior for an ecommerce platform and
builds predictive models to identify customers at risk of churn. The workflow
includes exploratory data analysis, preprocessing with scikit-learn pipelines,
model evaluation, threshold tuning, and business recommendations.

## Approach
- Exploratory data analysis to identify behavioral and service-related churn drivers
- Feature engineering and preprocessing using scikit-learn pipelines
- Logistic regression baseline and gradient boosted tree models
- Cross-validation, threshold analysis, and model interpretation

## Key Results
- Gradient boosted tree achieved stronger precision–recall tradeoffs at comparable
  recall levels (ROC-AUC ≈ 0.94)
- Key churn drivers include tenure, inactivity, complaints, payment method,
  and product category

## Repository Structure
- `notebooks/01_eda_churn_analysis.ipynb`: Data exploration and insights
- `notebooks/02_modeling_churn_analysis.ipynb`: Modeling, evaluation, and recommendations

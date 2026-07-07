# Automotive-Price-Prediction-Market-Intelligence-System

## Overview
Built an end-to-end machine learning pipeline to predict European car prices using regression models.

## Technologies
Python, Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn

## Dataset
European Cars Dataset from Kaggle:
(https://www.kaggle.com/datasets/eswarpanchakarla/european-cars-dataset)

## Workflow
- Importing libraries and loading the dataset
- Data cleaning and preprocessing:
       Duplicate and missing value checks,
       Outlier handling using IQR (Interquartile Range method))
- Feature engineering:
       Domain-based feature creation,
       One-hot encoding
- Model building and training
- Model comparison
- Visualization

## Models Used
- Linear Regression
- Lasso Regression
- Ridge Regression
- Random Forest
- XGBoost

## Evaluation Metrics
- Mean Squared Error (MSE)
- R² Score

## Results
XGBoost achieved the best performance among the tested models.

## Key Insights
Feature analysis showed that vehicle performance, efficiency, and safety-related features influence car pricing.

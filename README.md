This repository contains a single Python notebook used for the master's thesis:
"Exploring Machine Learning Techniques for Credit Risk: Feature Selection, Multiple Classifier Systems, and Survival Analysis in Probability of Default Prediction".

The thesis fulfills the requirements for the Master of Data Science and Society at Tilburg University.

Notebook Overview
The notebook is divided into the following sections:

1. EDA & Data Cleaning & Feature Engineering
   
   1.1 Exploratory Data Analysis (EDA) before splitting into training/testing
   
   1.2 Data preprocessing and feature engineering

2. Splitting Dataset: Train/test split

3. Rolling-Window Cross-Validation Split

4. Pipeline

5. Model Training with All Features (70): Train four models

6. Feature Selection
   
   6.1 Business judgment
   
   6.2 Information value analysis
   
   6.3 Correlation analysis

7. Model Training with Selected Features (25)
    Compare performance between 70 and 25 features
    Includes hyperparameter tuning, test performance, feature importance, and SHAP analysis (LightGBM)
   
8. Multiple Classifier Systems (Weighted Majority Voting)

9. Macro Analysis: General model performance evaluation

10. Micro Analysis: Error analysis

11. Survival Machine Learning Models
    
    11.1 Random Survival Forest
    
    11.2 Gradient Boosting Survival Analysis
    

# Differentiated Thyroid Cancer Recurrence: EDA and Recurrence Prediction

This repository focuses on exploring and predicting recurrence in differentiated thyroid cancer using machine learning models. The project includes extensive exploratory data analysis (EDA) and the development of optimized models to achieve high prediction accuracy. 

## Dataset

The dataset used in this project is sourced from the UCI Machine Learning Repository:  
[https://archive.ics.uci.edu/dataset/915/differentiated+thyroid+cancer+recurrence](https://archive.ics.uci.edu/dataset/915/differentiated+thyroid+cancer+recurrence)

### Dataset Overview:
The dataset contains clinical and demographic features related to patients diagnosed with differentiated thyroid cancer. It includes the following key details:
- Patient characteristics: Age, gender, and other demographic information.
- Clinical features: Tumor size, type, and histological findings.
- Treatment and follow-up data: Surgery type, therapy details, and recurrence status.

For further details, refer to the [dataset description](https://archive.ics.uci.edu/dataset/915/differentiated+thyroid+cancer+recurrence).

## Project Overview

1. **Exploratory Data Analysis (EDA):**
   - Data cleaning, handling missing values, and feature engineering.
   - Statistical and graphical analysis of key features.
   - Identification of significant factors contributing to recurrence.

2. **Machine Learning Models:**
   - Development of supervised learning models for recurrence prediction.
   - Hyperparameter optimization using **Optuna** to enhance model performance.
   - Evaluation using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

3. **Results:**
   - The best-performing model achieved an **accuracy of 97.2%** on the test set.
   - Feature importance analysis revealed the most influential predictors of recurrence.

## Tools and Technologies

- **Programming Language:** Python
- **Frameworks and Libraries:** 
  - Data analysis: Pandas, NumPy, Matplotlib, Seaborn
  - Machine learning: Scikit-learn
  - Hyperparameter optimization: Optuna
- **Development Environment:** Jupyter Notebook

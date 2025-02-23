# Customer_Churn_Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-✔-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-✔-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-✔-blue)

## Overview
This project focuses on predicting customer churn using machine learning. Businesses use churn prediction to retain customers and improve services.

## Tools Used
- **Python**
- **Pandas**
- **Scikit-Learn**
- **Seaborn**
- **Matplotlib**
- **SciPy**

## Approach
1. **Data Loading & Cleaning:**  
   - Loaded customer data from CSV files.  
   - Identified and handled missing values in the dataset.  
   - Converted categorical variables to numerical values using encoding techniques.

2. **Exploratory Data Analysis (EDA):**  
   - Visualized data distributions and correlations between features.  
   - Performed statistical tests to determine feature significance.  

3. **Feature Engineering & Selection:**
   - Used statistical tests (ANOVA, Chi-square) to select the most important predictors. 
   - Normalized and scaled numerical features.   

5. **Model Training & Evaluation:**  
   - Implemented multiple machine learning models (DecisionTree, Random Forest, XGBoost).  
   - Used GridSearchCV for hyperparameter tuning to optimize model performance.
   - Applied ensemble methods to enhance predictive accuracy.  
   - Evaluated model performance using precision, recall, and F1-score.

## Results
- Achieved **81% accuracy** in predicting customer churn using optimized machine learning models.  
- Identified key factors influencing churn, such as contract type and monthly charges.

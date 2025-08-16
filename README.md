# Customer Satisfaction Prediction  

## Overview  
**Customer Satisfaction Prediction** is a machine learning project that predicts whether a customer is happy or unhappy based on survey responses.  
The project uses classification models and explainability techniques to identify the most important factors influencing customer satisfaction.  

This project was originally called *Happy Customer Prediction* and the notebook file was named *Assignment 1 Final Workbook.ipynb*. It has now been renamed and documented for clarity and reproducibility.  

Note: The dataset (ACME-HappinessSurvey2020.csv) is **not included** in this repository due to proprietary restrictions.  

---

## Goals  
- Predict if a customer is **happy (1)** or **unhappy (0)** based on survey ratings.  
- Identify which factors (delivery, contents, price, courier, app usability) most influence satisfaction.  
- Provide interpretable ML models to support business decision-making.  

---

## Features  
- **Data Preprocessing:** Handling missing values, scaling, and encoding categorical variables.  
- **Class Imbalance Handling:** SMOTE oversampling and undersampling techniques.  
- **Feature Selection:** Statistical selection with `SelectKBest`.  
- **Modeling:**  
  - Logistic Regression  
  - Decision Trees, Random Forests  
  - Gradient Boosting, AdaBoost, XGBoost  
  - Bagging & Stacking classifiers  
- **Hyperparameter Tuning:** GridSearchCV and RandomizedSearchCV.  
- **Explainability:** LIME and SHAP visualizations for feature importance.  

---

## Methodology  
1. **Data Preparation** – Imported survey data, handled missing values, applied scaling and encoding.  
2. **Exploratory Analysis** – Analyzed distributions and correlations among features.  
3. **Model Training** – Trained multiple ML classifiers on customer happiness prediction.  
4. **Model Tuning** – Optimized hyperparameters using cross-validation.  
5. **Interpretability** – Applied LIME and SHAP to explain model predictions.  

---

## Results  
- Achieved strong classification accuracy and recall on test data.  
- SHAP and LIME highlighted **delivery satisfaction (X1)** and **price fairness (X4)** as key drivers of customer happiness.  
- Ensemble models (Random Forest, XGBoost) performed best.  

---

## Tools & Technologies  
- **Python**  
- **Scikit-learn** – preprocessing, models, evaluation  
- **XGBoost** – boosting algorithms  
- **Imbalanced-learn** – SMOTE/undersampling  
- **LIME, SHAP** – interpretability  
- **Matplotlib, Seaborn** – visualization  
- **Pandas, NumPy** – data manipulation  

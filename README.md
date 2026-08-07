# Telecom Customer Churn Prediction using Machine Learning

## Overview

This project predicts whether a telecom customer is likely to churn using Machine Learning techniques. The project includes data preprocessing, feature engineering, model comparison, imbalance handling, explainability, and business insights.

---


## 📊 Project Results

### Customer Churn Distribution

![Customer Churn Distribution](images/Customer%20Churn%20Distribution.png)

---

### Statistical Summary

![Statistical Summary](images/Statistical%20Summary.png)

---

### Machine Learning Pipeline

![Machine Learning Pipeline](images/Logistic%20Pipeline.png)

---

### Model Comparison

![Model Comparison](images/Model%20Comparison%20Table.png)

---

### SHAP Feature Importance

![SHAP Summary](images/SHAP%20Summary.png)

---

## Dataset

- IBM Telco Customer Churn Dataset
- 7,043 customer records
- 21 original features

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- SHAP
- Matplotlib
- Seaborn
- imbalanced-learn (SMOTE)

---

## Project Workflow

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Data Preprocessing
- Machine Learning Model Training
- Model Comparison
- Handling Class Imbalance using SMOTE
- Model Explainability using SHAP
- Business Recommendations

---

## Machine Learning Models

- Logistic Regression
- Random Forest
- Gradient Boosting
- Support Vector Machine (SVM)
- XGBoost

---

## Best Model

Gradient Boosting achieved the best overall performance with approximately **79.46% Accuracy**.

---

## Repository Structure

```
telecom-customer-churn-prediction
│
├── Customer_Churn_Prediction.ipynb
├── README.md
├── requirements.txt
│
├── dataset
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── models
│   ├── best_churn_model.pkl
│   └── preprocessor.pkl
│
└── images
```

---

## Future Improvements

- Hyperparameter Optimization
- Ensemble Learning
- Model Deployment using Flask/FastAPI
- Interactive Dashboard

---

## Author

**Waleed Hasnain**
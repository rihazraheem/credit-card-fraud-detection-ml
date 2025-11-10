# Credit Card Fraud Detection using Machine Learning
This project builds and compares several machine learning models to detect fraudulent credit card transactions.  
It focuses on handling data imbalance, scaling features, and evaluating models with appropriate metrics for fraud detection.

#  Project Overview
Fraud detection is a key challenge in financial transactions due to the high imbalance between legitimate and fraudulent data.  
This notebook demonstrates how to:
- Preprocess and scale transaction data
- Handle class imbalance using SMOTE
- Train multiple ML models
- Compare performance using Precision, Recall, F1-Score, and ROC-AUC

# Workflow

1. **Data Loading:** Read credit card transaction dataset  
2. **EDA:** Visualize fraud ratio and feature correlations  
3. **Preprocessing:** Feature scaling using `StandardScaler`  
4. **Imbalance Handling:** Oversample fraud cases using `SMOTE`  
5. **Model Training:** Fit multiple algorithms for comparison  
6. **Evaluation:** Generate confusion matrices, classification reports, and ROC curves

7. 
The dataset is from an open-source website, Kaggle.com.
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

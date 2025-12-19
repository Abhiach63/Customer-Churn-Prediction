# Customer-Transaction-Prediction
Machine learning project to create predictive model which will help the bank to identify which customer will make transactions in future.

## 📌 Problem Statement
Predict whether a customer will make the target transaction using anonymized banking data.

## 📂 Dataset Overview
- Rows: 200,000
- Columns: 202
- Target variable is highly imbalanced (Class 1 ≈ 10%)

## 🎯 Objective
- Analyze customer transaction behavior
- Handle severe class imbalance
- Compare multiple ML models
- Select a production-ready model

## 🧠 Models Implemented
- Logistic Regression (baseline)
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier

## ⚙️ Techniques Used
- Feature scaling
- Class weighting
- SMOTE (for tree models)
- Hyperparameter tuning
- Threshold tuning
- Precision–Recall optimization

## 🏆 Best Model
**XGBoost with threshold tuning (0.25)**  
Achieved the best balance between recall and precision, making it suitable for banking risk prediction.

## 📊 Evaluation Metrics
- Confusion Matrix
- Precision
- Recall
- F1-score
- ROC-AUC

## 🛠 Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn

## 🚀 How to Run
```bash
pip install -r requirements.txt

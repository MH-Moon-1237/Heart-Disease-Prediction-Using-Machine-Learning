# Heart-Disease-Prediction-Using-Machine-Learning
Machine learning–based heart disease prediction using multiple classifiers with ROC–AUC evaluation.


This project presents a machine learning–based system for predicting heart
disease using clinical and demographic patient data. Multiple classification
models are trained and evaluated to identify the most effective approach for
accurate and reliable heart disease prediction.

---

## 🎯 Project Objective

The main objective of this project is to develop an intelligent system that can:
- Predict the presence of heart disease based on patient health indicators
- Compare the performance of multiple machine learning models
- Handle class imbalance effectively
- Support medical decision-making through data-driven insights

---

## 🗂️ Dataset Description

- Dataset: Heart Disease Dataset (UCI / clinical dataset)
- Data includes patient attributes such as:
  - Age, Sex
  - Chest pain type
  - Blood pressure
  - Cholesterol level
  - Fasting blood sugar
  - ECG results
  - Maximum heart rate
- Target variable:
  - Presence or absence of heart disease

---

## ⚙️ Data Preprocessing

The following preprocessing steps were applied:
- Handling missing values
- Encoding categorical variables
- Feature scaling and normalization
- Outlier treatment using IQR method
- Class imbalance handling using **SMOTE**

These steps improve model stability and generalization performance.

---

## 🧠 Machine Learning Models Used

The following classification models were implemented and compared:
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Naive Bayes
- XGBoost

Among these models, **XGBoost and Random Forest** achieved the best performance.

---

## 📊 Evaluation Metrics

Model performance was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve and AUC score

These metrics ensure a comprehensive evaluation of classification performance.

---

## 🔁 Validation Strategy

- Train–test split was used for performance evaluation
- SMOTE was applied to address class imbalance
- ROC–AUC analysis was performed to assess discriminative ability

> Note: Future work will include strict unseen test sets and cross-validation
for more robust evaluation.

---

## 🚀 How to Run the Project

1. Install required dependencies:
   ```bash
   pip install -r requirements.txt


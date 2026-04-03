#  Heart Disease Prediction

##  Overview
This project predicts the likelihood of heart disease using machine learning models. It demonstrates a complete ML workflow including data preprocessing, feature engineering, model training, and evaluation.

---

## 📂 Dataset
The dataset (`heart.csv`) contains medical attributes such as:

- Age  
- Sex  
- Chest Pain Type (cp)  
- Resting Blood Pressure (trestbps)  
- Cholesterol (chol)  
- Fasting Blood Sugar (fbs)  
- Resting ECG (restecg)  
- Max Heart Rate (thalach)  
- Exercise-Induced Angina (exang)  
- Oldpeak  
- Slope  
- Number of Vessels (ca)  
- Thal  
- Target (0 = No Disease, 1 = Disease)

---

##  Models Used

### 1. Logistic Regression
- Baseline linear model

### 2. Support Vector Machine (SVM)
- Effective for classification tasks

### 3. K-Nearest Neighbors (KNN)
- Tested multiple values of K (1–39)
- Best performance observed at **K = 2**

---

## 📊 Model Evaluation

- Train-test split: **80% training / 20% testing**
- Evaluation metric: **Accuracy Score**

Models compared:
- Logistic Regression
- SVM
- KNN

Visualization done using **Seaborn barplot**

---

##  Results
- Compared accuracy of all models
- KNN achieved strong performance with optimal K value
- Visualization helps in selecting the best model

---

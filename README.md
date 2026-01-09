# 🩺 Diabetes Prediction - Proof of Concept (POC)

A machine learning-based predictive model for diabetes detection using patient health metrics. This project implements multiple classification algorithms to predict diabetes and evaluates their performance.

## 📌 Overview
This project is a Proof of Concept (POC) for predicting diabetes based on patient health data. Key highlights include:

- **Data Preprocessing & Feature Engineering:** StandardScaler & Label Encoding  
- **Exploratory Data Analysis (EDA):** Visualizations using Seaborn and Matplotlib  
- **Machine Learning Models:** Logistic Regression, K-Nearest Neighbors, Random Forest, Support Vector Machine, and more  
- **Performance Metrics:** Accuracy, Precision, Recall, F1-Score  
- **Hyperparameter Tuning:** GridSearchCV  

## 📊 Dataset
- **Source:** Diabetes Prediction Dataset  
- **Size:** 100,000 samples, 9 features  
- **Target Variable:** `diabetes` (0 = No Diabetes, 1 = Diabetes)  
- **Features:**  
  - Gender  
  - Age  
  - Hypertension  
  - Heart Disease  
  - Smoking History  
  - BMI  
  - HbA1c Level  
  - Blood Glucose Level  

## 🏗️ Project Structure
Diabetes_Prediction_POC.ipynb 
diabetes_prediction_dataset.csv



## 📊 Model Performance

| Model                  | Accuracy  |
|------------------------|-----------|
| Random Forest          | ~97.0%    |
| K-Nearest Neighbors    | ~96.2%    |
| Support Vector Machine | ~96.1%    |
| Logistic Regression    | ~95.9%    |

## 👥 Author
**Ariful Islam**  


**Note:** This project is intended as a Proof of Concept (POC) and should not be used for medical diagnosis in real-world applications.



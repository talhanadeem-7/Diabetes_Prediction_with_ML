# 🤖 Predicting Diabetes with Machine Learning

This project was built as part of my Machine Learning coursework at **UMT**. The goal was to build a complete ML pipeline to predict diabetes using real-world health data from the BRFSS 2015 dataset. It includes data cleaning, preprocessing, model comparison, and performance evaluation.

---

## 📌 Project Overview

- **Objective:** Predict whether an individual has diabetes based on diagnostic health indicators.
- **Dataset:** Behavioral Risk Factor Surveillance System (BRFSS) 2015
- **Workflow:** Data Exploration → Preprocessing → Model Training → Evaluation
- **Models Used:** Logistic Regression, Decision Tree, Random Forest, XGBoost
- **Best Model:** XGBoost with 83.6% Accuracy and 0.795870 F1-Score

---

## 🗂️ Dataset

The dataset includes the following medical features:

- Age  
- Body Mass Index (BMI)  
- HbA1c Level  
- Blood Glucose Level  
- Physical and mental health indicators  
- Smoking, alcohol, and exercise habits  
- And other relevant diagnostic attributes  

---

## 🔍 What I Did

- 🧹 **Data Cleaning:** Removed duplicates, verified class balance  
- 📊 **Exploratory Data Analysis (EDA):** Visualized distributions and key features  
- ⚙️ **Preprocessing:** 
  - Scaled features using `StandardScaler`  
  - Encoded categorical data with `ColumnTransformer`  
  - Used `Pipeline` to streamline preprocessing and modeling  
- 🤖 **Model Training:** Trained and tested four classifiers  
- 📈 **Model Evaluation:** Accuracy, Precision, Recall, F1-Score, ROC-AUC  
- 🧪 **Overfitting Check:** Compared train vs test performance  
- 🧮 **Training Size Impact:** Evaluated model accuracy with different train sizes

---

## ✅ Results

- **XGBoost** performed the best:
  - **Accuracy:** `83.6%`
  - **F1-Score:** `0.795870`
- XGBoost consistently performed better across varying training set sizes, peaking at `79.6%` when using 100% of training data.

---

## 📊 Visuals Included

- Feature distribution plots
- Confusion matrices for all models
- Model comparison charts
- F1-Score vs. Training Data Size graph

---

## ⚙️ Technologies Used

- Python  
- Jupyter Notebook  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Scikit-learn  
- XGBoost  

---

## 🚀 Getting Started

To run the project locally:

---

### 1. Clone the repository

```bash
git clone https://github.com/sameerrr0111/Predicting_Diabetes_with_ML

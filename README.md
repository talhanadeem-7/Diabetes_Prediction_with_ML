# 🤖 Predicting Diabetes with Machine Learning

This project was built as part of my machine learning journey. The goal was to build a complete ML pipeline to predict diabetes using real-world health data from the **BRFSS 2015** dataset. It includes data cleaning, preprocessing, model comparison, and performance evaluation.

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

After evaluating all four models, here’s the final performance comparison:

| **Model**              | **Accuracy** | **F1-Score** |
|------------------------|--------------|--------------|
| XGBoost                | 83.6%        | 0.795870     |
| Logistic Regression    | 83.3%        | 0.789844     |
| Random Forest          | 82.4%        | 0.787020     |
| Decision Tree          | 73.9%        | 0.746779     |

🔍 **XGBoost** showed the best overall performance, achieving the highest accuracy and F1-Score among all tested models.

---

## 📊 Visuals Included

- 📌 Feature distribution plots  
- 📌 Confusion matrices for all models  
- 📌 Model performance comparison  
- 📌 F1-Score vs. Training Data Size graph  

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

1. Clone the repository

```bash
git clone https://github.com/talhanadeem-7/Diabetes_Prediction_with_ML
```
2. Open the code in VS Code or any other editor.

3. Install the dependencies
```bash
 pip install -r requirements.txt
```
4. Load the dataset Place your dataset file i.e. diabetes_012_health_indicators_BRFSS2015.csv in the working directory.

5. Run the notebook. Open the .ipynb file in Jupyter Notebook, Google Colab or VS Code and run all cells step by step.

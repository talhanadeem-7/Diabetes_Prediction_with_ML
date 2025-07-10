# Diabetes_Prediction_with_ML
This project was built as part of my machine learning journey, where I aimed to develop a complete, real-world ML pipeline to predict diabetes using health indicators from the BRFSS 2015 dataset.

📌 Project Overview
Objective: Predict whether an individual has diabetes based on various health metrics

Dataset: BRFSS 2015 health survey data

Tech Stack: Python, Pandas, Scikit-learn, XGBoost, Seaborn, Jupyter Notebook


🔍 What I Did
🧹 Data Cleaning: Removed duplicate rows and verified class distribution

📊 EDA: Visualized health features such as Age, BMI, HbA1c, and Glucose

⚙️ Preprocessing:

Feature scaling using StandardScaler

Encoding with ColumnTransformer

Combined using Pipeline


🤖 Modeling:

Trained 4 models: Logistic Regression, Decision Tree, Random Forest, and XGBoost


📈 Evaluation:

Metrics used: Accuracy, Precision, Recall, F1-Score, ROC-AUC

Compared model performance

Checked for overfitting and tested the impact of different training sizes


✅ Results
Best Model: XGBoost

Accuracy: 83.6%

F1-Score: 0.795870

XGBoost showed the best balance between precision and recall among all models.

Additional analysis showed that larger training sizes slightly improved performance (up to 79.6%).


📊 Visualizations Included
Feature distributions

Confusion matrices for each model

Model performance comparison

F1-Score vs. Training Data Size graph


⚙️ Technologies Used
Python

Pandas & NumPy

Matplotlib & Seaborn

Scikit-learn

XGBoost

Jupyter Notebook

🚀 Getting Started
To run the project locally:

# 1. Clone the repository
git clone https://github.com/your-username/diabetes-ml-prediction

# 2. Change directory
cd diabetes-ml-prediction

# 3. Install dependencies
pip install -r requirements.txt
Make sure the dataset (diabetes_012_health_indicators_BRFSS2015.csv) is in your working directory.

Then, open the notebook and run all cells:
jupyter notebook Diabetes_Prediction.ipynb

💬 Feedback & Collaboration
Feel free to fork the repo, open issues, or suggest improvements. I'm always open to learning and collaborating on health-focused AI solutions.

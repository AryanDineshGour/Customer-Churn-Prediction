# Customer-Churn-Prediction
1) Project Overview

This project constructs a machine learning model to forecast customer churn, which is determined by analyzing customer demographics, account details, and service usage data. The objective is to assist companies in recognizing vulnerable clients and implementing protective measures.

2) Dataset Source

Telco Customer Churn Dataset (Kaggle)
https://www. kaggle. com/datasets/blastchar/telco-customer-churn

3) Steps to Run the Project

Clone the repository:

git clone 
cd customer-churn-prediction


Install required libraries:

pip install pandas numpy scikit-learn matplotlib seaborn xgboost


Input the dataset file named (WA_Fn-UseC_-Telco-Customer-Churn). Csv) located within the project directory.

Run the Python script or Jupyter notebook:

python churn_prediction. py


Or start and let it run. If working with Jupyter Notebook, use an ipynb file.

4) Model Used

Logistic Regression

Random Forest Classifier

XGBoost Classifier

The Random Forest and XGBoost models showed the highest performance and were employed for the final assessment.

5) Final Result Summary

The model accurately forecasts customer attrition at an 80-85% rate.

Random Forest and XGBoost demonstrated superior performance relative to Logistic Regression.

The project encompasses a thorough ML pipeline: data cleaning, feature transformation, model creation, and assessing performance through accuracy and confusion matrix.

Learnings

Learned how to preprocess categorical data

Understood the importance of feature scaling

Obtained practical knowledge through working with classification models and assessing evaluation metrics.


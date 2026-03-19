Customer Churn Prediction in Telecom Industry
1. Project Overview:This project aims to reproduce the results of the research paper: "Churn Prediction of Customer in Telecom Industry using Machine Learning Algorithms. We focus on predicting whether a customer will leave the service provider based on their usage patterns and demographics
2. Dataset Information:
Source: Kaggle (Telco Customer Churn dataset).
Features used: Gender, Tenure, Monthly Charges, and Total Charges.
Target: Churn (Yes/No)
3. Methodology:
Following the research paper's proposed model:
Data Preprocessing: Handled missing values in TotalCharges and performed label encoding for categorical variables.
Data Splitting: 80% Training and 20% Testing.
Algorithms Implemented: Decision Tree: To handle non linear data.
Logistic Regression: To estimate the probability of churn.
4. Results:
Based on our pythonPR.ipynb execution:
Logistic Regression Accuracy: ~77.9%.
Decision Tree Accuracy: ~71.6%.
5. Project Structure:
data/: Contains the Customer.csv file.
models/: Contains the pythonPR.ipynb file with the implementation code.
README.md: Summary and instructions.

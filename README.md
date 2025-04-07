Customer Churn Prediction
Project Overview
This project focuses on predicting customer churn for a telecom company using machine learning. By analyzing customer data such as contract type, monthly charges, tenure, and service usage, the model identifies customers likely to leave the service. Early churn detection helps businesses improve retention strategies.

Dataset
The dataset used is from Kaggle:

It contains 7,043 entries and includes features like:

Demographics: Gender, SeniorCitizen, Partner, Dependents

Account Info: Tenure, Contract, PaymentMethod, MonthlyCharges, TotalCharges

Services: InternetService, OnlineSecurity, TechSupport, etc.

Target: Churn (Yes/No)

Tech Stack
Python 

Pandas, NumPy

Seaborn, Matplotlib

Scikit-learn

EDA Highlights
Handled missing and inconsistent data

Visualized churn vs. features like Contract type, Tenure, and MonthlyCharges

Found that longer contracts and lower charges reduce churn likelihood

Addressed class imbalance using stratified splitting

Model Training
Tried Logistic Regression, Decision Tree, and Random Forest

Final model: Logistic Regression

Achieved ~80% accuracy

Evaluated using:

Confusion Matrix

ROC AUC

Precision, Recall, F1-score

# Credit Risk Modeling

## 📌 Project Overview
This project focuses on **Credit Risk Modeling**, where the objective is to predict whether a loan applicant is likely to **default (bad risk)** or **repay (good risk)**.  
**Task 1** of my **Data Science internship at DevelopersHub Corporation**.

The project uses the **German Credit Dataset** and applies exploratory data analysis, feature engineering, and machine learning models to understand and predict credit risk.

---

## 🎯 Problem Statement
To build a machine learning model that predicts loan default risk based on applicant and loan characteristics.

---

## 📊 Dataset
The dataset contains information about:
- Demographics (Age, Sex, Job)
- Financial status (Savings, Checking account)
- Loan details (Credit amount, Duration, Purpose, Housing)
- Target variable: **Risk** (Good / Bad)

---

## 🔍 Exploratory Data Analysis (EDA)
Key insights from EDA:
- Larger **credit amounts** and longer **loan durations** are associated with higher default risk.
- Applicants with **higher savings and better checking account status** tend to be safer.
- Customers living in **rent/free housing** show higher default risk.
- Education-related loans have a higher proportion of bad risk.
- No strong multicollinearity among numerical features.

---

## ⚙️ Feature Engineering
- Selected relevant numerical and categorical features
- Encoded categorical variables using **Label Encoding**
- Handled missing values
- Stratified train-test split to address class imbalance

---

## 🤖 Models Trained
The following models were trained and tuned using **GridSearchCV**:
- Decision Tree
- Random Forest
- Extra Trees
- XGBoost

📌 **Best Performing Model:** Extra Trees Classifier

---

## 📈 Evaluation Metric
- Accuracy score on test data
- Class imbalance handled using class weights and scale position weight

---

## 🧠 Key Learnings
- Credit risk depends more on **loan behavior** than age alone
- Ensemble models perform better for structured financial data
- Model interpretability and business understanding are as important as accuracy

---

## 🛠 Tools & Technologies
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Joblib

---

## 🚀 Conclusion
This project demonstrates how machine learning can assist financial institutions in **risk assessment and decision-making** by identifying potential defaulters early.

---

## 📎 Internship
**DevelopersHub Corporation – Data Science And Analytics Internship**  
Task 1: Credit Risk Modeling


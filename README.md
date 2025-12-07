# 🏦 Loan Eligibility Prediction – Machine Learning Project

This project predicts whether a customer's loan application should be **Approved** or **Not Approved** using Machine Learning.  
It was completed as part of my **Data Science Internship**, where I learned end-to-end ML workflow including data cleaning, feature engineering, model building, and prediction on new data.

---

## 🚀 Project Overview

The goal of this project is to build a model that can automatically determine loan eligibility based on customer financial and demographic details.

**Target Variable:**  
`Loan_Status` → Approved (1) / Not Approved (0)

---

## 📊 Features Used

The dataset contains the following columns:

- Gender  
- Married  
- Dependents  
- Education  
- Self_Employed  
- ApplicantIncome  
- CoapplicantIncome  
- LoanAmount  
- Loan_Amount_Term  
- Credit_History  
- Property_Area  
- Loan_Status  

---

## 🧹 Data Preprocessing

✔ Handled missing values  
✔ Converted categorical values to numeric  
✔ Created log transformations:
- `LoanAmount_log`
- `TotalIncome_log`

✔ One-hot encoded:
- Dependents: (1, 2, 3+)  
- Property_Area: (Semiurban, Urban)

✔ Final model features:


---

## 🤖 Machine Learning Model

I trained a **Logistic Regression** model using Scikit-Learn.

Steps:
1. Train-test split  
2. Feature scaling using StandardScaler  
3. Model training  
4. Model evaluation  
5. Saving model + scaler as `.pkl` files  

---

## 📈 Model Evaluation

Metrics included:

- Accuracy Score  
- Classification Report  
- Confusion Matrix  

The trained model was then used to predict loan status for:

✔ Existing customers  
✔ New customer data (uploaded separately)

---

## 📝 Files in This Repository

| File | Description |
|------|-------------|
| `Loan_Eligibility_Prediction.ipynb` | Complete Jupyter Notebook |
| `loan_model.pkl` | Trained ML model |
| `scaler.pkl` | StandardScaler used to preprocess inputs |
| `old_customers_predictions.csv` | Predictions for original dataset |
| `new_customers_predictions.csv` | Predictions for new customer data |
| `README.md` | Project description (this file) |

---

## 🔍 How to Use

1. Clone this repository  
2. Upload any new CSV containing customer data  
3. Apply the same preprocessing steps  
4. Load `loan_model.pkl` and `scaler.pkl`  
5. Use them to predict approval for new customers  

---

## 🧠 Skills Used

- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Data Cleaning  
- Feature Engineering  
- Machine Learning  
- Logistic Regression  
- Model Deployment Basics  

---

## 🙌 Acknowledgment

This project was completed as part of my **Data Science Internship**, where I practiced real-world machine learning workflows and prediction tasks.

---

## 📬 Contact

If you want to connect or discuss ML/Data Science:

**LinkedIn:** *(Add your profile link here)*  
**GitHub:** *(Your profile link)*


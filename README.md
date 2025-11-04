# 🏦 Loan Approval Prediction Model

This project focuses on predicting whether a loan application will be **approved or rejected** using **machine learning algorithms**. It aims to assist financial institutions in making quick, data-driven lending decisions.

---

## 🚀 Project Overview

The model analyzes applicant and loan-related features such as **income, credit history, education, and property area** to predict approval likelihood. The final model achieved an accuracy of **83%** using a **Random Forest Classifier**.

---

## ⚙️ Tech Stack

* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Algorithms:** Logistic Regression, Decision Tree, Random Forest

---

## 🧩 Features Used

* Applicant Income
* Coapplicant Income
* Loan Amount
* Loan Term
* Credit History
* Gender, Marital Status, Education
* Property Area
* Self Employment Status

---

## 🧠 Model Workflow

1. Data Cleaning & Preprocessing
2. Encoding Categorical Variables
3. Splitting Data into Train/Test Sets
4. Model Training (Multiple Classifiers)
5. Model Evaluation (Accuracy, Precision, Recall, ROC-AUC)
6. Feature Importance Analysis

---

## Result
 
High Accuracy across the board: Most models achieved a Test Accuracy in the 83%-86% range.

Stability is Key: While Decision Tree and Gradient Boosting had the highest Test Accuracy (0.86), the Decision Tree had the lowest Cross-Validation score (0.78), indicating potential instability or overfitting.

Best starting point: Logistic Regression had a strong, stable performance (0.85 Acc, 0.84 CV Score).


## 📈 Insights

* **Credit history** and **applicant income** were the strongest predictors of loan approval.
* The **Random Forest model** provided the best trade-off between accuracy and interpretability.

---

## 💡 Future Improvements

* Add feature scaling and hyperparameter tuning
* Deploy model using Flask or Streamlit
* Integrate explainability tools (e.g., SHAP)

---

## 🏁 Conclusion

This model demonstrates how **machine learning** can automate and optimize the **loan approval process**, reducing bias and manual workload while improving accuracy.


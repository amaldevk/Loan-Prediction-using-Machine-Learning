# 🏦 Loan Approval Prediction using Machine Learning

## 📌 Project Overview

Loan approval is one of the most important decision-making processes in the banking sector. Financial institutions evaluate several applicant attributes before approving or rejecting a loan application.

This project builds a machine learning classification model to predict whether a loan application will be **Approved** or **Rejected** using applicant information. The project includes complete data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison using **K-Nearest Neighbors (KNN)** and **Decision Tree** algorithms.

---

# 🎯 Objectives

* Perform Exploratory Data Analysis (EDA)
* Handle missing values
* Encode categorical variables
* Train multiple machine learning models
* Compare model performance
* Identify the most influential features affecting loan approval
* Predict loan approval for new applicants

---

# 📂 Dataset

The dataset contains information about loan applicants, including:

| Feature           | Description                           |
| ----------------- | ------------------------------------- |
| Gender            | Applicant Gender                      |
| Married           | Marital Status                        |
| Dependents        | Number of Dependents                  |
| Education         | Education Level                       |
| Self_Employed     | Self Employment Status                |
| ApplicantIncome   | Applicant Income                      |
| CoapplicantIncome | Co-applicant Income                   |
| LoanAmount        | Requested Loan Amount                 |
| Loan_Amount_Term  | Loan Repayment Term                   |
| Credit_History    | Credit History                        |
| Property_Area     | Property Area                         |
| Loan_Status       | Target Variable (Approved / Rejected) |

---

# 🛠 Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

# 📊 Exploratory Data Analysis (EDA)

The project includes:

* Dataset inspection
* Missing value analysis
* Statistical summary
* Income distribution visualization
* Loan amount distribution
* Loan status distribution
* Credit History vs Loan Status
* Property Area analysis
* Education analysis

---

# ⚙️ Data Preprocessing

The following preprocessing steps were performed:

* Missing value imputation
* Removal of unnecessary columns
* Label Encoding of categorical features
* Train-Test Split (80:20)
* Feature Standardization (for KNN)

---

# 🤖 Machine Learning Models

Two supervised classification algorithms were implemented:

### 1. K-Nearest Neighbors (KNN)

* Standardized numerical features
* Euclidean distance-based classification
* K = 5 Nearest Neighbors

### 2. Decision Tree

* Criterion: Gini Index
* Maximum Depth: 5
* Feature Importance Analysis

---

# 📈 Model Evaluation

The models were evaluated using:

* Accuracy Score
* Confusion Matrix
* Feature Importance (Decision Tree)

---

# 🔍 Key Findings

* **Credit History** is the most influential feature for loan approval.
* Applicant Income and Loan Amount also contribute to prediction.
* Decision Tree automatically identifies the most important features.
* KNN performs well after feature standardization.
* Personal attributes such as Gender and Marital Status have minimal influence on the trained Decision Tree model.

---

# 📁 Project Structure

```
loan-approval-prediction-ml/
│
├── Loan_Prediction.ipynb
├── train_u6lujuX_CVtuZ9i.csv
├── README.md
```



---

# 📌 Future Improvements

* Hyperparameter tuning using GridSearchCV
* Random Forest Classifier
* XGBoost Classifier
* ROC Curve Analysis
* Cross Validation
* Web Application using Flask or Streamlit

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:

* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Classification Algorithms
* Model Evaluation
* Data Visualization
* Machine Learning Workflow using Scikit-learn

---

# 👨‍💻 Author

**Amaldev K**

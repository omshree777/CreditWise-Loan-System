# CreditWise-Loan-System-
CreditWise Loan System is a machine learning-based loan approval prediction system that , analyzes applicant data and predicts loan eligibility using classification algorithms.

# CreditWise Loan Approval System

CreditWise Loan Approval System is a machine learning project that predicts whether a loan application will be approved or not based on applicant financial data.

The project compares multiple classification algorithms to determine the best-performing model.

---

## 📌 Project Objective

To build and compare multiple machine learning models to accurately predict loan approval status and support better financial decision-making.

---

## 📊 Dataset Features

The dataset includes:

- Education Level
- Applicant Income
- Credit Score
- Debt-to-Income (DTI) Ratio
- Employment Details
- Other financial indicators

Target Variable:
- `Loan_Approved` (Approved / Not Approved)

---

## ⚙️ Data Preprocessing

The following preprocessing steps were applied:

- Handling missing values using **SimpleImputer (mean strategy)**
- Encoding categorical variables using **LabelEncoder**
- Feature Engineering:
  - Squared DTI Ratio
  - Squared Credit Score
- Train-test split (80% training, 20% testing)
- Feature scaling using **StandardScaler**

---

## 🧠 Machine Learning Models Used

The following classification algorithms were implemented and compared:

1. Logistic Regression  
2. K-Nearest Neighbors (KNN)  
3. Naive Bayes  

---

## 📈 Model Evaluation Metrics

Each model was evaluated using:

- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- Confusion Matrix

The best-performing model was selected based on overall evaluation metrics.

Best Model on basis of Precision => Naive Bayes Model

Best Model: Naive Bayes Model 
Precision : 80%

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 👨‍💻 Author

Omshreekrishna Boraju 
Machine Learning Enthusiast 
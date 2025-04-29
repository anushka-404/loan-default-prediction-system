# loan-default-prediction-system


This repository contains a machine learning project that predicts the likelihood of a loan default using the [Loan Default Dataset](https://www.kaggle.com/datasets/yasserh/loan-default-dataset) provided by Yasser H on Kaggle.

## 📚 Project Overview

Loan default prediction is a critical task for financial institutions, helping them minimize risk by identifying borrowers who are likely to default on their loans.  
In this project, I have used machine learning techniques to build a model that classifies whether a borrower will default or not based on several features.

The complete workflow — from data exploration, preprocessing, model building, to evaluation — is available in the uploaded **Jupyter Notebook** (`loan_default_prediction.ipynb`).

---

## 📈 Dataset Information

- **Source**: [Kaggle - Loan Default Dataset](https://www.kaggle.com/datasets/yasserh/loan-default-dataset)
- **Description**: The dataset contains information about loans, borrowers, and whether the loan resulted in a default.

### Attributes:

| Attribute | Description |
|:----------|:------------|
| `loan_amount` | Amount of money borrowed |
| `term` | Duration of the loan (e.g., 36 months, 60 months) |
| `interest_rate` | Interest rate of the loan |
| `installment` | Monthly payment amount |
| `grade` | Loan grade assigned based on credit risk |
| `sub_grade` | Sub-category of loan grade |
| `employment_length` | Number of years the borrower has been employed |
| `home_ownership` | Home ownership status (e.g., Rent, Own, Mortgage) |
| `annual_income` | Borrower's annual income |
| `verification_status` | Whether income was verified |
| `issue_date` | Date when the loan was issued |
| `purpose` | Purpose of the loan (e.g., debt consolidation, small business) |
| `address_state` | State where the borrower resides |
| `debt_to_income` | Ratio of borrower's debt payments to income |
| `delinquency_2yrs` | Number of delinquencies in the past 2 years |
| `fico_range_low` | Lower range of the borrower's FICO score |
| `fico_range_high` | Higher range of the borrower's FICO score |
| `open_acc` | Number of open credit lines |
| `pub_rec` | Number of derogatory public records |
| `revol_util` | Revolving line utilization rate |
| `total_acc` | Total number of credit lines |
| `application_type` | Type of loan application (Individual/Joint) |
| `loan_status` | Target variable — whether the loan was paid back or defaulted |

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🚀 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/loan-default-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd loan-default-prediction
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook loan_default_prediction.ipynb
   ```

---

## 📌 Acknowledgments

- Dataset by [Yasser H on Kaggle](https://www.kaggle.com/datasets/yasserh/loan-default-dataset)

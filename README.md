# 💳 Consumer Credit Risk Analysis

This project focuses on analyzing consumer credit data to assess the risk of loan default. It applies exploratory data analysis, data preprocessing, and classification modeling to predict credit risk using key financial indicators.
🧠 Objectives

    Analyze credit-related financial features.

    Identify strong predictors of credit risk.

    Build classification models to predict loan default likelihood.

    Evaluate model performance using standard metrics.

# 📦 Dataset Description

Each row in the dataset represents a consumer applying for a loan. The target variable indicates whether the applicant is likely to default.
<details> <summary><strong>
    
# 📊 Features Description (Click to expand)</strong></summary>

| Column Name                        | Description                                                              |
|-----------------------------------|--------------------------------------------------------------------------|
| `Customer_ID`                     | Unique customer identifier (dropped from modeling).                      |
| `Credit_Score`                    | Creditworthiness score (300–850 scale).                                  |
| `Income`                          | Annual income of the applicant (USD).                                    |
| `DTI_Ratios`                      | Ratio of debt payments to income.                                        |
| `Employment`                      | Employment condition (Employed, Unemployed, etc.).                       |
| `Purpose`                         | Reason for the loan (Auto, Education, Business, etc.).                   |
| `Credit_History`                  | Numeric score (1–20) indicating the strength or length of credit history |
| `Open_Accounts`                   | Number of active credit accounts.                                        |
| `Utilization`                     | Ratio of credit used to total available credit.                          |
| `Delinquencies`                   | Count of missed payments.                                                |
| `Housing`                         | Rental or ownership status.                                              |
| `Default`                         | Target variable — whether the applicant defaulted (1 = Yes, 0 = No).     |

</details>
🧹 Preprocessing Steps

    Handled Missing Values using imputation strategies.

    One-Hot Encoding applied to categorical features like Loan_Purpose and Employment_Status.

    Feature Scaling used for numerical features via standardization.

# 🤖 Modeling

Classification model trained is Random Forest Classifier

# Model Evaluation Metrics:

    Accuracy

    Precision & Recall

    F1-Score

# 🔍 Key Insights

    Credit_Score, Debt_to_Income_Ratio, and Delinquencies are highly predictive of default.

    Applicants with high Credit_Utilization_Ratio and low income were more likely to default.



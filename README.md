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
| `Debt_to_Income_Ratio`            | Ratio of debt payments to income.                                        |
| `Employment_Status`               | Employment condition (Employed, Unemployed, etc.).                       |
| `Loan_Amount_Requested`           | Loan amount applied for in USD.                                          |
| `Loan_Purpose`                    | Reason for the loan (Auto, Education, Business, etc.).                   |
| `Length_of_Credit_History_Years` | Years since the customer opened their first credit line.                |
| `Open_Accounts`                   | Number of active credit accounts.                                        |
| `Credit_Utilization_Ratio`        | Ratio of credit used to total available credit.                          |
| `Delinquencies`                   | Count of missed payments.                                                |
| `Bankruptcies`                    | Number of past bankruptcy filings.                                       |
| `Housing_Status`                  | Rental or ownership status.                                              |
| `ZIP_Code`                        | Postal code (dropped due to ethical and legal concerns).                 |
| `Default`                         | Target variable — whether the applicant defaulted (1 = Yes, 0 = No).     |

</details>
🧹 Preprocessing Steps

    Dropped Columns: Customer_ID, ZIP_Code (non-predictive or privacy-sensitive).

    Handled Missing Values using imputation strategies.

    One-Hot Encoding applied to categorical features like Loan_Purpose and Employment_Status.

    Feature Scaling used for numerical features via standardization.




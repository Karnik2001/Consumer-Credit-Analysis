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
| ' Bankruptcy'                     | whether a borrower has ever filed for bankruptcy (1) or not (0)          |
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

# ✅ Conclusion

This credit risk analysis project used a Random Forest classifier to predict the likelihood of loan default based on consumer financial and credit attributes. Key findings from the analysis include:

    Random Forest Model Performance

        The model demonstrated solid classification performance, capturing complex patterns and feature interactions without overfitting.

        Metrics such as accuracy, precision, and recall confirmed that the model is effective at identifying high-risk applicants.

    Important Predictors Identified

        Features like Credit Score, Debt-to-Income Ratio, Credit Utilization Ratio, and Delinquencies were the top contributors to predicting defaults.

        These indicators aligned with financial intuition: applicants with poor credit management or heavy debt loads are more likely to default.

    Data Preparation Was Crucial

        Categorical variables were encoded and scaled appropriately.
# 📌 Final Takeaway

The Random Forest classifier proved to be a powerful tool for modeling consumer credit risk. With accurate predictions and meaningful insights, this analysis offers a reliable framework that lenders can use to reduce default exposure and improve credit decision-making.

# Citation

https://python.plainenglish.io/building-a-credit-risk-model-a-step-by-step-guide-with-python-3e62beabfe9a

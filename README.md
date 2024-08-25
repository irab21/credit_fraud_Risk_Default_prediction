# credit_fraud_Risk_Default_prediction
The task is to develop a predictive credit risk model using a dataset that simulates credit bureau information.  The goal is to predict the loan status (default or non-default) based on the provided features.

# Business Problem: Credit Risk¶
Context

Financial institutions, such as banks and credit unions, face significant challenges in assessing credit risk when granting loans to individuals. One of the main objectives is to predict the likelihood of a customer defaulting on a loan, meaning not repaying the loan as agreed. Loan defaults can lead to considerable financial losses, affecting the profitability and stability of the financial institution. To mitigate these risks, it is essential to develop robust predictive models that can identify potential defaulters before the credit is granted. These models rely on a variety of demographic, financial, and historical customer data.

# Objective

Create a machine learning model that can accurately predict the likelihood of a customer defaulting on a loan (loan_status = 1) using the available information in the dataset.

# Dataset
The dataset contains the following columns:

person_age: Age of the person

person_income: Annual income

person_home_ownership: Type of home ownership (e.g., rent, own, etc.)

person_emp_length: Length of current employment in years

loan_intent: Loan intent (e.g., personal, educational, etc.)

loan_grade: Loan grade

loan_amnt: Loan amount

loan_int_rate: Loan interest rate

loan_status: Loan status (0 for non-default, 1 for default)

loan_percent_income: Percent of income committed to the loan

cb_person_default_on_file: Historical default (Yes or No)

cb_preson_cred_hist_length: Credit history length in years

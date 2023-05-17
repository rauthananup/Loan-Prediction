# Loan-Prediction
![loan](https://github.com/rauthananup/Loan-Prediction/assets/123797009/06d588de-ab87-4f26-b436-7340db25b83b)

# About Project
 I Have Created the Home Loan prediction Model Using Supervised Machine Learning .This notebook is designed for to solve binary classification problems using Python.
 
 # About Company
 Dream Housing Finance company deals in all home loans. They have presence across all urban, semi urban and rural areas. Customer first apply for home loan after that company validates the customer eligibility for loan.
 
 # Problem
 Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers.

# Dataset Description:
The data is provided by Kaggle and has 614 rows and 12 columns as follows :
Variable	           Description

Loan_ID	             Unique Loan ID
Gender	             Male/ Female
Married	             Applicant married (Y/N)
Dependents	         Number of dependents
Education	           Applicant Education (Graduate/ Under Graduate)
Self_Employed	       Self employed (Y/N)
ApplicantIncome	     Applicant income
CoapplicantIncome	   Coapplicant income
LoanAmount	         Loan amount in thousands
Loan_Amount_Term	   Term of loan in months
Credit_History	     credit history meets guidelines
Property_Area	       Urban/ Semi Urban/ Rural

# Approach
## 📍Task1 -> Analyze the customer 
1. Applied data pre-processing and preparation techniques in order to obtain clean data.

2. Univariate and Bivariate Analysis was done. 

3. Inisghts Obtained are as follows:
📌 Salary: Applicants with high income should have more chances of loan approval.

📌 Previous history: Applicants who have repayed their previous debts should have higher chances of loan approval.

📌 Loan amount: Loan approval should also depend on the loan amount. If the loan amount is less, chances of loan approval should be high.

📌 Loan term: Loan for less time period and less amount should have higher chances of approval.

📌 EMI: Lesser the amount to be paid monthly to repay the loan, higher the chances of loan approval.

## 📍Task2 -> Predictive behavior modeling

1. Splitting data into train and test data in 70:30 ratio.

3.  Building and training four classification models on the 80% training split: Logistic Regression, Decision Tree and Random Forest.

3. Making predictions from the model

4. Testing the performance of the model using performance metrics like Precision, Recall and F-1 score.











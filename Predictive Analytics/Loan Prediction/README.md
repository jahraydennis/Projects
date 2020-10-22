# Loan_Approval_Prediction
Predict if a loan will get approved or not.


Loan prediction is a very common real - life problem that each retail bank faces at least once in its lifetime. 
If done correctly,it can save a lot of man hours at the end of a retail bank.

# Problem Statement

## About Company
Dream Housing Finance company deals in all home loans. They have presence across all urban, semi urban and rural areas. Customers first apply for a home loan after that company validates the customer eligibility for loan.

## Problem
The company wants to automate the loan eligibility process (real time) based on customer details provided while filling the online application form. 

These details are;
**Gender
Marital Status
Education
Number of Dependents
Income
Loan Amount
Credit History, etc**

To automate this process, they have given a problem to identify the customer segments and those who are eligible for loan amounts so that they can specifically target these customers.

# Hypothesis Generation
**What are some of the factors that can possibly impact the outcome?**
- **Salary**: Applicants with high income should have more chances of loan approval
- **Previous history**: Applicants who have repaid their previous debts should have higher chances or loan approval.
- **Loan amount**: Loan approval should also depend on the loan amount. If the loan amount is less, chances of loan approval should be high.
- **Loan term**: Loan for less time period and less amount should have higher chances of approval.
- **EMI**: Lesser the amount to be paid monthly to repay the loan, the higher the chance of loan approval.

# Data Analysis
**Data Dictionary**

**Train file:** CSV ****containing the customers for whom loan eligibility is known as 'Loan_Status'

- **Variable**                 	    **Description**
- **Loan_ID:**                       	Unique Loan ID
- **Gender:**	                        Male/ Female
- **Married:**	                      Applicant married (Y/N)
- **Dependents:**	                    Number of dependents
- **Education:**	                    Applicant Education (Graduate/ Under Graduate)
- **Self_Employed:**	                Self employed (Y/N)
- **ApplicantIncome:**	              Applicant income
- **CoapplicantIncome:**	            Coapplicant income
- **LoanAmount:**	                    Loan amount in thousands
- **Loan_Amount_Term:**	              Term of loan in months
- **Credit_History:**	                credit history meets guidelines
- **Property_Area:**	                Urban/ Semi Urban/ Rural
- **Loan_Status:**                    (Target)Loan approved (Y/N)


**Test file:** CSV ****containing the customer information for whom loan eligibility is to be predicted

- **Variable**                 	    **Description**
- **Loan_ID:**                       	Unique Loan ID
- **Gender:**	                        Male/ Female
- **Married:**	                      Applicant married (Y/N)
- **Dependents:**	                    Number of dependents
- **Education:**	                    Applicant Education (Graduate/ Under Graduate)
- **Self_Employed:**	                Self employed (Y/N)
- **ApplicantIncome:**	              Applicant income
- **CoapplicantIncome:**	            Coapplicant income
- **LoanAmount:**	                    Loan amount in thousands
- **Loan_Amount_Term:**	              Term of loan in months
- **Credit_History:**	                credit history meets guidelines
- **Property_Area:**	                Urban/ Semi Urban/ Rural


**Submission file format**

- **Variable**                 	    **Description**
- **Loan_ID:**                       	Unique Loan ID
- **Loan_Status:**                    (Target)Loan approved (Y/N)


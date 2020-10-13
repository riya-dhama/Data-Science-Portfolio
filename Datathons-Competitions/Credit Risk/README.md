# Credit Risk
Predict if a loan application should be rejected or approved

## Context:
Credit risks refer to the risks of loss on a debt that occurs when the borrower fails to repay the principal and related interest amounts of a loan back to the lender on due dates.

When a bank receives a loan application, based on the applicant’s profile the bank has to make a decision for its approval or rejection. There are two types of risks associated with this decision:

- If the applicant has good credit risk, i.e. is likely to repay the loan, then rejecting the loan results in a loss to the bank
- If the applicant has bad credit risk, i.e. is unlikely to repay the loan, then approving the loan results in a loss to the bank

## Problem Statement:
Imagine a bank in your locality. The bank has realized that applying data science methodologies can help them focus their resources efficiently, make smarter decisions on credit risk calculations, and improve performance.

Earlier they used to check the credit risk of the loan applicants manually by analyzing their bank-related data, which used to take months of time. But this time they want a smart data scientist who can automate this process.

## Objective:
You are required to build a machine learning model that helps you predict the credit risk of the loan applicants.

## Evaluation Criteria:
Submissions are evaluated using Accuracy Score.

## Acknowledgement:
This data has been sourced from the UCI Machine Learning Repository.

## Structure 

### Task1: Load the Data and Import Essential Libraries
- Load the dataset using pandas.
- Import essential modules and helper functions from NumPy, Matplotlib, sklearn.
- Explore the dataframe using the head().

### Task 2: Inspect the Data
- Explore the dataframe using the shape, info() functions.
- Check the null values
- Get Statistical Overview using describe()

### Task 3: Visualize the Data(EDA)
- For this dataset, I used a histogram, correlation matrix, countplot(), piechart,  using Seaborn & Matplotlib to analyse & visualize the data

### Task 4: Data-preprocessing: 
- Handle missing values
- Log transformation of skewed data
- Handling muli-categorical features
- Drop irrelevent columns
- Convert Textual Data and Analyse the categorical variable.

### Task 5: Spliting Data into X(independent variables) and y (dependent variable)
- Spliting data to training and test set. 

### Task 6: Train the model using Diffrent Ensemble technques:
Random Forest
Gradient Boost

### Task 7: Check accuracy score on Test and Train set

### Task 8: preprocessing of Test Data and Prediction on TEST DATA 

## Conclusion :
Gradient Boost is 79% accurate to predict if a loan application should be rejected or approved

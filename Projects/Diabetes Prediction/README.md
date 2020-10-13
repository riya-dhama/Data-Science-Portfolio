# Diabetes Prediction using Machine-Learning
Predict whether a patient has diabetes or not 

## Context
- This dataset is originally from the <b> National Institute of Diabetes and Digestive and Kidney Diseases</b>. 
- Several constraints were placed on the selection of these instances from a larger database. 
- In particular, all patients here are females at least 21 years old of Pima Indian heritage.

## Objective: 
The objective of the dataset is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset.44

## About the Data:
- The datasets consists of several medical predictor variables and one target variable, Outcome. 
- Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

## Acknowledgment:
This dataset is downloaded from the <a href='https://www.kaggle.com/uciml/pima-indians-diabetes-database'> Kaggle </a>

## Structure: 

### Task 1: Load the Data and Import Libraries
- Load the dataset using pandas.
- Import essential modules and helper functions from NumPy and Matplotlib and sklearn.
- Explore the pandas dataframe using the head() and info() functions.

### Task 2: Exploratory Data Analysis:
- I used a correlation matrix, pairplot(), pointplot(), piechart using Seaborn & Matplotlib to visualize the data 
- Used pandas inbuilt functions like df.hist(), crosstab() 

### Task 3: Spliting data into X(independent features) and y(dependent feature)
- Used Feature scaling to scale the features using standrad scaler
- Split again into Train-Test split
### Task 4: Train the model using various algorithms
- K-Nearest Neighbour
- Logistic Regression
- Random Forest
- XG Boost
### Task 5: Display accuracy score, Confusion matrix, and Classification report
### Task 6: Used RandomizedSearch-CV for:
- Random Forest
- XG Boost
### Task 7: Display accuracy score, Confusion matrix, and Classification report

## Conclusion
Random Forest after applying Hyper-parameter tunning gives best result in predicting Diabetes.

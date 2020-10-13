# Survival of Patients
Predict the chances of Survival of a Patient after 1 year of treatment

## Context
A hospital in the province of Greenland has been trying to improve its care conditions by looking at historic survival of the patients. They tried looking at their data but could not identify the main factors leading to high survivals.

## Objective
The objective of the dataset is predicting the chances of Survival of a Patient after 1 year of treatment

## About the dataset
The dataset contains the patient records collected from a hospital in Greenland. The "Survived_1_year" column is a target variable which has binary entries (0 or 1).

- Survived_1_year == 0, implies that the patient did not survive after 1 year of treatment
- Survived_1_year == 1, implies that the patient survived after 1 year of treatment

## Evaluation Criteria
Submissions are evaluated using the F1 Score

## Structure:

### Task 1: Load the Data and Import Libraries
* Load the dataset using pandas.
* Import essential modules and helper functions from NumPy and Matplotlib.
* Explore the dataframe using the head().

### Task 2: Inspect the Data
* Explore the dataframe using the shape, info() functions.
* Check the null values
* Get Statistical Overview using describe()

### Task 3:  Visualize the Data(EDA)
* For this dataset, I used a histogram, correlation matrix, jointplot(), pairplot(), countplot(), boxplot()  using Seaborn & Matplotlib to visualize the data
* Pandas functions used to analyse data

### Task 4: Splitting Training Dataset into Test and Train set 
### Task 5: Train the model using Various Algorithms and Ensemble Techniques:
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boost
### Task 6: Check accuracy score on Test and Train set
### Task 7: Display Confusion Matrix and Classification Report of each Model (check F1 Score) before Hyper-parameter tuning.
### Task 8: Used  Hperparameter tuning
- Tried to increase Test set Accuracy.
- Tried to Increase F1 Score
- Display Confusion Matrix and Classification Report of Result (check F1 Score) after applying Hyper-parameter tuning.
### Task 9: Prediction on TEST DATA and Check accuracy score of each model

## Conclusion :
Gradient Boost after applying Hyper-parameter tunning gives best result in predicting the chances of Survival of a Patient after 1 year of treatment.

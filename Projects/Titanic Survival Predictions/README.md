# Titanic Survival Predictions 
Predicts Survival of Passengers

## Objective: 
Create and Train model to predict whether a given passenger survived or not

## Context:
On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.
While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

## About the dataset:
There are 1309 records and 12 attributes which are splitted in train and test set. Training set includes 819 records and 418 records are in Test Set.
The Survived column is Target Column.

## Acknoweldgment :
This dataset is taken from <a href="https://www.kaggle.com/c/titanic/data"> Kaggle </a>

## Structure of Project: 

### Task 1: Load the Data and Import Libraries
- Load the dataset using pandas.
- Import essential modules and helper functions
- Explore the dataframe using the head().

### Task 2: Inspect the Data
- Explore the dataframe using the shape, info() functions.
- Check the null values
- Get Statistical Overview using describe()

### Task 3: Visualize the Data(EDA)
- For this dataset, I used a histogram, heatmap(), catplot(), barplot(), pairplot(), factorplot(), boxplot() using Seaborn & Matplotlib to visualize the data
Pandas functions used to analyse data

### Task 4: Data-prepocessing:
- Handled Missing values
- Droped irrelevent columns
- Convert categorical data into numerical form (One-Hot Encoding/Label Emcoder)

### Task 5: Spliting Data into Dependent Variable and Independent variable 
- Then Spli the data into Train and Test Split:

### Task 6: Train the model using Various Algorithms and Ensemble Techniques:
- Logistic
- Decision Tree
- Random Forest (Ensemble technqiue)
- Gradient Boost (Ensemble technqiue)
- XG boost (Ensemble technqiue)
- KNN
- SVM
- Naive Bayes
- Ada Boost (Ensemble technqiue)
- Extra Tree (Ensemble technqiue)

### Task 7: Display Accuracy score, Confusion Matrix and Classification Report of each Model 
### Task 8: Used Grid Search-CV (Hperparameter tuning)
- Tried to increase Test set Accuracy.
- Display Accuracy score, Confusion Matrix and Classification Report of Result 

### Task 9: Prediction on TEST DATA and Check accuracy score of each model.
- Preprocess the Test data
- Prediction on Test data using each model

## Conclusion :
GradientBoost is 78.708% accurate(checked score via kaggle) in predicting survival of passengers.

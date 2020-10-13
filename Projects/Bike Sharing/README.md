# Bike Sharing 
Predict the count of Rental Bikes

## Objective
The objective of the dataset is to predict the count of rental bikes.

## About Data:
This database contains 17 attributes. The target variable refers to the count of rented bikes.

## Acknowledgement
This dataset has been sourced from the <a href="https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset">UCI-ML repository </a>

## Structure:
### Task 1: Load the Data and Import Libraries
- Load the dataset using pandas.
- Import essential modules and helper functions from NumPy and Matplotlib & sklearn.
- Explore the dataframe using the head().

### Task 2: Inspect the Data
- Explore the dataframe using the shape, info() functions.
- Check the null values
- Get Statistical Overview using describe()

### Task 3: Exploratory Data Analysis
- For this dataset, I used a histogram, correlation matrix, barplot(), lineplot(), piechart, pointplot(), scatterplot() using Seaborn & Matplotlib to visualize the data
- Used boxplot()/jointplot() to check outliers in data
- Analysis of Time-Series Data

### Task 4: Spliting Data into x(independent variables) and y(target variable)
- Split X and y to train and test set.

### Task 4: Train the model using various Techniques:
- Linear Regression
- Decision Tree 

### Task 5: Check r2_score and RMSE Value on Test and Train set
### Task 6: Visualise Result by ploting the graph of Predicted Values of Train and Test Set
### Task 5: Used Hperparameter tunning :
- Tried to reduce RMSE
- Tried to increase Test set Accuracy.
### Task 6: Prediction on TEST DATA and Check RMSE of each model

## Conclusion :
Decision Tree we achieved 98% accurate result in predicting count of rental bikes.

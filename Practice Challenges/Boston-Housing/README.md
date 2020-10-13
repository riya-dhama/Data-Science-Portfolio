# Boston-Housing
Predicting the median value of owner-occupied homes

## Objective:
The objective of the dataset is to predict the median value of owner-occupied homes in 1000 USD's

## About the Data
This database contains 14 attributes. The target variable refers to the median value of owner-occupied homes in 1000 USD's

## Evaluation Criteria
Submissions are evaluated using Root-Mean-Squared-Error (RMSE).

## Acknowledgement
- This dataset has been sourced from the Kaggle
- Dataset Link : https://www.kaggle.com/c/boston-dataset/data

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
* For this dataset, I used a histogram, correlation matrix, jointplot(), pairplot()  using Seaborn & Matplotlib to visualize the data
* Used boxplot()/jointplot() to check outliers in data

### Task 4: Splitting Training Dataset into Test and Train set 
### Task 5: Train the model using various Ensemble Techniques:
- Random Forest
- Gradient Boost
- XG Boost
### Task 6: Check accuracy and RMSE Value on Test and Train set
### Task 7: Visualise Result by ploting the graph of Predicted Values of Train and Test Set            
### Task 8: Used Hperparameter tunning  :
- Tried to reduce RMSE 
- Tried to increase Test set Accuracy.              
### Task 9: Prediction on TEST DATA and Check RMSE of each model

## Conclusion : 
XG Boost is giving least RMSE on Test data, ie It is more accurate in predicting Median value of Owner-Occupied homes.

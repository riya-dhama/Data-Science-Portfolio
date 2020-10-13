# Abalone
Determine the age of Abalone from the physical measurements

## Context:

 What is Abalon?

Abalone is a common name for any of a group of small to very large sea snails, marine gastropod molluscs in the family Haliotidae.
Other common names are ear shells, sea ears, and muttonfish or muttonshells in Australia, ormer in the UK, perlemoen in South Africa, and paua in New Zealand.

## Objective :
Objective is to determine the age of Abalone from the physical measurements.
(The age of abalone is determined by cutting the shell through the cone, staining it, and counting the number of rings through a microscope -- a boring and time-consuming task. Other measurements, which are easier to obtain, are used to predict the age.)

## Evaluation Criteria
Submissions are evaluated using Root-Mean-Squared-Error (RMSE).

## About the Data
The data set has 9 columns which have information related to physical measurements of abalones and the number of rings (representing age)

## Acknowledgement
This dataset is downloaded from the UCI Machine Learning Repository.

## Structure : 

### Task 1: Load the Data and Import Libraries
* Load the dataset using pandas.
* Import essential modules and helper functions from NumPy and Matplotlib.
* Explore the dataframe using the head().

### Task 2: Inspect the Data
* Explore the dataframe using the shape, info() functions.
* Check the null values
* Get Statistical Overview using describe()

### Task 3:  Visualize the Data(EDA) & Data-preprocessing
* For this dataset, I used a histogram, correlation matrix, pairplot()  using Seaborn & Matplotlib to visualize the data
* Convert Textual Data and Analyse the categorical variable.
* Drop irrelevent columns

### Task 4: Splitting Training Dataset into Test and Train set 
### Task 5: Train the model using RandomForest. 
-  Check accuracy and RMSE Value on Test and Train set
-  Visualise Result by ploting the graph of Predicted Values of Train and Test Set            
### Task 6: Used Hperparameter tunning in Random Forest:
- Tried to reduce RMSE 
- Tried to increase Test set Accuracy.            
### Task 7: Train the model using XG Boost 
- Check accuracy and RMSE Value on Test and Train set
- Visualise Result by ploting the graph of Predicted Values of Train and Test Set             
### Task 8: Used Hperparameter tunning in XG Boost:
- Tried to reduce RMSE 
- Tried to increase Test set Accuracy.              
### Task 9: Prediction on TEST DATA and Check RMSE of both model

## Conclusion : 
XG Boost is giving least RMSE on Test data, ie It is more accurate in predicting age of Abalone from physical measurements.

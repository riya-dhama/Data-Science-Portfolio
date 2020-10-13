# Wine Quality
Predicting the qaulity of Red Wine.

## Context 
About Wine

Wine is an alcoholic drink typically made from fermented grapes. Yeast consumes the sugar in the grapes and converts it to ethanol, carbon dioxide, and heat.
Red wine is made with darker red or black grapes, and the skins remain on the grapes during the fermentation process.

## Objective
Predict the Quality of Red Wine.

The wine connoisseurs in a wine factory in Portugal are debating on the quality of red and white wines. They thought to take the help of Data Science industry for this work. They hired you as a data scientist as you were the best data scientist in the world.

## About the dataset
The dataset is about red vinho verde wine samples, from the north of Portugal. The goal is to model wine quality based on physicochemical tests. The dataset is related to red variant of the Portuguese "Vinho Verde" wine.

## Evaluation Criteria
Submissions are evaluated using Accuracy Score.

## Reference :
Dataset Link : https://archive.ics.uci.edu/ml/datasets/wine+quality

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
- Decision Tree
- Random Forest
- Gradient Boost
- XG boost
### Task 6: Check accuracy score on Test and Train set
### Task 7: Visualise Result by ploting the graph of Predicted Values of Train and Test Set 
### Task 8: Display Confusion Matrix and Classification Report of each Model before hyper-parameter tuning.
### Task 9: Used Randomized Search-CV and Hperparameter tuning
-  Tried to increase Test set Accuracy.
- Display Confusion Matrix and Classification Report of Result after applying Hyper-parameter tuning.
### Task 10: Prediction on TEST DATA and Check accuracy score of each model

## Conclusion :
Random Forset is giving best Accuracy on Test data, ie It is more accurate in predicting Red Wine Quality.

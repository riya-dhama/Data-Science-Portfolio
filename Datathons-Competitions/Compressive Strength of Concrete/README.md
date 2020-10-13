# Compressive Strength of Concrete 
Estimate Compressive Strength of Concrete

## Context :
Concrete is the most important material in civil engineering. The concrete compressive strength is a highly nonlinear function of age and ingredients. Compressive strength or compression strength is the capacity of a material or structure to withstand loads tending to reduce the size, as opposed to which withstands loads tending to elongate. In other words, compressive strength resists being pushed together, whereas tensile strength resists tension (being pulled apart). In the study of strength of materials, tensile strength, compressive strength, and shear strength can be analyzed independently.

## Objective:
The objective is to build a machine learning model that would help Civil Engineers to estimate the compressive strength of the concrete and they can further take a decision whether the concrete should be used in their current project or not.

## About the Data :
The dataset has 9 columns which tell you different measurements related to the concrete.

## Evaluation Criteria
Submissions are evaluated using Root-Mean-Squared-Error (RMSE).

## Acknowledgement
This dataset has been sourced from the UCI Machine Learning Repository.

## Structure: 

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
### Task 5: Train the model using Diffrent Ensemble technques:
- Random Forest
- Gradient Boost
- XG Boost
### Task 6: Check accuracy and RMSE Value on Test and Train set
### Task 7: Visualise Result by ploting the graph of Predicted Values of Train and Test Set            
### Task 8: Used Hperparameter tunning , Grid-SeachCV in these model to :
- Tried to reduce RMSE 
- Tried to increase Test set Accuracy.                          
### Task 9: Prediction on TEST DATA and Check RMSE of each model

# Conclusion :
XG Boost is giving least RMSE on Test data, ie It is more accurate in Estimating compressive strength of concrete.

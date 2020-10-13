# Credit-Card-Use-Case
Application Of Descriptive Analytics in Banking

## Project Statement :

The portfolio manager of a leading consumer credit card feels his current spend acceleration strategy is not aligned with the need of his customers <b>which is a major cause of lower spends on the credit card</b>

As a first step he would like to deep dive and understanding what is the typical <b>spend pattern of the customers</b> in his portfolio. This will help him gain some initial pointer to pivot his current strategy accordingly.

The current portfolio is divided in different segments based on characteristics like Product , Payments Patterns and Customer Value and Potential.

The manager is also keen to understand in detail if the <b>spend behavior varies across these customer segments</b> which will give him some idea to the level of granularity he needs to think to come up with his revamped spend growth strategy.

## About the Dataset:
Data available for the challenge has credit card spend information for the period Jan2013 - Jun2013. It also has information on type of customer and type of card.

## Objectives :

By Visualization and Descriptive Statistics finding the major cause of lower spends on the credit card, deep dive and understanding what is the typical spend pattern of the customers in his portfolio & Checking if spend behavior varies across these customer segments

In this we are going to focus on two learning objectives:
* Find statistical summary and get some interesting insights from stats
* Apply graphical techniques used in exploratory data analysis (EDA).

## Structure :
### Task 1: Load the Data and Import Libraries
- Load the dataset using pandas.
- Import essential modules and helper functions from NumPy and Matplotlib & sklearn.
- Explore the dataframe using the head().

### Task 2: Inspect the Data
- Explore the dataframe using the shape, info() functions.
- Check the null values
- Get Statistical Overview using describe()
- Check skewness, kurtosis and range to get some idea about graph

### Task 3: Exploratory Data Analysis
- With the help of histogram, correlation matrix, barplot(), lineplot(), piechart, pointplot() using Seaborn & Matplotlib to visualize the data
- Analysis of Data with each feature

## Conclusion:
Customer who spend the Least
- Customers with wealth tag " MM "
- Customers with card_type " Blue "
- Customers from Delinquent
- Customers spend Least at Entertainment and Personal

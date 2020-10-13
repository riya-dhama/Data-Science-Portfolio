# Restaurant Reviews Analysis
Predict whether a review of the restaurant is positive or negative

## Objective:
To build a prediction model to predict whether a review of the restaurant is positive or negative

## About the data: 
- It consists of 1000 reviews on a restaurant.
- It is a Balanced Datset with 500 positive reviews and 500 negative reviews

## Acknoweldgment :
This Datset is taken from <a href='https://www.kaggle.com/hj5992/restaurantreviews'> Kaggle </a>

## Structure:
### Task 1: Load the Data and Import Essential Libraries
- Load the dataset using pandas.
- Import essential modules and helper functions from NumPy, Matplotlib, and scikit-learn.
- Explore the dataframe using the head().

### Task 2: Inspecting Data
- Explore the dataframe using the shape, info() functions.
- Check the null values
- Using pandas groupby()/value_counts() functions to check the counts of positive and negative reviews.
- Plot the pie chart for Target column

### Task 3: Pre-process the 1st review only
- Clean and Preprocess a single review then create a for loop for cleaning all 1000 reveiws

### Pre-process steps: 
- Removing Numbers and Punctuations with the help of Rgular Expressions
- Convert the string to lower 
- Download stopwords from 'nltk' library then, by list comprehension we tried to remove the stopwords 
- Use Stemming to convert word it to its Root form
- Convert list to string 
- Using Count-Vectorizer( ) : This will construct the vocabulary of the bag-of-words model and transform the sentences into sparse feature vectors

### Task 4: Pre-process each review 
### Task 5: Visual represntation of positive and negative sentiments by use of wordcloud 
### Task 6: Create Bag of words model (using count vectorizer) for all the reviews
### Task 7 : Spliting Dataset into Train and Test Set
### Task 8: Train the model using Various Algorithms
- Logistic Regression
- Naive Bayes
- Support vector classifier 

### Task 9: Display Accuracy score, Confusion Matrix and Classification report for each model( prediction on test set)
### Task 10: Prediction on Unseen Data
- Review is taken from user 
- prediction on that review.

## Conclusion: 
Naive Bayes and SVM has 77% accuracy on test dataset to predict review to be positive or negative.

# Classification

This was done as part of datacamp course : https://campus.datacamp.com/courses/supervised-learning-with-scikit-learn

First we will perform some Exploratory Data Analysis on data. 

# Datasets used: 

1. *Iris dataset*: This dataset is available in sklearn.datasets 
2. *Voting record dataset*: https://archive.ics.uci.edu/ml/datasets/Congressional+Voting+Records We have done some preliminary fix on this data so as to make it easier for this track. Updated dataset is uploaded as house-votes-84.data.txt.

# Scatter Plot 
(file: *EDA-scatter-plot-iris.ipynb*, dataset: *iris*)
	To Perform Exploratory data analysis on iris data using scatter-plot. 
	A scatter plot displays the correlation between a pair of variables. Given a set of n variables, there are n-choose-2 pairs of variables, and thus the same numbers of scatter plots.

# Seaborn Countplot 
(file:*EDA-seaborn-countplot.ipynb*, dataset: *house-votes-84.data.txt*)
	We will use Seaborn Countplot to fetch some initial analysis about data. You can read more about seaborn-countplot on link http://seaborn.pydata.org/generated/seaborn.countplot.html.

# k-Nearest-Neighbors Algorithm 
(file: *classification-knn.ipynb*, dataset: *house-votes-84.data.txt*)
	Using kNN we train model and use it to predict labels for new data. In this case we split given data into 4 parts: X_train, X_test, y_train and y_test. Using the fitted model we will predict y_predict based on how the model works with X_test, then compare the results to get accuracy score. 

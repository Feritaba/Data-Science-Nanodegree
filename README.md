# Data-Science-Nanodegree

In the first lesson (number 1 to 10 notebooks) I learned how to deal with data especially Nan values.

## A look at the data:

In this jupyter notebook I worked with dataset's rows and columns, plotting some value-count charts for each column. The dataset is a survey from StackOverflow website.

## How to break into the field:

In this jupyter notebook I used a smaller dataset and learned to have access to values correlated with other columns. Then I used the process for the bigger dataset to rename columns and plot a certain columns. At the end to answer some questions about the data I defined simple functions and showed the result in a table in order to make conclusions easier.

## Job satisfaction:

In this jupyter notebook I started to work with Nan values, some built-in methods like sum() and mean() and also grouping columns.

## What happened:

In this jupyter notebook I started with working with histogram and describe methods and answered some questions regarding the output of these two methods. Then, I learned that without cleaning the missing data (Nan) we cannot fit our data into the LinearRegression model. The process of working with missing values started from this notebook.
I also learned these steps on how to utilize our cleaned and ready data:
1. First, split the data into trains and tests.
2. Second, instansiate our linear model with normalization
3. Fit our training data into our model
4. Predict our outcome on test data.
5. Score our model on how it could predict on a new data(test data)

## Removing values:

In this jupyter notebook I learned to work with dropna() and its arguments.

## Removing data part II

In this jupyter notebook I learned to remove rows that have missing values for one of the columns. Then I tried to fit the cleaned data to the model and this time it worked but the score of the model is really low on a test data. Meaning that droping missing values might result a wrong prediction.

## Imputation methods and resources:

In this jupyter notebook I worked with mode() and mean() methods to impute the data instead of droping it from a small dataset.

## Imputing values:

In this jupyter notebook I learned that some rows need to be dropped other missing values should be filled with mean() of the values in a column. We could get a higher score from fitting our training data. But, still we see at the end of the page that the score is much lower than it should be.

## Categorical variables:

In this jupyter notebook I learned how to work with missing data in categorical columns, making dummy data and fit the fixed dataframe into our model. We see that the score increased but still is not close to what we could rely on.

## Putting it all together:

In this jupyter notebook I put together all the learnings. Cleaned the data properly(dropping, imputing, creating dummy columns for categorical variables), then fit the data into the model and plot the result with different cutoffs. If a number in cutoff list gets bigger it means we have more missing values and less features for our data. If a number in this list gets smaller, there are more features and less missing values. We would think that this would be great but in the plot we see that the result of our model on train data is getting closer to 1 and on the test data is dropping drastically. It shows having a lot of features would not cause a higher score for our model on the test data.
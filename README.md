# Data-Science-Nanodegree

In the first lesson (number 1 to 9b notebooks) I learned working with data and prepare it for fitting into our model. In the real world projects the data that we collect would not be without missing values. We want a model that predicts the correct results on a non-trained data and these values play an important role in our outcome result of our model. Ommiting the missing(Nan) values is not a promised way to a correct prediction. So, we should have a proper way to deal with the missing values. Here is the process that I worked on to get a better results from our model with wrangling the data.

## 1- A Look at the Data.ipynb:

In this jupyter notebook I worked with dataset's rows and columns, plotting some charts for each column. The dataset that I work with in this lesson is a survey from StackOverflow website.

## 2- How To Break Into the Field.ipynb:

In this jupyter notebook I used a smaller dataset and learned to have access to values correlated with other columns. Then I used the process for the bigger dataset to rename columns and plot a certain columns. At the end I answered some questions about the data defining simple functions and showing the result in a table in order to make conclusions easier.

## 3- Job Satisfaction.ipynb:

In this jupyter notebook I started to work with missing values, some built-in methods and also grouping columns.

## 4- What Happened_.ipynb:

In this jupyter notebook I started working with histogram(hist()) and describe() methods and answered some questions regarding the output of these two methods. Then, I figured out without cleaning the missing data we cannot fit our data into the LinearRegression model. The process of working with missing values started from this notebook.
I also learned these steps on how to utilize our data after cleaning:
1. First, split the data into trains and tests
2. Instansiate our linear model with normalization
3. Fit our training data into our model
4. Predict our outcome on test data
5. Score our model, how well it could predict responses on a test data

## 5- Removing Values.ipynb:

In this jupyter notebook I learned to work with dropna() and its arguments.

## 6- Removing Data Part II.ipynb:

In this jupyter notebook I learned to remove rows that have missing values. Then I tried to fit the cleaned data to the model and this time the score of the model is really low on a test data. Meaning that droping missing values might result a wrong prediction.

## 7- Imputation Methods and Resources -.ipynb:

In this jupyter notebook I worked with mode() and mean() methods to impute the data instead of droping it.

## 8- Imputing Values.ipynb:

In this jupyter notebook I learned that some rows need to be dropped and other missing values should be imputed. With these changes I got a higher score from fitting the training data. But, still we see at the end of the page that the score is much lower than it should be.

## 9a- Categorical Variables.ipynb:

In this jupyter notebook I learned how to work with missing data in categorical columns, making dummy data and fit the fixed dataframe into our model. We see that the score increased but still is not close to what we could rely on.

## 9b- Putting It All Together.ipynb:

In this jupyter notebook I put together all the learnings. Cleaned the data properly(dropping, imputing, dummy columns), then fit the data into the model and plot the result with different cutoffs. If a number in the cutoff list gets bigger it means we have more missing values and less features for our data. If a number in this list gets smaller, there are more features and less missing values. We would think that this is great but in the final plot we see that the result of our model on train data is getting closer to 1 and on the test data is dropping drastically. It shows having a lot of features would not cause a higher score for our model on the test data. In the next lesson I will learn how to fix "overfitting" the model.
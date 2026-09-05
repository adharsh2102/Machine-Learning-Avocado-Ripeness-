# Machine-Learning-Avocado-Ripeness-
## Project Overview

So basically,

I used a dataset from Kaggle with a few features of an avocado.

The dataset was converted into a DataFrame using the `pandas` module.

I imported a few other modules mainly from `sklearn`, such as
`LogisticRegression` and `train_test_split`.

The colour category column was stored as a string, but it needed to
be converted into an integer value for the machine learning model.
Therefore, I used Label Encoding.

Then, I defined `X` and `y`, where `y` is the value to predict
(ripeness), and `X` contains all the other features
(firmness, size, weight, etc.).

I used `train_test_split` to divide the dataset into training and
testing data in a 7:3 ratio.

Then, I created a Logistic Regression model and fitted it to the
training data.

After training the model, I predicted the ripeness of the avocados
in the testing data.

I used the accuracy score and classification report to compare the
predicted values with the actual values.

The accuracy score I obtained was **1.0 (100%)**.


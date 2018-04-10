# Titanic-Kaggle
Titanic Machine Learning from Disaster.

Competition Website: (http://www.kaggle.com/c/titanic-gettingStarted).

## Goal
Predict if a passenger survived the sinking of the Titanic or not. 
For each PassengerId in the test set, it predicts a 0 or 1 value for the Survived variable.


## Overview
The data has been split into two groups:
* training set (train.csv)
* test set (test.csv)

The **training set** is used to build machine learning models. For the training set, the outcome (also known as the “ground truth”) were provided for each passenger. The model will be based on “features” like passengers’ gender and class. Also using feature engineering, new new features were created.

The **test set** is be used to see how well the model performs on unseen data. For the test set, the ground truth was not provided for each passenger. It predicts these outcomes. For each passenger in the test set, the model we trained was used to predict whether or not they survived the sinking of the Titanic.

Also, **gender_submission.csv**, a set of predictions that assume all and only female passengers survive, is an example of what a submission file should look like.


## Variable Notes
**pclass**: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

**age**: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

**sibsp**: The dataset defines family relations in this way...
Sibling = brother, sister, stepbrother, stepsister
Spouse = husband, wife (mistresses and fiancés were ignored)

**parch**: The dataset defines family relations in this way...
Parent = mother, father
Child = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.


## Variable	Definition	Key
|Variable|Definition|Key|
|---------|----------|---|
|survival|Survival|	0 = No, 1 = Yes|
|pclass|Ticket class|1 = 1st, 2 = 2nd, 3 = 3rd|
|sex|Sex||
|Age|Age in years||
|sibsp|# of siblings / spouses aboard the Titanic||
|parch|# of parents / children aboard the Titanic||	
|ticket|Ticket number||
|fare|Passenger fare||
|cabin|Cabin number||
|embarked|Port of Embarkation|C = Cherbourg, Q = Queenstown, S = Southampton|

## Dependencies:
* [NumPy](http://www.numpy.org/)
* [Pandas](http://pandas.pydata.org/)
* [SciKit-Learn](http://scikit-learn.org/stable/)
* [Matplotlib](http://matplotlib.org/)

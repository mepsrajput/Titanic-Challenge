# Titanic-Challenge
Solving Titanic Challenge from Kaggle

## Overview

The data has been split into two groups:
- training set (train.csv)
- test set (test.csv)

The training set should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Your model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.

The test set should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.

We also include gender_submission.csv, a set of predictions that assume all and only female passengers survive, as an example of what a submission file should look like.

## Data Dictionary

| Variable | Definition                                 | Key                                            |
|----------|--------------------------------------------|------------------------------------------------|
| survival | Survival                                   | 0 = No, 1 = Yes                                |
| pclass   | Ticket class                               | 1 = 1st, 2 = 2nd, 3 = 3rd                      |
| sex      | Sex                                        |                                                |
| Age      | Age in years                               |                                                |
| sibsp    | # of siblings / spouses aboard the Titanic |                                                |
| parch    | # of parents / children aboard the Titanic |                                                |
| ticket   | Ticket number                              |                                                |
| fare     | Passenger fare                             |                                                |
| cabin    | Cabin number                               |                                                |
| embarked | Port of Embarkation                        | C = Cherbourg, Q = Queenstown, S = Southampton |

## Variable Notes

**pclass**: A proxy for socio-economic status (SES)
1st = Upper
2nd = Middle
3rd = Lower

**age**: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

**sibsp**: The dataset defines family relations in this way...
*Sibling* = brother, sister, stepbrother, stepsister
*Spouse* = husband, wife (mistresses and fiancés were ignored)

**parch**: The dataset defines family relations in this way...
*Parent* = mother, father
*Child* = daughter, son, stepdaughter, stepson
Some children travelled only with a nanny, therefore parch=0 for them.

## File Structure

+ **README.md**	- Details of the challenge and solution
+ **Titanic Challenge.ipynb**	- Final Submitted Challenge Code
+ **gender_submission.csv**	- A set of predictions that assume all and only female passengers survive
+ **submission.csv**	- Predicted Data
+ **test.csv**	- CSV File which contain the test data that need to be used for testing the trained Model
+ **train.csv** - CSV File which contain the data that needs to be trained

## How to solve the Challenge
- The data present in the **train.csv** needs to be trained by using the apropriate algorithm and then **test.csv** needs to be tested to predict the values.
- The Aim is to predict the survivors in the Titanic Incident based on various properties associated with the passengers.

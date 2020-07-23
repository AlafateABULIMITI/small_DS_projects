# Overview

The data has been split into two groups:

- *training set (train.csv)*
- *test set (test.csv)*

The training set should be used to build your machine learning models. For the training set, we provide the outcome (also known as the “ground truth”) for each passenger. Your model will be based on “features” like passengers’ gender and class. You can also use feature engineering to create new features.

The test set should be used to see how well your model performs on unseen data. For the test set, we do not provide the ground truth for each passenger. It is your job to predict these outcomes. For each passenger in the test set, use the model you trained to predict whether or not they survived the sinking of the Titanic.

We also include *gender_submission.csv*, a set of predictions that assume all and only female passengers survive, as an example of what a submission file should look like.

Below is a brief information about each columns of the dataset:

- PassengerId: An unique index for passenger rows. It starts from 1 for first row and increments by 1 for every new rows.
- Survived: Shows if the passenger survived or not. 1 stands for survived and 0 stands for not survived.
- Pclass: Ticket class. 1 stands for First class ticket. 2 stands for Second class ticket. 3 stands for Third class ticket.
- Name: Passenger's name. Name also contain title. "Mr" for man. "Mrs" for woman. "Miss" for girl. "Master" for boy.
- Sex: Passenger's sex. It's either Male or Female.
- Age: Passenger's age. "NaN" values in this column indicates that the age of that particular passenger has not been recorded.
- SibSp: Number of siblings or spouses travelling with each passenger.
- Parch: Number of parents of children travelling with each passenger.
- Ticket: Ticket number.
- Fare: How much money the passenger has paid for the travel journey.
- Cabin: Cabin number of the passenger. "NaN" values in this column indicates that the cabin number of that particular passenger has not been recorded.
- Embarked: Port from where the particular passenger was embarked/boarded.

# Oblig 2

## Task

1. Create a model that predicts a the age of a passenger on the titanic based on the features in the dataset. 
2. Validate the model on test_data. The model _should_ have a RMSE (root mean squared error) of 15 or less when validating on test_data. The RMSE score of the model on train_data is not important.

## Disclaimers

The model _must_ be trained exclusively on train_data.csv. test_data.csv should _only_ used for validation, and you are not allowed to use test_data.csv for the model creation.

You can assume that test_data.csv is clean, train_data, however, is not. You should clean the data before training the model.

Hyperparameter optimalization is nice, and will give you a better model, but data cleaning is always the most important part of a machine learning project.

## Feature explanation

### X
- PassengerId: Unique id for each passenger
- Survived: 0 = No, 1 = Yes
- Pclass: Ticket class
- Sex: sex of the passenger
- SibSp: # of siblings / spouses aboard the Titanic
- Parch: # of parents / children aboard the Titanic
- Ticket: Ticket number
- Fare: Passenger fare
- Cabin: Cabin number (-1 means no data on cabin)
- Embarked: Port of Embarkation

### Y
- Age: Age in years


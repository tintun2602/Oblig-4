# Oblig 2

## Task

1. Create a model that predicts a the age of a passenger on the titanic based on the other features in the dataset. 
2. Validate the model on test_data. The model _must_ have a RMSE (root mean squared error) of less than 15 on test_data. 

## Disclaimers

The model _must_ be trained exclusively on train_data, test_data is only used for validation, and is not allowed to be used for model the model creation.

You can assume that test_data.csv is clean, train_data, however, is not. You should clean the data before training the model.


## Feature explanation

- PassengerId: Unique id for each passenger
- Survived: 0 = No, 1 = Yes
- Pclass: Ticket class 1 = 1st, 2 = 2nd, 3 = 3rd
- Sex: sex of the passenger
- SibSp: # of siblings / spouses aboard the Titanic
- Parch: # of parents / children aboard the Titanic
- Ticket: Ticket number
- Fare: Passenger fare
- Cabin: Cabin number (-1 means no data on cabin)
- Embarked: Port of Embarkation
- Age: Age in years

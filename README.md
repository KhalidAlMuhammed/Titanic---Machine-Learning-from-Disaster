# Titanic Survival Prediction - Machine Learning from Disaster

## Project Overview
This project involves building a predictive model that determines whether a passenger survived the Titanic disaster. The model is trained on a dataset containing various features of the passengers such as age, sex, ticket class, etc. The goal is to predict survival status with high accuracy, as evaluated on a separate test dataset.

## Dataset
The dataset used in this project is split into two parts:
- `train.csv`: Contains the details of a subset of the passengers on board (891 entries) and whether they survived or not. This data is used to train the model.
- `test.csv`: Contains the details of another subset of passengers (418 entries). This data is used to test the model's predictions.

The `gender_submission.csv` file provides a sample of the expected format for submissions to a competition platform.

## Features
The dataset contains several features that are informative for predicting survival:
- **PassengerId**: An id given to each traveler on the boat.
- **Pclass**: The passenger class. It has three possible values: 1,2,3 (1st, 2nd and 3rd classes).
- **Name**: The name of the passenger.
- **Sex**: The gender of the passenger.
- **Age**: The age of the passenger.
- **SibSp**: The number of siblings and spouses the passenger had on board.
- **Parch**: The number of parents and children the passenger had on board.
- **Ticket**: The ticket number.
- **Fare**: The amount of money spent on their ticket.
- **Cabin**: The passenger's cabin number.
- **Embarked**: The port where the passenger embarked the Titanic.

## Model
The model used for predicting the survival of passengers is outlined in `model.ipynb`. The notebook includes data preprocessing, exploratory data analysis, model selection, and training procedures.

## Evaluation
The model's performance is evaluated based on the accuracy of the predictions it makes on the test data. Accuracy is defined as the percentage of passengers correctly predicted.

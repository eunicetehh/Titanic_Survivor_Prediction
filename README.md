# Titanic_Survivor_Prediction

## Overview
This repository contains an analysis of the Titanic dataset obtained from Kaggle. The dataset provides information about passengers aboard the Titanic, including various attributes such as age, gender, ticket class, and survival status.

## Dataset Description
- **Source:** [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)
- **Description:** The dataset includes two CSV files: `train.csv` and `test.csv`. 
  - `train.csv`: Contains data on a subset of the Titanic passengers, along with the information on whether they survived or not.
  - `test.csv`: Contains similar information but does not disclose the survival status. This dataset is used for model evaluation.

### Data Card
| Column        | Description                                            |
|---------------|--------------------------------------------------------|
| PassengerId   | Unique identifier for each passenger                   |
| Survived      | Survival status (0 = No, 1 = Yes)                      |
| Pclass        | Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)               |
| Name          | Passenger's name                                       |
| Sex           | Passenger's sex                                        |
| Age           | Passenger's age                                        |
| SibSp         | Number of siblings/spouses aboard the Titanic          |
| Parch         | Number of parents/children aboard the Titanic          |
| Ticket        | Ticket number                                          |
| Fare          | Passenger fare                                         |
| Cabin         | Cabin number                                           |
| Embarked      | Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton) |

## Model Used
- **Model:** Random Forest Classifier
- **Accuracy Score:** 0.8071748878923767

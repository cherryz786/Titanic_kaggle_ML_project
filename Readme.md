# Titanic Machine Learning Project

![titanic](https://github.com/ishikawa-yui/Titanic_kaggle_ML_project/assets/71602299/7ab0f30d-5f56-4d76-b40d-27d27ecd5518)


This repository contains the code and data for my Titanic Machine Learning project, which is based on the famous Kaggle competition "Titanic: Machine Learning from Disaster". The goal of this project is to predict the survival of passengers aboard the Titanic based on various features like age, sex, ticket class, etc.

## About the Kaggle Competition

The "Titanic: Machine Learning from Disaster" competition on Kaggle is one of the most popular introductory machine learning competitions. The dataset used in this competition contains information about passengers on the Titanic, including whether they survived or not. The challenge is to build a predictive model that can accurately determine if a given passenger survived or not.

## Data Description

The dataset contains the following variables:

- **Survival**: Survival (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Sex**: Sex of the passenger
- **Age**: Age in years (fractional if less than 1, in the form of xx.5 if estimated)
- **SibSp**: Number of siblings / spouses aboard the Titanic
- **Parch**: Number of parents / children aboard the Titanic
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Cabin**: Cabin number
- **Embarked**: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

### Variable Notes

- **Pclass**: A proxy for socio-economic status (SES)
  - 1st = Upper
  - 2nd = Middle
  - 3rd = Lower

- **Age**: Age is fractional if less than 1. If the age is estimated, it is in the form of xx.5.

- **SibSp**: The dataset defines family relations in this way...
  - Sibling = brother, sister, stepbrother, stepsister
  - Spouse = husband, wife (mistresses and fiancés were ignored)

- **Parch**: The dataset defines family relations in this way...
  - Parent = mother, father
  - Child = daughter, son, stepdaughter, stepson
  - Some children travelled only with a nanny, therefore parch=0 for them.

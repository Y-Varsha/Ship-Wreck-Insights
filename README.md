
# ShipwreckInsights

## Overview

**ShipwreckInsights** is a machine learning project that predicts the survival chances of passengers on the Titanic based on various features like age, gender, class, and more. This project is built using Python and popular libraries such as Pandas, Scikit-learn.

## Table of Contents
- [Data](#data)
- [Features](#features)
- [Modeling](#modeling)
- [Results](#results)

## Data

The dataset used in this project is sourced from the [Kaggle Titanic dataset]((https://www.kaggle.com/competitions/titanic/data)). It contains information about the passengers, such as:

- PassengerId: A unique identifier for each passenger.
- Pclass: Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd).
- Name: Name of the passenger.
- Sex: Gender of the passenger.
- Age: Age of the passenger.
- SibSp: Number of siblings/spouses aboard the Titanic.
- Parch: Number of parents/children aboard the Titanic.
- Ticket: Ticket number.
- Fare: Amount of money paid for the ticket.
- Cabin: Cabin number.
- Embarked: Port of embarkation (C = Cherbourg; Q = Queenstown; S = Southampton).

## Features

For this project, the following features were considered:

- **Pclass**: Socio-economic status (1st, 2nd, 3rd class).
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **Fare**: The fare paid by the passenger.
- **Embarked**: The port from which the passenger embarked.

Feature engineering and data preprocessing steps, such as handling missing values and creating new features, are discussed in the notebook.

## Models Used

In this project, several machine learning models were explored to predict passenger survival on the Titanic. The models used include:

- **Logistic Regression**: A linear model for binary classification that estimates the probability of a binary outcome using the logistic function.
- **KNeighbors Classifier**: A non-parametric method that classifies data points based on the majority vote of their nearest neighbors.
- **Random Forest Classifier**: An ensemble learning method that operates by constructing multiple decision trees and outputting the class that is the mode of the classes of the individual trees.
- **Gaussian Naive Bayes**: A probabilistic classifier based on applying Bayes' theorem with the assumption of independence between features. It is particularly effective when the feature distributions are Gaussian.
- **Multinomial Naive Bayes**: A variant of Naive Bayes used for classification with discrete features, especially suitable for text data.
- **Bernoulli Naive Bayes**: Another variant of Naive Bayes designed for binary/boolean features, often used for text classification tasks.
- **Decision Tree Classifier**: A model that uses a tree-like graph of decisions and their possible consequences to perform classification.

Each of these models was evaluated to determine which provided the best performance in predicting survival rates, with considerations of accuracy.

## Results

Key findings from the project include:

- Women and children had a higher survival rate.
- Passengers in 1st class were more likely to survive.
- The port of embarkation also played a role in survival chances.

These insights are visualized using various plots and graphs in the Analysis notebook.

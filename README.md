---Titanic Data Analysis & Feature Engineering

This project focuses on Exploratory Data Analysis (EDA) and Feature Engineering on the Titanic dataset to understand patterns and prepare data for machine learning.

Project Objective
Analyze passenger data to find patterns affecting survival
Clean and preprocess the dataset
Transform raw data into meaningful features for future modeling

Dataset
Source: Kaggle Titanic Dataset
File used:
train.csv

Features:
PassengerId
Pclass
Name
Sex
Age
SibSp
Parch
Fare
Embarked
Survived (target variable)

Exploratory Data Analysis (EDA)
Checked missing values in Age, Embarked, Cabin
Analyzed survival distribution
Studied relationships:
Survival vs Gender
Survival vs Passenger Class

Used correlation matrix for numerical features

Feature Engineering:
Dropped irrelevant columns:
PassengerId

Encoding:
Sex → Mapping
Embarked → One-Hot Encoding

Feature scaling:
Applied scaling to numerical columns like Age, Fare

Project Structure:

├── Titanic_survival.ipynb
├── train.csv
├── README.md

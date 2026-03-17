# EDA-Exploratory-Data-Analysis-
Titanic Dataset Exploratory Data Analysis (EDA)
Overview

This project presents a comprehensive Exploratory Data Analysis (EDA) of the Titanic dataset (Titanic-Dataset.csv), performed using Python in Google Colab. The Titanic dataset is a well-known dataset in the field of data science, containing detailed information about passengers aboard the RMS Titanic.

The primary aim of this project is to analyze the dataset, identify patterns, handle missing data, and extract meaningful insights related to passenger survival. This analysis serves as a foundational step toward building predictive machine learning models.

Dataset Description

The dataset used in this project is Titanic-Dataset.csv, which includes demographic and travel-related information of passengers.

Dataset Features
Column Name	Description
PassengerId	Unique identifier assigned to each passenger
Survived	Survival status (0 = Did not survive, 1 = Survived)
Pclass	Passenger class (1 = First Class, 2 = Second Class, 3 = Third Class)
Name	Full name of the passenger
Sex	Gender of the passenger
Age	Age of the passenger
SibSp	Number of siblings or spouses aboard
Parch	Number of parents or children aboard
Ticket	Ticket number
Fare	Ticket fare paid by the passenger
Cabin	Cabin number
Embarked	Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
Objectives

The key objectives of this project include:

Performing data cleaning and preprocessing

Handling missing and inconsistent data

Conducting univariate and bivariate analysis

Identifying patterns and relationships between variables

Understanding key factors influencing passenger survival

Tools and Technologies

Python

Pandas

NumPy

Matplotlib

Seaborn

Google Colab

Methodology

The analysis was conducted through the following structured steps:

Data loading and initial inspection to understand dataset structure

Identification and handling of missing values in relevant columns

Data cleaning and preparation for analysis

Univariate analysis to study individual feature distributions

Bivariate analysis to explore relationships between features and survival

Visualization of patterns using statistical plots and charts

Key Insights

The exploratory analysis revealed several important findings:

Female passengers had a significantly higher survival rate compared to male passengers

Passengers traveling in first class had better survival probabilities than those in lower classes

Socio-economic factors such as class and fare played a major role in survival outcomes

Younger passengers showed relatively higher chances of survival

Missing data in certain features required appropriate handling to ensure accurate analysis

Project Structure
Titanic-EDA
│
├── Titanic-Dataset.csv
├── titanic_eda.ipynb
└── README.md
Results and Discussion

The analysis provides a clear understanding of the dataset and highlights the major factors influencing survival during the Titanic disaster. These findings form a strong basis for further predictive modeling and machine learning applications.

Future Work

Future enhancements to this project may include:

Advanced feature engineering

Implementation of classification algorithms for survival prediction

Model evaluation and performance comparison

Hyperparameter tuning for improved accuracy

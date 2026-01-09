📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Insurance dataset to understand the factors that influence medical insurance charges.
The analysis helps uncover patterns, relationships, and insights that can later support machine learning model building.

📁 Dataset Description

The dataset contains information about individuals and their insurance-related attributes.

🔹 Columns
Column	Description
age	Age of the individual
sex	Gender (male/female)
bmi	Body Mass Index
children	Number of dependent children
smoker	Smoking status
region	Residential region
charges	Medical insurance cost (target variable)
🧪 EDA Steps Performed
1️⃣ Data Understanding

Loaded dataset and checked shape

Inspected column names and data types

Identified numerical and categorical features

2️⃣ Data Cleaning

Handled categorical variables using one-hot encoding

Converted boolean values (True/False) to numeric (1/0)

Ensured dataset was ML-ready

3️⃣ Univariate Analysis

Distribution analysis using histograms & KDE plots

Checked skewness in numerical features

Observed spread and central tendency

4️⃣ Bivariate Analysis

Relationship between features and insurance charges

Impact of:

Smoking status

Age

BMI

Used correlation analysis

5️⃣ Feature Engineering

Standardized continuous variables using StandardScaler

Converted categorical features into numerical format

6️⃣ Feature Selection

Applied Pearson Correlation

Retained features strongly correlated with charges

Removed weak and redundant features

📈 Key Insights

Smoking status has the strongest impact on insurance charges

Age and BMI show moderate positive correlation with charges

Non-smokers have significantly lower medical expenses

Region has minimal influence on insurance cost

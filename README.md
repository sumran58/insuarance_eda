Insurance Cost Analysis using Exploratory Data Analysis & Linear Regression

This project focuses on performing Exploratory Data Analysis (EDA) on an Insurance dataset to identify key factors influencing medical insurance charges and to build a Linear Regression model for cost prediction.

📁 Dataset Overview

The dataset contains demographic and lifestyle attributes of individuals along with their medical insurance costs.

Key Features:

age – Age of the individual

sex – Gender (male/female)

bmi – Body Mass Index

children – Number of dependent children

smoker – Smoking status

region – Residential region

charges – Medical insurance cost (target variable)

🧪 EDA & Modeling Workflow
1️⃣ Data Understanding

Loaded and inspected the dataset structure and dimensions

Identified numerical and categorical variables

Verified data types and target variable

2️⃣ Data Cleaning & Preprocessing

Applied one-hot encoding to categorical variables

Converted boolean values (True/False) into numeric format (1/0)

Prepared the dataset for machine learning models

3️⃣ Univariate Analysis

Analyzed feature distributions using histograms and KDE plots

Examined skewness, spread, and central tendency of numerical variables

4️⃣ Bivariate Analysis

Studied relationships between independent variables and insurance charges

Analyzed the impact of:

Smoking status

Age

BMI

Used correlation analysis to identify influential features

5️⃣ Feature Engineering

Standardized continuous features using StandardScaler

Converted all categorical variables into numerical representations

6️⃣ Feature Selection

Applied Pearson Correlation analysis

Retained features with strong correlation to insurance charges

Removed weak and redundant features

🤖 Model Building & Evaluation

Built a Linear Regression model to predict medical insurance charges

Evaluated model performance using:

R² Score: 0.80

Adjusted R² Score: 0.79

These results indicate that the model explains approximately 80% of the variance in insurance charges, demonstrating strong predictive capability.

📈 Key Insights

Smoking status has the strongest impact on insurance charges

Age and BMI show a moderate positive correlation with medical costs

Non-smokers incur significantly lower medical expenses compared to smokers

Region has minimal influence on insurance charges

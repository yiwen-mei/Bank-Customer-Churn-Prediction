# Bank-Customer-Churn-Prediction

## Introduction

This project aims at leveraging advanced machine learning models to predict customer churn for a bank. By analyzing a dataset that encapsulates a wide range of customer attributes, the project seeks to identify customer churn which may be helpful for future retention strategies formulation.

## Objectives

- **Data Preprocessing**: Prepare the bank's customer dataset for machine learning analysis, including normalization, handling missing values, and encoding categorical variables.
- **Model Implementation**: Utilize a variety of machine learning models, including Random Forest, Gradient Boosting, and Logistic Regression, find the best model to predict customer churn.


## Data Source

The analysis utilizes the `BankChurners.csv` dataset, featuring customer-related data such as demographics, account details, and financial behaviors. Key attributes include:
- **Demographics**: Age, Gender, Marital Status, Education Level.
- **Account Information**: Card Category, Number of Dependents.
- **Financial Behaviors**: Monthly Transaction Volume, Changes in Transaction Amount, Total Transaction Amount.
- **Engagement Metrics**: Months on Book, Inactive Months, Contact Count.

## Tools and Technologies Used

- **Programming Language**: Python
- **IDE**: Jupyter Notebook
- **Libraries**: pandas, scikit-learn, matplotlib, seaborn

## Results

This project successfully identified the Gradient Boosting Classifier as the most effective model (96.3% accuracy rate) for predicting customer churn. The findings of this project are instrumental for the bank in formulating data-driven strategies to enhance customer retention and loyalty, ultimately contributing to the bank's overarching goal of long-term customer relationship management.


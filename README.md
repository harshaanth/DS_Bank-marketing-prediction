# Bank Marketing Prediction

## Overview
This project focuses on analyzing and preprocessing data related to direct marketing campaigns (via phone calls) of a Portuguese banking institution. The primary objective is to predict whether a client will subscribe to a term deposit (variable `y`).

## Project Highlights
- **Data Preprocessing:** Handling missing values, encoding categorical variables, and feature engineering.
- **Exploratory Data Analysis (EDA):** Visualizing the data distribution and relationships between features.
- **Prediction Goal:** Preparing the dataset for potential machine learning models to predict term deposit subscriptions.

## Dataset
The dataset used in this project is sourced from the UCI Machine Learning Repository. It includes various attributes related to the bank's clients, their interactions during the marketing campaign, and the outcome of previous campaigns.

- **Source:** [UCI Bank Marketing Dataset](http://archive.ics.uci.edu/ml/datasets/Bank+Marketing)
- **Attributes:**
    - **Bank client data:** Age, Job, Marital Status, Education, Default, Housing Loan, Personal Loan
    - **Last contact of the campaign:** Contact type, Month, Duration
    - **Other attributes:** Number of contacts, Days passed since last contact, Outcome of the previous campaign
    - **Output variable:** `y` - Whether the client subscribed to a term deposit (Yes/No)

## Technologies Used
- **Python:** The primary language used for data analysis and preprocessing.
- **Pandas:** For data manipulation and analysis.
- **NumPy:** For numerical computations.
- **Matplotlib & Seaborn:** For data visualization.
- **Scikit-learn:** For potential machine learning model building.
- **Google Colab:** To run the notebook in an online environment.

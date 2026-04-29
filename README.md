# Online Advertisement Click Prediction


## Project Notebook

Click here to view the notebook:  
[Open Notebook](https://github.com/elizaliva/data-mining-project/blob/main/DataMining_Project_Template_Spring_2026_Final.ipynb)

## Project Overview
This project focuses on predicting whether a user will click on an online advertisement (is_click). The dataset includes user demographics, product information, and campaign details. The goal is to build and evaluate machine learning models to predict user click behavior.

The project includes exploratory data analysis (EDA), data preprocessing, and model training using different algorithms.

## Dataset
The dataset contains information about users, products, and advertisement campaigns. It includes both numerical and categorical features such as:
- User demographics (age_level, gender, user_depth)
- Product categories
- Campaign and webpage information

The target variable is:
- **is_click** (1 = clicked, 0 = not clicked)

## Exploratory Data Analysis
AutoViz was used to explore the dataset and identify patterns.

Key findings:
- The target variable is imbalanced (most users do not click ads)
- Some features have many missing values (e.g., product_category_2)
- There are duplicate rows and outliers in some features
- The dataset contains both numerical and categorical variables
The trained model file (`final_model.pkl`) is not included due to GitHub file size limits.

## Models
The following machine learning models were used:
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors

Hyperparameter tuning was performed using GridSearchCV.

## Conclusion
This project demonstrated how exploratory data analysis and preprocessing are essential steps before building machine learning models. The results show that handling imbalanced data and missing values is critical for improving model performance.

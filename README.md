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
- The dataset contains both numerical and categorical variables
- The model achieved 79% accuracy, but performance on click prediction is weak (F1: 0.12, Precision: 0.08, Recall: 0.21). This indicates the model is biased toward predicting non-clicks due to class imbalance.
- Feature importance shows that timing (hour, day) is more influential than user characteristics.

## Recommendations
- Optimize ad timing to focus on high-engagement periods
- Improve model performance using class balancing and better algorithms (e.g., XGBoost)
- Focus on precision & recall, not just accuracy
- Reduce wasted ad spend by improving click prediction

## Models
The following machine learning models were used:
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors

Hyperparameter tuning was performed using GridSearchCV.

## Conclusion

This project demonstrates the importance of data preprocessing and handling class imbalance in real-world machine learning problems. 

While the model achieved strong overall accuracy, it struggled to identify actual clicks due to the highly imbalanced dataset. This highlights the need to focus on metrics such as precision, recall, and F1-score rather than accuracy alone.

## Future improvements

Future improvements should focus on better handling class imbalance and exploring more advanced models. Additionally, researching and incorporating alternative datasets—potentially smaller but more balanced and focused on a specific type of advertisement—could provide deeper insights into customer behavior and improve prediction performance.

## Notes

The trained model file (final_model.pkl) is not included due to GitHub file size limits.

# Phase3_Modeling_Project
## A data driven project on customer churn rate at SyriaTel
SyriaTel is a telecommunication company that offers services to various customers. The company would like to reduce its loses by predicting how soon a customer will stop doing business with SyriaTel.

This project attempts to help SyriaTel reduce its loses by creating a model that will be used in predicting churn rate.

## Tech Stack
- Python
- Pandas
- Matplotlb
- Seaborn
- Scikit-Learn
## Objectives
- Engineer a binary target variable (churn) based on all the other features in the dataset apart form phone number.
- Train a classification model that categorises customers based on their loyalty to SyriaTel.
- Optimize the model's performance using feature engineering and hyperparemeter tuning.

## Data Analysis
For modeling feature and target data was gotten from data on SyriaTel's customers. Data was cleaned, analysed and categorical data was encoded through one hot encoding.
## Modeling
For this project, 6 models were trained. They include:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine(SVM)
- Naive Bayes
- XG Boost
## Conclusion/Next Steps
The XGBoost model is the best performing model for predicting customer churn, with a high accuracy of 97%.With this model SyriaTel can achieve the following;
- Focus on high risk customers.
- Optimise customer service interactions
- Reduce false alarms in identifying churners.
- Improvng its products or services using churn patterns.
- Personalised marketing efforts through creating tailored promotions

There was a class imbalance with the number of churned customers and loyal customers, so during train-test splits smaller sample categories could all be included in either the training set or testing set.

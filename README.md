# Churn Prediction Project

## Project Overview

This project focuses on predicting user churn for a service using machine learning techniques. By analyzing user behavior and engagement metrics, the project aims to identify users who are at risk of discontinuing their subscription, allowing the company to implement targeted retention strategies.

This project is part of the Google Advanced Data Analytics Professional Certificate on Coursera. It demonstrates the application of advanced data analysis and machine learning techniques to real-world problems.

## Dataset Description

The dataset comprises various features related to user activity and characteristics:

- **user_id**: A unique identifier assigned to each user.
- **user_engagement**: Metrics reflecting the user's activity levels on the platform.
- **user_duration**: The length of time the user has been active or subscribed.
- **user_interactions**: The number of interactions (e.g., likes, comments) performed by the user.
- **user_last_login**: The most recent date and time the user logged in.
- **user_plan**: The subscription plan chosen by the user (e.g., Basic, Premium).
- **user_age**: The age of the user.
- **user_location**: The geographical location of the user.
- **churn_status**: A binary target variable indicating whether the user has churned (1) or not (0).

## Data Processing

- **Feature Engineering**: Developed new features and transformed existing ones to enhance model performance. This included encoding categorical variables and normalizing numerical features.
- **Data Cleaning**: Addressed missing values and outliers to prepare the dataset for modeling.
- **Preprocessing**: Scaled features and performed encoding to ensure compatibility with machine learning algorithms.

## Modeling Techniques

- **Random Forest**: An ensemble learning method that combines multiple decision trees to improve prediction accuracy.
- **XGBoost**: A powerful boosting technique that builds models sequentially to correct previous errors.
- **Deep Learning**: Employed a neural network model with hyperparameter optimization to capture complex patterns in the data.

## Results

- **Best Performing Model**: XGBoost
  - **Threshold for Prediction**: 0.194
- **Evaluation Metrics**:
  - **Recall**: 0.552 — Effectiveness in identifying churned users.
  - **Precision**: 0.33 — Proportion of predicted churns that were actual churns.
  - **F1-Score**: 0.41 — Balance between precision and recall.
  - **Accuracy**: 0.72 — Overall correctness of the model's predictions.
- **Key Features**: Engagement metrics, such as interaction counts and subscription plan types, were significant predictors of churn.

## Key Insights

- **Engagement Levels**: High levels of user interaction and engagement are crucial indicators of churn risk.
- **Subscription Plans**: Different subscription plans impact the likelihood of user retention.

## Next Steps

- **Enhance Model Performance**: Investigate additional features and advanced techniques to further improve model accuracy.
- **Expand Dataset**: Collect more comprehensive user data to strengthen the model's predictive capabilities.
- **Refine Features**: Continue to develop and test new features to boost model performance.
- **Deployment and Monitoring**: Explore deploying the model into a live environment and establish monitoring to track its performance.
- **Further Analysis**: Conduct more exploratory data analysis to uncover deeper insights and refine feature selection.


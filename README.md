# Customer Churn Prediction Project 📡 📞
## Project Overview
The Customer Churn Prediction project aims to analyze patterns and behaviors of customers that are most likely to stop using a service or leave a company, helping businesses understand and act on these trends. By leveraging machine learning techniques and exploratory data analysis (EDA), this project seeks to predict the likelihood of customer churn based on several factors such as demographics, service usage, and customer interactions.
## Objective
The main objective of this project is to build a predictive model to identify customers who are at a high risk of churning. This helps the company target retention strategies more effectively, reducing the churn rate and increasing customer satisfaction.
## Problem Statement
Customer churn is one of the major challenges faced by companies today. It costs businesses more to acquire new customers than to retain existing ones, so accurately predicting which customers are at risk of leaving becomes critical. By understanding why and when a customer might churn, businesses can implement preventive measures, create targeted marketing campaigns, and improve customer loyalty.
## Dataset
The dataset used for this project includes customer information such as:
- Demographic details (age, gender, income, etc.)
- Account details (contract type, service tenure)
- Service usage details (internet service, monthly charges, etc.)
- Customer interaction records (number of calls, service complaints, etc.)
The data includes both active customers and those who have churned. It’s important to differentiate between these two categories and identify features that can contribute to better churn predictions.
## Exploratory Data Analysis (EDA)
EDA helps us gain an initial understanding of the dataset, identify trends, and figure out the important variables influencing customer churn. Key steps in the EDA included:
### Data Cleaning:
- Handled missing values and corrected data types.
- Removed any irrelevant features.
- Created new features that could add value, such as customer tenure and service usage patterns.
### Visualization:
- Used matplotlib and seaborn to visualize the relationships between features and the churn variable.
- Key insights were gathered from bar charts, box plots, and histograms to show the distribution of data.
## Example insights include:
### Contract type:
- Customers with month-to-month contracts have a higher churn rate compared to those with long-term contracts.
### Charges:
- Higher monthly charges tend to correlate with a higher churn rate.
### Tenure:
- Customers with a longer tenure are less likely to churn.
## Feature Engineering
Feature engineering is a crucial part of the project, ensuring that relevant features are optimized for the model. The following features were derived from the dataset:
### Tenure buckets:
- Grouping customers based on their tenure (e.g., 0–12 months, 13–24 months, etc.)
### TotalCharges:
- Created new features such as "Average Monthly Charges" by dividing TotalCharges by tenure.
### Contract length:
- Transformed categorical variables into numerical ones for the model.
## Modeling
Several machine learning algorithms were implemented and compared to predict customer churn. The following steps were followed:
### Train-Test Split:
The dataset was split into training and test sets to evaluate model performance effectively.

## Model Selection:

### Logistic Regression:
- Used as a baseline for classification.
### Decision Trees:
- Built to capture complex non-linear relationships.
### Random Forest:
- Used to improve performance by combining multiple decision trees.
### XGBoost:
- Applied for better accuracy and to handle feature importance.
## Evaluation Metrics:
- Accuracy, Precision, Recall, and F1-Score were used to evaluate model performance.
- ROC-AUC score was used to measure the model’s ability to distinguish between churners and non-churners.
## Hyperparameter Tuning:
- Performed grid search for fine-tuning models and improving accuracy.
## Insights and Results
### Overall Churn rate:
- Approximately 26.5% of users are about to churn based on the dataset.
### Churn by contract Type:
- Customers with month-to-month contracts are the most likely to churn.
### Churn by Service Features:
- Internet service features like high-speed data significantly impact churn rates.
### Churn by Tenure:
- Longer-tenured customers are less likely to churn, making tenure a strong predictor.
### Churn by Internet Service:
- Fiber optic service has lower churn rates.
### Churn by Demographic Insights:
- Customers in the age group of 25-34 have a higher churn rate, while customers over 50 years old are less likely to churn.
### Churn by Payment Method:
- Customers who pay using electronic checks tend to have a higher churn rate compared to those using credit cards or automatic bank transfers.
## Retention Strategies:
Based on the insights, suggestions for improving customer retention could be:

- Offering discounts to customers on month-to-month contracts to encourage them to move to long-term plans.
- Targeting younger customers with loyalty rewards to increase retention.
- Offering specialized customer support for customers identified as at-risk to address their concerns.

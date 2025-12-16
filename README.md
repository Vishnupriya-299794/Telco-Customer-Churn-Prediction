# Telco Customer Churn Prediction

#  Project Overview

Customer churn is a critical challenge for subscription based businesses such as telecom companies. Retaining existing customers is significantly more cost-effective than acquiring new ones. This project focuses on building an end-to-end machine learning solution to predict whether a customer is likely to churn, enabling businesses to take proactive retention measures.

#  Business Objective

The primary goal of this project is to:
1. Predict customer churn using historical customer data
2. Identify key factors that influence churn
3. Provide actionable insights that can help reduce customer attrition

#  Dataset Description

The dataset contains customer-level information including:
a) Demographics (e.g., SeniorCitizen)
b) Account information (tenure, billing details)
c) Service usage details

# Target variable:
**Churn** (Yes / No)
#  Tools & Technologies Used:- Python
   Pandas, NumPy – Data manipulation
   Matplotlib, Seaborn – Data visualization
   Scikit-learn – Machine learning and evaluation
   Jupyter Notebook

#  Exploratory Data Analysis (EDA)
Key insights discovered during EDA:
* Customers with shorter tenure show a higher tendency to churn
* Monthly charges have a positive relationship with churn
* Total charges are strongly correlated with tenure, indicating higher lifetime value for long-term customers

##  Data Preprocessing

* Handled missing values using SimpleImputer
* Encoded categorical variables into numerical format
* Removed non-informative identifiers
* Addressed class imbalance during model training

#  Feature Engineering
* Selected relevant features related to customer behavior, billing, and services
* Ensured all features were suitable for machine learning models

#  Model Building

* Implemented Logistic Regression as a baseline model
* Used class_weight="balanced" to handle imbalanced target classes
Logistic Regression was chosen due to its simplicity and interpretability, making it suitable for business decision-making.

#  Model Evaluation

Model performance was evaluated using:
* Accuracy
* Precision
* Recall
* F1-score

Special attention was given to recall for churned customers, as failing to identify potential churners can lead to revenue loss.

#  Business Insights & Recommendations

* Customers with low tenure and high monthly charges are more likely to churn
* Businesses can reduce churn by:
  1) Offering personalized discounts
  2) Providing flexible pricing plans
  3) Improving customer support for high-risk customers

# Conclusion

This project demonstrates a complete end-to-end machine learning workflow exploration to model evaluation and business insight generation.The solution can help telecom companies proactively identify churn-prone customers and design effective retention strategies.

#  Future Improvements
* Experiment with advanced models such as Random Forest or XGBoost
* Deploy the model using a web application

# Author
**Vishnupriya**
MSc Data Science Student


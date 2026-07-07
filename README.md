# Client Churn & Revenue Forecasting Using Machine Learning

## Project Overview

This project focuses on predicting customer churn and forecasting future revenue using machine learning algorithms. It helps organizations identify customers who are at risk of leaving, analyze the factors behind churn, and estimate future revenue trends for better business planning.

---

## Objectives

* Predict customers who are likely to discontinue services.
* Analyze important factors that influence customer churn.
* Forecast future revenue using customer-related data.
* Generate insights that can help improve customer retention strategies.

---

## Dataset

A synthetic dataset containing **10,000 customer records** was generated to represent real-world business scenarios.

The dataset includes:

* Customer ID
* Service Category
* Monthly Revenue
* Subscription Duration
* Number of Support Requests
* Customer Satisfaction Score
* Payment Delay Information
* Usage Patterns
* Security Issues
* Churn Status

Project Preparation Steps:

* Missing values were introduced and handled during preprocessing.
* Data imbalance was considered while building the churn prediction model.

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Joblib

---

## Project Workflow

1. Created a synthetic customer dataset.
2. Performed data cleaning and preprocessing.
3. Handled missing values using appropriate techniques.
4. Conducted Exploratory Data Analysis (EDA).
5. Trained a Random Forest Classifier for churn prediction.
6. Developed a Random Forest Regressor for revenue forecasting.
7. Evaluated model performance using different metrics.
8. Generated business insights from model results.

---

## Machine Learning Models

### Churn Prediction

* Random Forest Classifier

Evaluation Metrics:

* Accuracy Score
* Classification Report
* Confusion Matrix

### Revenue Forecasting

* Random Forest Regressor

Evaluation Metrics:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## Business Insights

* Customers with lower satisfaction levels have a higher possibility of churn.
* Frequent support issues can affect customer retention.
* Delayed payments can be an early indicator of customer risk.
* Customers with longer service durations generally show better retention.
* Improving customer experience can help reduce churn rates.

---

## Recommendations

* Provide faster and better customer support.
* Regularly monitor customers with high churn probability.
* Improve customer engagement through feedback collection.
* Encourage long-term service subscriptions.
* Use predictive insights for proactive customer retention.

---

## Repository Structure

```text
Client_Churn_Revenue_Forecasting/
│
├── data/
│   └── client_churn_dataset.csv
│
├── notebooks/
│   └── Client_Churn_Revenue_Forecasting.ipynb
│
├── models/
│   ├── churn_prediction_model.pkl
│   └── revenue_forecasting_model.pkl
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Note

The trained model files may not be included in the repository if they exceed GitHub file size limits. The models can be recreated by running the provided notebook.

---

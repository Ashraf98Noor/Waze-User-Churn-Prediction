# Waze User Churn Prediction Project

## 🚗 Project Overview

A 5 part series developed for each end of course project for Google Advanced Data Analytics, This multi-notebook project is focused on predicting and understanding monthly user churn in the Waze app. Churn is defined as users who have uninstalled or stopped using Waze. Using a full analytics workflow—from data inspection through machine learning—the project aims to equip Waze with actionable insights and a predictive model to reduce churn and retain more users.

## 📋 Table of Contents

* [Business Problem](#business-problem)
* [Data Description](#data-description)
* [Notebook Summaries](#notebook-summaries)
* [Key Results](#key-results)
* [Insights & Recommendations](#insights--recommendations)
* [References](#references)

## 💼 Business Problem

Waze’s product team seeks to proactively reduce monthly user churn by understanding which factors cause users to stop using or uninstall the app. The project’s goal is to analyze user behavior, quantify churn risk, and build a machine learning model that can accurately predict which users are at risk of churning.

## 📊 Data Description

The dataset includes:

* User activity and engagement metrics (sessions, features used, report frequency)
* Trip characteristics (duration, distance, congestion, incident reports)
* App usage history (recency, frequency)
* User satisfaction indicators
* Churn label (whether a user stopped using the app that month)

## 📓 Notebook Summaries

### 1. **Inspect and Analyze Data**

* Loaded user and trip datasets, profiled variables and checked data quality
* Identified missing values, outliers, and performed initial feature selection

### 2. **Visualize a Story in Python**

* Developed bar charts, boxplots, and scatterplots to uncover trends in user engagement, satisfaction, and app usage
* Illustrated behavioral differences between retained and churned users

### 3. **Data Exploration & Hypothesis Testing**

* Formulated and statistically tested hypotheses about churn risk factors (e.g., session frequency, incident reporting)
* Applied t-tests and correlation analysis to validate relationships

### 4. **Build a Regression Model**

* Constructed a regression model to analyze drivers of key numeric engagement metrics (e.g., session duration, usage frequency)
* Used insights to support feature selection for churn modeling

### 5. **Build a Machine Learning Model**

* Developed and evaluated a churn prediction model (e.g., logistic regression, decision tree)
* Tuned the model using accuracy, precision, recall, and confusion matrix
* Identified and visualized the most influential features for churn risk

## 📈 Key Results

* **Churn risk** is strongly linked to decreased session frequency, lower engagement, and lack of recent app usage
* **Churn prediction model** reliably distinguishes at-risk users

## 📝 Insights & Recommendations

* **Increase Engagement:** Proactive outreach and new feature prompts for users with declining session counts
* **Retention Campaigns:** Target high-risk users with incentives or personalized content
* **Feature Improvements:** Simplify critical features and reporting tools to drive recurring usage


## 📚 References

* Waze data documentation (Synthetic) created in partnership with Google Certificates.
* pandas, matplotlib, scikit-learn documentation.

---

*Created by Ashraf Un Noor. For questions or collaborations, connect via LinkedIn.*

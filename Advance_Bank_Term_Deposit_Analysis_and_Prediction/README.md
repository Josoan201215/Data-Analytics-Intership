# Advance Bank Term Deposit Analysis & Prediction

## 📌 Overview
This project builds on initial bank marketing data inspection to deliver a deeper analysis of customer behavior and a predictive model for term deposit subscriptions. It covers demographic analysis, campaign effectiveness, correlation analysis, and a logistic regression model to predict subscription outcomes.

This was completed as part of my internship with **Skillfied Mentor**.

## 🎯 Objective
- Analyze customer demographics (age, job) and their relationship with term deposit subscriptions
- Explore call duration and campaign contact trends
- Evaluate the effectiveness of different contact methods
- Identify correlations between numerical features
- Build and evaluate a logistic regression model to predict subscription likelihood
- Identify the strongest predictive features

## 🛠️ Tools & Libraries
- Python
- Pandas
- Seaborn & Matplotlib
- Scikit-learn (Logistic Regression, StandardScaler, train_test_split)
- Google Colab

## 📊 Key Steps
1. **Data Loading & Overview** – Loaded the dataset and reviewed its structure and shape
2. **Customer Demographics Analysis** – Visualized age distribution and job category breakdown
3. **Call Duration & Deposit Trends** – Compared average call duration between subscribers and non-subscribers
4. **Campaign Effectiveness** – Analyzed contact method (cellular vs. telephone) and number of contacts against subscription outcomes
5. **Correlation Heatmap** – Examined relationships between numerical variables (age, duration, campaign, economic indicators)
6. **Predictive Modeling** – Encoded categorical variables, scaled features, and trained a Logistic Regression model
7. **Feature Importance** – Ranked the top 10 features driving subscription predictions

## 📈 Model Performance
- **Accuracy:** ~91%
- **Precision (Subscribed):** 0.67
- **Recall (Subscribed):** 0.43
- **F1-score (Subscribed):** 0.53

> Note: The dataset is imbalanced (far more non-subscribers than subscribers), which affects recall for the minority class.

## 🔑 Key Takeaways
- Certain age groups and job categories are more likely to subscribe to a term deposit
- Higher call duration correlates with higher subscription rates (used as a proxy since the dataset has no balance field)
- Cellular contact is more effective than telephone contact
- Campaign duration and number of contacts influence subscription outcomes
- Logistic regression highlights the strongest predictors of subscription behavior

## 🚀 How to Run
1. Clone this repository
2. Open `PROJECT_Advance_Bank_Term_Deposit.ipynb` in Jupyter Notebook or Google Colab
3. Update the dataset path to point to your local copy of `data.csv`
4. Run all cells sequentially

## 📁 Dataset
The dataset used is `data.csv`, a bank marketing dataset containing customer demographics, contact details, campaign information, and economic indicators (e.g., `emp.var.rate`, `euribor3m`).

## 🙏 Acknowledgements
This project was completed as part of an internship program with **Skillfied Mentor**.

# Bank Marketing Data Inspection

## 📌 Overview
This project is an exploratory data analysis (EDA) of a bank's marketing campaign dataset. The goal is to inspect the dataset's structure, understand customer behavior, and identify early patterns related to whether a client subscribes to a term deposit.

This was completed as part of my internship with **Skillfied Mentor**.

## 🎯 Objective
- Load and inspect the `bankmarketing.csv` dataset
- Handle missing values and check data types
- Generate summary statistics
- Visualize the distribution of the target variable (`y`)
- Explore correlations between numerical features

## 🛠️ Tools & Libraries
- Python
- Pandas
- Seaborn
- Matplotlib
- Google Colab

## 📊 Key Steps
1. **Data Loading** – Imported the dataset via Google Drive/local upload
2. **Data Cleaning** – Checked for missing values and filled numeric nulls with the median
3. **Summary Statistics** – Generated descriptive statistics for all features
4. **Target Variable Analysis** – Visualized the class distribution of term deposit subscriptions (`y`)
5. **Correlation Analysis** – Built a correlation heatmap for numerical features

## 📈 Key Findings
- The dataset contains rich customer demographic and contact information useful for segmentation
- The target variable is **imbalanced**, with the majority of customers not subscribing to a term deposit
- This inspection lays the groundwork for further preprocessing, feature engineering, and predictive modeling

## 🚀 How to Run
1. Clone this repository
2. Open `PROJECT_Bank_Marketing_Inspection_test.ipynb` in Jupyter Notebook or Google Colab
3. Update the dataset path to point to your local copy of `bankmarketing.csv`
4. Run all cells sequentially

## 📁 Dataset
The dataset used is `bankmarketing.csv`, containing customer demographic details, contact information, and campaign outcomes from a bank's marketing campaign.

## 🙏 Acknowledgements
This project was completed as part of an internship program with **Skillfied Mentor**.

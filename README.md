# 📊 Customer Churn Analysis – Telecom Sector

## 🔍 Overview
Analyzed customer data from a telecom company to understand churn behavior, build predictive models, and create an interactive dashboard to support retention strategies.

## 📁 Dataset
- Source: [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Records: 7,043 rows × 21 columns

## 🛠️ Tools Used
- Python (Pandas, Matplotlib, Scikit-learn)
- Power BI
- SQL (for segmentation)
- Jupyter Notebook

## 📊 Key Features
- Logistic Regression model (accuracy ~87%)
- One-hot encoding of categorical variables
- Cleaned and exported dataset for dashboarding
- Power BI Dashboard with churn rate, tenure trends, and service usage insights
- SQL queries for churn analysis by segments (contract, tenure, payment method)


## 📈 Sample Dashboard Screenshot
![Screenshot 2025-05-20 130022](https://github.com/user-attachments/assets/bdd84753-ae2d-4f6d-9ca0-a221bed1668a)


## ✅ Results
- Churn rate: 26.5%
- Highest churn in month-to-month contracts with fiber optic internet
- Customers with tenure < 12 months are most likely to churn

## 📌 How to Run
1. Open `churn_analysis.ipynb` to review and run the code
2. Load `cleaned_churn_data.csv` into Power BI
3. Import visuals and connect slicers to explore churn patterns

# 📈 Stock Price Prediction and Analysis
### Machine Learning & Power BI Project using Historical Stock Market Data

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)
![License](https://img.shields.io/badge/License-MIT-red)

---

# 📌 Project Overview

This project is an end-to-end Stock Market Analysis and Stock Price Prediction system developed using historical stock market data of India's top companies.

The project focuses on predicting stock prices using multiple Machine Learning regression algorithms while performing complete data preprocessing, feature engineering, exploratory data analysis (EDA), model evaluation, and interactive business visualization using Power BI.

The dataset contains historical stock information of:

- Reliance Industries Ltd.
- Adani Enterprises Ltd.
- Tata Consultancy Services (TCS)

The project demonstrates the complete Data Science workflow from raw data collection to predictive modeling and dashboard development.

---

# 🎯 Objectives

The main objectives of this project are:

- Analyze historical stock market data.
- Clean and preprocess raw datasets.
- Merge multiple company datasets.
- Perform Exploratory Data Analysis (EDA).
- Engineer meaningful features.
- Train multiple Machine Learning models.
- Compare model performance.
- Predict future stock prices.
- Create an interactive Power BI dashboard.
- Generate business insights from historical stock performance.

---

# 📊 Dataset Information

The project uses historical stock price datasets containing daily market information.

## Companies

- Reliance Industries
- Adani Enterprises
- Tata Consultancy Services (TCS)

## Dataset Features

| Column | Description |
|----------|-------------|
| Date | Trading Date |
| Open | Opening Price |
| High | Highest Price |
| Low | Lowest Price |
| Close | Closing Price |
| Price | Average/Adjusted Price |
| Volume | Number of Shares Traded |
| Company | Company Name |

---

# 🛠 Project Workflow

## 1. Data Collection

Historical stock datasets were collected for three Indian companies using the web scraping \.

---

## 2. Data Cleaning

Performed:

- Missing value handling
- Duplicate removal
- Date formatting
- Data type conversion
- Column standardization
- Outlier checking

---

## 3. Dataset Merging

Merged all three company datasets into one master dataset.

Result:

```
Combined Stock Dataset
        │
        ├── Reliance
        ├── Adani
        └── TCS
```

---

## 4. Exploratory Data Analysis (EDA)

Performed:

- Company-wise stock comparison
- Closing price trends
- Volume analysis
- Distribution plots
- Correlation analysis
- Time series visualization
- Price movement analysis

---

## 5. Feature Engineering

Created new features including:

- Daily Return
- Moving Average (MA)
- Rolling Mean
- Rolling Standard Deviation
- Price Change
- Percentage Change
- Volatility
- Lag Features

These engineered features improve prediction accuracy.

---

## 6. Machine Learning Models

Four regression algorithms were trained and compared.

### Models Used

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor

---

## 7. Model Evaluation

Performance metrics used:

- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- R² Score
- Accuracy
- Precision
- Recall
- F2 Score

The best-performing model was selected based on evaluation metrics.

---

## 8. Prediction

The trained model predicts future stock prices using engineered features.

---

## 9. Power BI Dashboard

Interactive dashboard developed using Power BI.

Dashboard includes:

- Company-wise performance
- Price trends
- Trading volume
- Average prices
- Year-wise analysis
- Monthly trends
- Stock comparison
- KPI Cards
- Interactive Filters

---

# 📁 Project Structure

```
Stock-Price-Prediction/
│
├── Dataset/
│   ├── Reliance.csv
│   ├── Adani.csv
│   ├── TCS.csv
│   └── Combined_Dataset.csv
│
├── Data_Cleaning/
│
├── EDA/
│
├── Feature_Engineering/
│
├── Machine_Learning/
│
├── Models/
│
├── PowerBI/
│   └── Stock_Dashboard.pbix
│
├── Images/
│
├── Notebook/
│   └── Stock_Price_Prediction.ipynb
│
├── requirements.txt
│
├── README.md
│
└── LICENSE
```

---

# 📈 Machine Learning Pipeline

```
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Data Preprocessing
      │
      ▼
Feature Engineering
      │
      ▼
Train/Test Split
      │
      ▼
Model Training
      │
      ▼
Model Evaluation
      │
      ▼
Prediction
      │
      ▼
Power BI Dashboard
```

---

# 📊 Technologies Used

## Programming

- Python

## Libraries

- Pandas
- NumPy
- Matplotlib
- Plotly
- Scikit-learn
- XGBoost

## Visualization

- Power BI

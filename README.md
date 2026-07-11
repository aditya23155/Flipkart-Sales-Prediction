# 📈 Flipkart Sales Prediction & Business Intelligence Dashboard

An end-to-end Machine Learning and Business Intelligence project that predicts product sales using historical sales data while providing interactive business insights through Power BI dashboards.

---

## 📌 Project Overview

This project focuses on analyzing Flipkart sales data to identify factors affecting product sales and building a machine learning model capable of predicting future sales.

In addition to predictive modeling, an interactive Power BI dashboard was developed to visualize sales performance, category-wise trends, customer insights, and business KPIs to support data-driven decision-making.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess the dataset
- Engineer meaningful features
- Build and evaluate Machine Learning models for sales prediction
- Create interactive Power BI dashboards
- Generate actionable business insights

---

## 🛠 Tech Stack

### Programming

- Python

### Libraries

- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

### Visualization

- Power BI

### Tools

- Jupyter Notebook
- Git
- GitHub

---

## 📂 Repository Structure

```
Flipkart-Sales-Prediction/
│
├── notebooks/
│   └── Flipkart_Sales_Prediction.ipynb
│
├── dashboard/
│   ├── flipkart_sales.pbix
│   ├── dashboard.pdf
│   └── screenshots/
│
├── images/
│   ├── correlation_heatmap.png
│   ├── feature_importance.png
│   ├── sales_distribution.png
│   └── dashboard_preview.png
│
├── data/
│   └── flipkart_sales.csv
│
├── requirements.txt
│
└── README.md
```

---

# 📊 Dataset

The dataset contains historical Flipkart product sales information including:

- Product Category
- Product Price
- Discount
- Ratings
- Reviews
- Sales
- Revenue
- Product Features

*(Dataset sourced from Kaggle.)*

---

# 🔄 Project Workflow

## 1. Data Collection

- Imported the dataset
- Loaded into Pandas DataFrame

---

## 2. Data Cleaning

- Removed duplicate records
- Handled missing values
- Corrected inconsistent data
- Converted data types

---

## 3. Exploratory Data Analysis

Performed analysis to understand:

- Sales distribution
- Product category trends
- Revenue distribution
- Customer purchasing behavior
- Correlation between variables

Visualizations were created using Matplotlib and Seaborn.

---

## 4. Feature Engineering

Created meaningful features for improving model performance.

Examples include:

- Price-based features
- Revenue features
- Discount-related features
- Product category encoding

---

## 5. Machine Learning

Developed regression models to predict product sales.

General workflow:

- Train/Test Split
- Model Training
- Prediction
- Model Evaluation

---

## 📈 Model Evaluation

Performance was evaluated using regression metrics such as:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 📊 Power BI Dashboard

The project includes an interactive Power BI dashboard providing:

- Sales Overview
- Revenue Analysis
- Category-wise Sales
- Top Performing Products
- Monthly Sales Trends
- KPI Cards
- Interactive Filters and Slicers

---

# 📷 Dashboard Preview

> Add screenshots of your dashboard here.

Example:

```
images/dashboard_preview.png
```

---

# 💡 Key Insights

Examples of business insights obtained:

- Best performing product categories
- Seasonal sales trends
- High revenue generating products
- Effect of discounts on sales
- Customer purchasing patterns

---

# 🚀 Future Improvements

- Deploy the prediction model using Streamlit
- Integrate real-time sales forecasting
- Build REST APIs for prediction
- Add advanced forecasting models
- Automate dashboard refresh

---

# ▶️ How to Run

Clone the repository

```bash
git clone https://github.com/yourusername/Flipkart-Sales-Prediction.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Flipkart_Sales_Prediction.ipynb
```

To view the dashboard, open

```
dashboard/flipkart_sales.pbix
```

using Microsoft Power BI Desktop.

---

# 📌 Author

**Aditya Singh**

B.Tech Computer Science Engineering

VIT Bhopal University

GitHub: https://github.com/aditya23155

LinkedIn: https://linkedin.com/in/aditya-singh-9b2792294

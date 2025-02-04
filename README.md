# ITEC621_Project
ITEC 621 Descriptive Analytics Project

🏡 Predicting Single-Family Home Prices Using Economic Indicators

# 📌 Project Overview

This project builds a predictive model for estimating single-family home prices based on economic indicators and past housing market trends. The goal is to identify how factors such as historical home values, new construction rates, interest rates, and tax policies influence future home prices.

This project follows the CRISP-DM framework, ensuring a structured approach to data exploration, modeling, and evaluation.

---

# 📈 Business Problem

The real estate market is highly dynamic, influenced by economic policies, interest rates, and supply-demand factors. By leveraging historical data, this project aims to:
✔ Provide insights into market trends 📊
✔ Help investors, policymakers, and homebuyers make informed decisions 🏡
✔ Forecast future home prices with interpretable predictive models 🔍

---

# 📊 Data Sources

- Zillow Housing Data{https://www.zillow.com/research/data/}
- Federal Reserve Economic Data{https://fred.stlouisfed.org/}
- IRS Historical Data{

---

# 🛠️ Methodology

This project explores multiple machine learning models to predict home prices:

1️⃣ Data Preprocessing
	•	Handling missing values
	•	Feature engineering (lag variables, inflation-adjusted prices)
	•	Scaling and normalizing economic indicators

2️⃣ Exploratory Data Analysis (EDA)
	•	Identifying trends in home values over time
	•	Correlation analysis between economic markers and home prices

3️⃣ Predictive Modeling
	•	OLS Regression → Baseline model for interpretability
	•	Random Forest Regression → Captures non-linear relationships
	•	XGBoost → Optimized tree-based model for improved accuracy

4️⃣ Model Evaluation & Interpretation
	•	Performance metrics: RMSE, MAE, R²
	•	Feature importance analysis

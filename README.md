# ITEC621_Project
ITEC 621 Descriptive Analytics Project

🏡 Predicting Median Housing Prices in New York City

# 📌 Project Overview

This project aims to analyze and predict single-family home prices in New York City using economic and social indicators. By leveraging historical housing market data, economic policy changes, and social trends, we build multiple predictive models to identify key drivers of home values.

The study follows the CRISP-DM framework, ensuring a structured approach to data exploration, modeling, and evaluation.

# 📈 Business Problem

The New York City housing market is influenced by a complex mix of economic conditions, policy decisions, and social factors. This project aims to:

✔ Analyze key economic and social predictors affecting home prices 📊
✔ Help policymakers, homebuyers, and investors make data-driven decisions 🏡
✔ Develop robust predictive models to forecast home prices with statistical accuracy 🔍

# 📊 Data Sources

The dataset spans January 2000 to December 2024 and integrates multiple sources:

- **[Zillow Housing Data](https://www.zillow.com/research/data/)**
  
  	•	Median home sale prices <br>
	•	New construction sales <br>
	•	Mean home values <br>
	•	Rental cost index <br>
 
- **[Federal Reserve Economic Data](https://fred.stlouisfed.org/)**

	•	Federal interest rates <br>
	•	15-year and 30-year mortgage rates <br>
	•	NY and national median household income <br>
	•	Unemployment rates <br>
 
- **[IRS Historical Data](https://www.irs.gov/statistics)**

	•	Major felonies <br>
	•	Misdemeanor offenses <br>
	•	Non-seven major felony offenses <br>

# 🛠️ Methodology

This study explores multiple machine learning techniques and econometric models:

1️⃣ Data Preprocessing
	•	Addressed missing values <br>
	•	Standardized data to a monthly frequency <br>
	•	Handled time series adjustments (e.g., transforming yearly data into monthly estimates) <br>
	•	Created dummy variables for key economic events (2008 Financial Crisis, COVID-19 Pandemic) <br>

2️⃣ Exploratory Data Analysis (EDA)
	•	Identified time trends and seasonality <br>
	•	Conducted correlation analysis among economic and social indicators <br>
	•	Visualized distributions and patterns to assess normality and stationarity <br>

3️⃣ Predictive Modeling
	•	Ordinary Least Squares (OLS) Regression – Baseline interpretability model <br>
	•	Weighted Least Squares (WLS) Regression – Addresses heteroskedasticity issues <br>
	•	Bootstrap Aggregation (Bagging) – Reduces variance and improves model robustness <br>
	•	Cross-Validation (10-Fold CV) – Evaluates model generalization performance <br>

4️⃣ Model Evaluation & Interpretation
	•	Performance metrics: R², RMSE, MAE <br>
	•	Heteroskedasticity tests – Addressing issues through transformation techniques <br>
	•	Durbin-Watson test – Analyzing serial correlation in residuals <br>
	•	Feature importance analysis <br>

# 🔍 Key Findings

- Financial <br>
	•	Mortgage rates (15-year and 30-year) and interest rates are significant predictors of housing prices. <br>
	•	Median household income is strongly correlated with home prices. <br>
- Crime <br>
	•	Crime rates (major felonies, misdemeanors) show relationships with property values but require further exploration. <br>
- Crises <br>
	•	The 2008 financial crisis and COVID-19 pandemic had measurable impacts on NYC home prices. <br>
- Statistical <br>
	•	High adjusted R² (98.7% - 99.66%) across models suggests strong explanatory power, though serial correlation and heteroskedasticity persist. <br>

# 📢 Conclusion & Future Work

This project highlights the interplay of economic, financial, and social indicators in shaping New York City’s real estate market. While our models achieved high predictive accuracy, challenges such as serial correlation and heteroskedasticity indicate opportunities for further refinement:

✔ Exploring alternative time series models (e.g., ARIMA, VAR) <br>
✔ Enhancing variable selection techniques to address multicollinearity <br>
✔ Incorporating additional external factors (e.g., inflation rates, housing policies) <br>

By refining these models, we can provide more actionable insights for homebuyers, investors, and policymakers in navigating the dynamic NYC housing market.

# 🚀 Contributors

*Ledia Dobi* ([ld5469a@american.edu](mailto:ld5469a@american.edu))

*Conie O’Malley* ([co1984a@american.edu](mailto:co1984a@american.edu))




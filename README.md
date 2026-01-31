# 🛒 Walmart Sales Forecasting using Machine Learning

Accurate sales forecasting is critical for retail businesses to optimize inventory, plan promotions, and streamline supply chain operations. This project builds a **data-driven forecasting system** to predict Walmart’s **weekly store-level sales** using historical data and economic indicators.

---

## 📌 Overview

Retail giants like Walmart operate across multiple stores where sales are influenced by **seasonality, holidays, and economic conditions**. Poor forecasts can lead to overstocking, stockouts, and revenue loss.

This project aims to:
- Analyze historical Walmart sales data
- Identify trends, seasonality, and external influences
- Engineer time-series features
- Train and evaluate machine learning models
- Generate reliable weekly sales forecasts to support business decision-making

---

## 🧰 Tech Stack

- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **Machine Learning:** scikit-learn  
- **Models:** Linear Regression, Random Forest, Gradient Boosting  
- **Techniques:**  
  - Exploratory Data Analysis (EDA)  
  - Feature Engineering  
  - Time-Series Forecasting  
  - Model Evaluation (RMSE, MAE)  

---

## 📂 Dataset

  https://www.kaggle.com/datasets/aslanahmedov/walmart-sales-forecast?resource=download
- **Source:** Walmart Sales Forecast Dataset (Kaggle)  
- **Domain:** Retail Analytics, Time-Series Forecasting  

### Key Features:
- Store ID  
- Date / Week  
- Weekly Sales  
- Holiday Flag  
- Temperature  
- Fuel Price  
- Consumer Price Index (CPI)  
- Unemployment Rate  

---

## 🔍 Workflow

### 1️⃣ Data Understanding
- Studied dataset structure and feature relevance
- Analyzed how economic and seasonal factors impact sales

### 2️⃣ Data Cleaning & Preprocessing
- Handled missing values and inconsistencies
- Converted date columns to datetime format
- Removed duplicates
- Treated outliers in weekly sales using statistical methods

### 3️⃣ Exploratory Data Analysis (EDA)
- Analyzed sales trends over time
- Compared holiday vs non-holiday sales
- Evaluated store-wise sales performance
- Studied the impact of fuel price, CPI, and unemployment on sales

### 4️⃣ Feature Engineering
- Extracted time-based features (Year, Month, Week)
- Created lag features (previous week sales)
- Generated rolling averages to capture trends
- Improved temporal learning capability of models

### 5️⃣ Model Building
- Trained baseline and advanced ML models:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
- Split data into training and testing sets
- Tuned models for improved accuracy

---

## 📊 Results & Model Performance

### Evaluation Metrics:
- **RMSE (Root Mean Squared Error)**
- **MAE (Mean Absolute Error)**

### Key Findings:
- Tree-based models outperformed baseline linear regression
- Gradient Boosting achieved the **lowest prediction error**
- Lag features and rolling averages significantly improved accuracy
- Holiday weeks showed distinct sales spikes captured by the model

### Outcome:
✔ Reliable weekly sales forecasts  
✔ Improved prediction accuracy over baseline models  
✔ Actionable insights for retail decision-making  

---

## 📈 Business Impact

This forecasting solution helps retail businesses:
- Reduce overstocking and stockouts  
- Improve inventory and supply chain planning  
- Plan promotions more effectively  
- Enable data-driven strategic decisions  

---

## 🚀 Future Work

- Implement advanced time-series models (ARIMA, SARIMA, Prophet)
- Apply deep learning models (LSTM, GRU)
- Perform hyperparameter tuning using GridSearchCV
- Build an interactive dashboard for visualization
- Extend forecasting to item-level sales

---

## 🧑‍💻 Author

** Armalla Purna Vignesh Reddy**  
Aspiring Data Analyst | Machine Learning & Analytics Enthusiast  

⭐ If you find this project helpful, consider giving it a star!

# walmart_sales_time_series_forecasting
walmart_sales__forecasting
# Walmart Sales Time Series Forecasting

## 📌 Project Overview
This project focuses on **time series forecasting** using the Walmart Sales dataset.  
The goal is to analyze historical sales data, identify trends and seasonality, and
forecast future sales using statistical forecasting techniques.

This project was completed as part of a **Data Analyst Internship – Task 16:
Forecasting (Time Series Trend & Prediction)**.

---

## 🛠 Tools & Technologies
- Python (Google Colab)
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- Scikit-learn

---

## 📂 Dataset Description
The project uses the **Walmart Sales Forecasting dataset**.

Files provided:
- `train.csv` – Historical weekly sales data (used for forecasting)
- `test.csv` – Future weeks data (not used in this task)
- `stores.csv` – Store metadata
- `features.csv` – Additional economic and holiday features

For this task, only **train.csv** was used to perform univariate time series forecasting.

---

## 🔍 Methodology
1. Loaded the dataset and converted the `Date` column to datetime format.
2. Aggregated weekly sales into **monthly total sales**.
3. Visualized sales trends over time.
4. Checked seasonality using rolling mean.
5. Split data into **training and testing sets** based on time.
6. Built a forecasting model using **Exponential Smoothing**.
7. Forecasted sales for the next 6 months.
8. Evaluated model performance using **MAE** and **MAPE**.
9. Exported forecast results and report.

---

## 📈 Forecasting Model
- **Model Used:** Exponential Smoothing (Additive Trend & Seasonality)
- **Seasonal Period:** 12 months
- **Forecast Horizon:** 6 months

---

## 📊 Evaluation Metrics
- **MAE (Mean Absolute Error)**
- **MAPE (Mean Absolute Percentage Error)**

These metrics were used to evaluate the accuracy of the forecast on unseen data.

---

## 📁 Project Deliverables
- `task16_forecasting.ipynb` – Complete Python notebook
- `forecast_output.csv` – Actual vs Forecasted sales
- `forecast_report.txt` – Summary report with results and conclusions

---

## ✅ Final Outcome
The project demonstrates how time series forecasting can be applied in a real-world
retail business scenario to support:
- Demand forecasting
- Inventory planning
- Business decision-making

---

## 🚀 Future Improvements
- Include external features using SARIMAX
- Forecast at store or department level
- Compare multiple forecasting models
  ---

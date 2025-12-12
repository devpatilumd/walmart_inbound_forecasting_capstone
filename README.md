# 📦 Walmart Inbound Forecasting & Demand Modeling  
### **UMD MSBA Capstone Project | Team Project with Vinay Chandran & UMD Analytics Team**

Forecasting inbound **cases** and **trucks** for 100 Walmart stores across 5 key departments using 17 months of historical operational data.  
We built an end-to-end pipeline including data engineering, feature creation, time-series modeling, evaluation, and business insights for decision-making.

---

## 🚀 My Key Contributions
- Processed and merged **275,000+ store-department-day** records  
- Built **custom time-series train/validation/test splits**  
- Engineered features for **seasonality, lags, rolling windows, holidays, and weather**  
- Developed & compared models:  
  - **CatBoost**
  - **XGBoost**
  - **ETS / ARIMA**  
- Hyperparameter tuning & department-level evaluation  
- Designed visualizations and performance diagnostics  
- Co-developed final business insights for Walmart stakeholders  

---

## 📊 Project Workflow
1. **Data Preparation** – merging CSV/XLSX files, cleaning, imputations  
2. **EDA** – patterns, seasonal signals, anomalies  
3. **Feature Engineering** – lags, rolling metrics, holiday features, weather  
4. **Time-Series Modeling** – CatBoost, XGBoost, ARIMA/ETS  
5. **Evaluation** – RMSE, MAPE, department-level comparison  
6. **Insights** – best model per department, key feature impact, operational recommendations  

---

## 🧠 Tech Stack
**Python**, **Pandas**, **NumPy**, **Scikit-learn**  
**CatBoost**, **XGBoost**, **Statsmodels**  
**Matplotlib**, **Seaborn**  
**Jupyter Notebooks**

---

## 📂 Repository Structure
```
├── data/
│   ├── inbound_cases_team8.csv
│   ├── stores_data.xlsx
│   └── trucks.csv
│
├── models/
│   ├── catboost/
│   ├── statsmodels/
│   └── xgboost/
│
├── visualizations/
│
├── 01_data_merge.ipynb
├── 02_data_preparation_pipeline.ipynb
├── 03_timeseries_splits.ipynb
├── 04_dept6_modeling_suite.ipynb
├── 05_dept9_modeling_suite.ipynb
├── 06_dept41_modeling_suite.ipynb
├── 07_dept67_modeling_suite.ipynb
├── 08_dept90_modeling_suite.ipynb
└── 09_dept_model_summary.ipynb
```

---

## 📈 Results Summary
- **CatBoost** had the strongest performance across most departments  
- Weather features improved truck forecasts in select states  
- High variation in department-level behavior — no universal model  
- Engineered lags and rolling windows were highly predictive  
- Delivered insights to optimize inbound scheduling & resource allocation  

---

## 👥 Team
**Devraj Patil** — Data Prep, Feature Engineering, Modeling, Insights  
**Vinay Chandran** — Modeling, Evaluation, Visualization, Insights  
UMD MSBA 2025 Cohort  

---

## 🔗 Source
Forked from the original project:  
https://github.com/VinChan2001/wmt_proj


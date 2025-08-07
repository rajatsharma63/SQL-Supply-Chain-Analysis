
## 🔍 Objectives

- Understand historical trends in car sales data
- Apply **time series forecasting** to predict future demand
- Compare performance of statistical vs. ML forecasting methods
- Lay the foundation for SQL-driven analytics in supply chain use cases

---

## 📈 Forecasting Techniques Used

### Part 1: Statistical Forecasting
- **Simple Exponential Smoothing (SES)**
- **Holt’s Linear Trend Model**
- **Holt-Winters Seasonal Model**
- **SARIMA (Seasonal ARIMA)**

### Part 2: Machine Learning Forecasting
- Feature Engineering (Lag features, Rolling averages)
- Train/test split using time series cross-validation
- **XGBoost Regressor**
- Model Evaluation using RMSE

---

## 📁 Dataset Description

1. **norway_new_car_sales_by_make.csv**  
   - Monthly car sales in Norway categorized by brand
   - Time span: Several years
   - Target variable: `Total car sales`

2. **GDP.xlsx**  
   - Economic indicator potentially usable for external regressors in advanced forecasting

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or VSCode
- Install required libraries:
```bash
pip install pandas numpy matplotlib statsmodels scikit-learn xgboost

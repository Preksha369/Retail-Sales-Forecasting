#  Retail Sales Forecasting

This project focuses on forecasting weekly retail sales using historical transaction data. The goal is to build a predictive model that estimates product-wise sales for the next 3 months, helping businesses optimize inventory and demand planning.

---

##  Project Structure

- `1_EDA_Retail_Sales.ipynb`  
  Exploratory Data Analysis notebook that inspects the dataset, identifies missing weeks, handles outliers, and uncovers trends in quantity sold across products and time.

- `2_Model_Retail_Sales_Forecasting.ipynb`  
  Model building notebook using XGBoost Regressor to predict future weekly sales. Includes preprocessing steps like feature engineering (lag features, rolling stats), hyperparameter tuning, and evaluation.

---

## Dataset Overview

The dataset includes the following columns:
- `weekend_date`: Week ending Saturday
- `SerailNum`: Product serial number
- `quantity`: Weekly quantity sold
- `channel`, `brand`, `category`, `sub_category`: Product metadata

---

## Tools & Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- XGBoost
- Time Series Analysis
- Feature Engineering
- Jupyter Notebook

---

## Key Highlights

- Detected missing weekly data for product serials.
- Handled outliers using IQR method.
- Engineered lag and rolling window features for improved model accuracy.
- Forecasted product-wise weekly sales with reasonable performance.

---

##  Output

- Cleaned dataset saved as: `cleaned_Assessment.csv`
- Forecasts for future weeks exported as: `forecast_output.csv`

---

##  Future Improvements

- Integrate seasonality and holidays into the model.
- Use advanced time series models like Prophet or LSTM.
- Deploy model as an API for real-time use.

---



# Gold-Price-Prediction-ML

# Gold Price Prediction using Machine Learning

## Project Overview
This project predicts the **historical gold price (GLD)** using machine learning techniques. The goal is to analyze how financial indicators like the S&P 500 index (SPX), crude oil prices (USO), silver prices (SLV), and currency exchange rates (EUR/USD) affect gold prices.  

We use a **Random Forest Regressor** to model the relationship and predict future prices, and we evaluate the model using the **R² score**.

---

## Dataset
The dataset used is `gld_price_data.csv` and contains historical gold price data from 2008 to 2018 with the following columns:

| Column   | Description |
|----------|-------------|
| Date     | Date of record |
| SPX      | S&P 500 Index value |
| GLD      | Gold price (target variable) |
| USO      | Crude oil price |
| SLV      | Silver price |
| EUR/USD  | Exchange rate of Euro to USD |

- Total records: 2290  
- No missing values in the dataset.

---

## Libraries Used
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  


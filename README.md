# Time Series Forecasting Project

## Project Overview
This project focuses on forecasting time series data using stock price data for **Amazon (AMZN)** from **Yahoo Finance**. The goal is to build, evaluate, and compare multiple forecasting models to determine the most accurate one for predicting future trends.

---

## Dataset
- **Source:** Yahoo Finance  
- **Stock Ticker:** AMZN (Amazon)  
- The dataset contains historical stock price data including open, close, high, low prices, and volume.

---

## Data Preprocessing
1. **Filling Missing Data:**  
   - Missing values are imputed using **pchip** (Piecewise Cubic Hermite Interpolating Polynomial) and **cubic interpolation** for smooth continuity.  

2. **Splitting Dataset:**  
   - The dataset is split into training and test sets with the following ratios:  
     - 70% training / 30% test  
     - 80% training / 20% test  
     - 90% training / 10% test  

---

## Models Used
1. **Bayesian Ridge Regression (Bayes Bridge):**  
   - A probabilistic model for time series forecasting that incorporates prior information and uncertainty into predictions.  

2. **Long Short-Term Memory (LSTM):**  
   - A type of Recurrent Neural Network (RNN) designed to capture long-term dependencies in sequential data.  

3. **Autoregressive Integrated Moving Average (ARIMA):**  
   - A statistical model used for time series forecasting based on lagged observations and error terms.  

---

## Implementation Steps
1. Preprocess the data and handle missing values using pchip/cubic interpolation.  
2. Train and test the models on each of the three data splits (70/30, 80/20, 90/10).  
3. Evaluate the performance of each model using metrics such as:  
   - Mean Absolute Error (MAE)  
   - Root Mean Squared Error (RMSE)  
   - Mean Absolute Percentage Error (MAPE)  

4. Compare the models to determine the optimal one for forecasting Amazon's stock prices.  

---

## Results and Findings
- Performance metrics and visualizations will guide the selection of the most accurate model.  
- The chosen model will provide insights into future stock price trends for Amazon based on historical data.  

---

## Requirements
- **Python Version:** 3.12 or higher  
- **Required Libraries:**  
  - `pandas`  
  - `numpy`  
  - `matplotlib`  
  - `seaborn`  
  - `scikit-learn`  
  - `statsmodels`  
  - `tensorflow`  

---

## How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name



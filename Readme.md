# Stock Market Prediction

## Project Overview

This project involves predicting stock market performance, specifically forecasting the future value of a particular stock and recommending the best strategy (Buy, Hold, or Sell) for each day. The goal is to assist in making informed investment decisions. This project uses time series analysis and classification techniques to achieve accurate predictions and strategy recommendations.

## Key Tasks

1. **Data Exploration**: Analyze the provided dataset, visualize historical stock prices, and assess data quality.
2. **Feature Engineering**: Create new features such as lagged variables, rolling statistics, and technical indicators to enhance the model's performance.
3. **Time Series Forecasting**: Implement the SARIMAX model to predict future stock prices.
4. **Strategy Classification**: Develop classification models using XGBoost and RandomForest to recommend Buy, Hold, or Sell strategies.
5. **Model Evaluation**: Compare model performance using Symmetric Mean Absolute Percentage Error (SMAPE) for price predictions and Accuracy for strategy classification.

## Requirements

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `statsmodels`
- `xgboost`
- `scikit-learn`

## File Structure

- `Stock_Market_Prediction.ipynb`: Jupyter Notebook containing the code for data exploration, feature engineering, time series forecasting, and strategy classification.
- `submission.csv`: CSV file with the final predictions and recommended strategies.

## How to Run

1. Clone the repository:
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Stock_Market_Prediction.ipynb
    ```

4. Run the cells sequentially to perform data analysis, build models, and generate predictions.

## Usage

- **Data Exploration**: Visualize the historical closing prices and assess feature distributions.
- **Time Series Forecasting**: Use the SARIMAX model to predict future stock prices.
- **Strategy Classification**: Train and evaluate XGBoost and RandomForest classifiers to suggest Buy, Hold, or Sell strategies.

## Results

- **Stock Price Predictions**: The SARIMAX model forecasts future stock prices, which are saved in `sarimax_test.csv`.
- **Strategy Recommendations**: The classification models provide daily strategy recommendations, saved in `submission.csv`.



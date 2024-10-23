# 🚀 Google Stock Prediction 📊

Welcome to my **Google Stock Prediction** project! This project uses historical stock data and machine learning techniques to predict Google's stock prices. Below are the main highlights:

## Key Metrics:
- **Historical Data**: Daily stock prices for Google (GOOGL).
- **Predicted Prices**: Forecasted stock prices using machine learning models.
- **Model Performance**: Evaluation of models using metrics like MSE (Mean Squared Error).

## Visuals:
- **Price Trends**: Visualizing historical stock price trends.
- **Predictions vs. Actuals**: Comparing predicted stock prices with actual values over time.
- **Model Accuracy**: Metrics and charts showing model performance.

## Tools Used:
- **Python**: For data processing and modeling.
- **Pandas**: To handle and manipulate the stock price data.
- **scikit-learn**: For building and evaluating machine learning models.
- **TensorFlow/Keras**: For constructing the LSTM model for time series prediction.
- **Matplotlib & Seaborn**: For creating visualizations of the data and predictions.
- **yfinance**: To retrieve stock price data from Yahoo Finance.

## Models Implemented:
- **Linear Regression**: For basic stock price prediction.
- **Random Forest**: For improving prediction accuracy.
- **LSTM (Long Short-Term Memory)**: A deep learning model to handle time-series data.

## How to Use:
1. **Clone the repository**:
    ```bash
    git clone <your-repository-link>
    ```

2. **Install required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook**:
    ```bash
    jupyter notebook Google_Stock_Prediction.ipynb
    ```

## Data Source:
- The stock data is pulled using the `yfinance` library from Yahoo Finance.

Feel free to explore the notebook and provide feedback! Your suggestions are always welcome.

---

### Screenshots:

#### 1. Price Trends:
![Price Trends](./images/price_trends.png)

#### 2. Predictions vs. Actuals:
![Predictions vs Actuals](./images/predictions_vs_actuals.png)

---

## License:
This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.


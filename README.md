# Stock-Price-Prediction---Time-Series-Model
Stock Price Prediction - Time Series Model forecasting techniques using Statsmodel Autoregressive Integrated Moving Average (ARIMA)

![Stock Price](https://i.postimg.cc/rscKQdHm/Black-and-White-Modern-Stock-Market-Presentation.jpg)

## Objective
To predict the stock price of the New Germany Fund (GF) and forecast its closing price for the next five trading days.

## Summary Objectives
- To analyze historical stock price data and detect underlying patterns.
- To implement time series forecasting techniques using `statsmodels.tsa.api` and `statsmodels.api`.
- To evaluate the accuracy and reliability of different forecasting models.

## Methodology
The project will utilize historical stock price data, which will undergo preprocessing, including handling missing values, stationarity checks, and feature engineering. The following models will be implemented:

- **Autoregressive Integrated Moving Average (ARIMA)** – A traditional statistical approach for time series forecasting.
- **Seasonal ARIMA (SARIMA)** – An extension of ARIMA that accounts for seasonality in stock prices.
- **Vector Autoregression (VAR)** – A multivariate time series forecasting method to analyze interdependencies between stocks.
- **Exponential Smoothing State Space Model (ETS)** – A smoothing-based approach for short-term stock price forecasting.

Performance will be evaluated using metrics like:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)

## Expected Outcomes
- A robust predictive model for forecasting the stock price of the New Germany Fund (GF).
- Identification of key trends and seasonality patterns affecting stock movements.
- A comparative analysis of different statsmodels-based forecasting models.

## Conclusion
This project will contribute to the understanding of stock market trends by leveraging time series forecasting techniques, providing a valuable tool for investors and financial analysts.

## Recommendations
Future work can focus on:
- Incorporating external economic indicators to improve model accuracy.
- Exploring deep learning-based time series forecasting methods such as LSTMs.
- Developing a real-time stock price prediction dashboard.

SARIMA Model Output
The SARIMA model was applied to forecast values for the given time series. The output below shows the actual values alongside the predicted values:

| Date       | Actual | Predicted |
|-------------|---------|-----------|
| 2018-06-05 | 18.93   | 18.96     |
| 2018-06-06 | 19.23   | 18.97     |
| 2018-06-07 | 19.08   | 18.96     |
| 2018-06-08 | 19.17   | 18.92     |
| 2018-06-09 | 19.11   | 18.94     |

Observations
- The predicted values are generally close to the actual values, indicating a good fit of the SARIMA model.
- There are some minor deviations between the actual and predicted values, which could be due to random fluctuations in the data.
- The model seems to be slightly underestimating the actual values, as the predicted values are mostly lower than the actual values.

Future Improvements
- Further tuning of the SARIMA model parameters (e.g., p, d, q, P, D, Q, S) may be necessary to improve the accuracy of the predictions.
- Incorporating additional features or variables into the model could potentially improve its performance.
- Using other time series forecasting models, such as ARIMA, ETS, or LSTM, may also be worth exploring to compare their performance with the SARIMA model.

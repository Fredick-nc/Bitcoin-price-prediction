# Bitcoin-price-prediction

Link of the dataset in this project: https://www.coindesk.com/price/bitcoin/

Digital currency market has not been smooth sailing because its price fluctuates sharply and it is difficult to regulate. Therefore, it is essential to predict the price of digital currency, like bitcoin, as it can bring significant information advantage and avoid potential risk, promoting economical effects obviously.  In this project, it takes bitcoin historical transaction data to construct five models, such as ARIMA, SVR, XGBoost, LSTM, Random Forest Regression. And from the result, we can know that the traditional ARIMA is not effective in predicting Bitcoin price fluctuations. As time increases, the error will increase; LSTM has the inherent ability to quickly adapt to sharp changes in the trend, and at the same time obtain the minimum RMSE. It is 399.15, R-squared is close to 99%, and the prediction effect is the best.

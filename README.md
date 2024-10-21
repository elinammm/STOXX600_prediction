# STOXX600_prediction (first draft)

Analyzing how well different economic indicators predict the changes in the Euro 600 (STOXX 600) index, which shows the performance of the European stock market [4]. This is a supervised machine learning project, since we have a labeled dataset for the STOXX Europe 600. All our data regarding the label as well as the feature variables can be found from the website Investing.com. The indicators used to analyze the STOXX Europe 600 are:

•	Euribor (Euro interbank offered rate) future rate [1]
•	The USD/EUR currency exchange rate [2]
•	S&P 500 index [3]

The features are normalized by using the daily  percentual changes. Linear regression and random forest regression are used as models. I'm using data from the last 5 years. 


References:
1.	Euribor C2S Futures Historical Price Data (no date) Investing.com. Available at: https://www.investing.com/indices/euribor-c2-futures-historical-data (Accessed: 12 September 2024). 
2.	USD EUR historical data (no date) Investing.com. Available at: https://www.investing.com/currencies/usd-eur-historical-data (Accessed: 12 September 2024). 
3.	S&P 500 historical rates (SPX) (no date) Investing.com. Available at: https://www.investing.com/indices/us-spx-500-historical-data (Accessed: 12 September 2024). 
4.	Stoxx 600 historical rates (Stoxx) (no date) Investing.com. Available at:https://www.investing.com/indices/stoxx-600-historical-data (Accessed: 12 September 2024). 
5. 	Randomforestregressor (no date) scikit. Available at: https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html (Accessed: 09 October 2024).
6. 	Linear regression (no date) scikit. Available at: https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html (Accessed: 18 September2024). 

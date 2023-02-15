# StockMarketAnalysis
Used different AWS components in order to analyse minute-by-minute data of the Indian Stock Market. 

Stock Markets have been one of the most lucrative ways to make money since the beginning of time. Predicting and Analyzing Stock Prices has been one of the biggest problems in the stock markets. To minimize speculations and increase the accuracy of data this project will focus on Analyzing and Predicting Stock Market movements and volatility. We will also be using the ARIMA model to predict future stock prices in this project..
The main focus of this project would be the Indian Stock Markets and more specifically the main index of Indian Markets and select stocks in that

Initially, we stored the data in a Cloudera EC2 instance and attempted to run Impala queries but we ran into some issues and hence tried to use some other technology.
We then decided to store the data in an Amazon S3 bucket. Then we set up an Amazon EMR instance and used PySpark in Jupyter Notebook to run predictive and descriptive analyses on the data. We used the ARIMA model to conduct predictive analysis on stock prices.

# Stock Market Prediction using Numerical and Textual Analysis

Stock Market Prediction using Numerical and Textual Analysis

### Installations
* Natural Language Toolkit - `pip install nltk` 
* Auto ARIMA for Autoregressive Integrated Moving Average model (ARIMA) - `pip install pmdarima`
### Project Overview
A time series analysis of Reliance Stock prices for the last 5 years from [Yahoo Finance](https://finance.yahoo.com), containing: <br>
* stationarity tests 
* autocorrelation tests, and finally
* a prediction using the Autoregressive Integrated Moving Average (ARIMA) method

The Second part of the project is a textual analysis of news headlines in India, compiled by Rohit Kulkarni, 2020, taken from Harvard Dataverse. Sentiments such as polarity, positive, negative, neutral, etc. is obtained through the Natural Language Tooklit (NLTK)'s (Vader), sentiment intensity analyzer. _Click [here](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DPQMQH) for the news dataset._

The final part is to combine the stock price dataset, and the textual dataset with the sentiment values, and different methods of machine learning such as Linear Regression, Random Forest Regression, XG Boost, ADA Boost, and Light Gradient Boost is used to predict the stock prices. 
The Mean squared Error is used as the evaluating criteria for the different methods. 
### Limitations of the methods used
One limitation of this project is the prediction in the first part : the stock prices contains heavy volatility clustering - and hence an ARIMA method may give biased results, without controlling for Autoregressive Conditional Heteroskedasticity, or ARCH. 

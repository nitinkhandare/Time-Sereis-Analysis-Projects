# Time-Sereis-Analysis-Projects

### Problem Statement: 

Time Series Analysis on Indian Stocks exchange(NSE, BSE) using Deep Learning by Recurrent neural networks (RNN) Approach, and Discover Long Short-Term Memory (LSTM) networks in Python and how you can use them to make stock market predictions.
Time series analysis allows us to extract meaningful statistics and other characteristics from time series Stock data. 
A type of time series analysis is forecasting, which predicts future values based on previously observed values.
Time series variables analyzed in business are often internal like sales or transactions.
You would like to model stock prices correctly, so as a stock buyer you can reasonably decide when to buy stocks and when to sell them to make a profit. This is where time series modelling comes in. 
You need good machine learning models that can look at the history of a sequence of data and correctly predict what the future elements of the sequence are going to be.


### Approach:

I have started the project time series analysis using deep learning RNN on Indian stock exchange Companies Stock Data.
I took Recurrent Neural Networks and LSTM model for this analysis  this is the state of the art algorithm for sequential data and among others used by Apples Siri and Googles Voice Search. 
This is because it is the first algorithm that remembers its input, due to an internal memory, which makes it perfectly suited for Deep Learning problems that involve sequential data. 
It is one of the algorithms behind the scenes of the amazing achievements of Deep Learning in the past few years.


### Data Understanding:
#### Data Source:

Quandl has historical stock quotes, both adjusted and un-adjusted, for many international stock exchanges. https://www.quandl.com/
Each of these databases includes daily OHLCV quotes and multiple years of history below is the Indian stock exchange Data.
1. XBOM – Bombay Stock Exchange of India
2. XNSE   – National Stock Exchange of India
Most of these global stock databases are sourced from Exchange Data International, the leading institutional-grade provider of stock price history in the world.


#### Data Description:

We find the following information about the columns in a Data and I am using different stock data they have same type of columns:
Date - Date for which the price is given
Open - Price of the stock at market open (In USD)
High - Highest price reached in the day
Low - Lowest price reached in the day
Close - Closing price for the day
Total Trade Quantity - Number of shares Traded Quantity for Day
Turnover (Lacs) - total turnover of a for Day


### Data Preparation:

Data extraction and collection from quandl data source
Then data understanding and pre-processing
Data is about time series and it is Sequential data. so we will consider a data for time series analysis
if there is a missing value we will impute using mean or median
Then convert Date column into datetime format
However quandl already provided a Good data

### Modelling

before starting modelling understand the deep learning approach and RNN-LSTMs  
http://karpathy.github.io/2015/05/21/rnn-effectiveness/
http://colah.github.io/posts/2015-08-Understanding-LSTMs/
https://www.analyticsvidhya.com/blog/2017/12/introduction-to-recurrent-neural-networks/



# Decoding the Sentiment driven Stock market

**Goal of the project:**

The goal of the project is to analyse the stock market data, the financial news headlines over
a period of time in an attempt to identify stocks that generally tend to peak or dip together.
Another objective of the project is to identify stocks that are more sensitive to the financial
news sentiment, and show more volatility based on the news sentiment.


**Datasets Used:**

Ø NIFTY-50 Stock Market Data (https://www.kaggle.com/rohanrao/nifty50-stockmarket-data ): This dataset provides the date wise opening and closing prices of a
stock symbol on the NSE. This dataset had the data for the top 50 stocks on the
NIFTY-50 index.

Ø Indian financial news articles (https://www.kaggle.com/hkapoor/indian-financialnews-articles-20032020 ): This dataset available on Kaggle provided date-wise
financial news headlines and description for these news.


**How to Run Project:**
1) Download DataSet from Kaggle and in **NEWS DataSet remove Description Column**
2) Modify the variables, according to the dataset_path
   DataSets
      
      stock_dataset_path = "<PATH>/*.csv"
  
      news_dataset_path = "<PATH>/IndianFinancialNews.csv" 
3) Run the Entire Notebook, Input Symbol needs to be entered for the final results
  

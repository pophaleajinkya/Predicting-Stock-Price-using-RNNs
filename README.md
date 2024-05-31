# Predicting-Stock-Price-using-RNNs
Our task is to develop recurrent neural network models to predict the stock price of a company of your choice. The goal is to use stock price data (open, high, low, and close data) from the prior 60 days to predict the close price of the stock 5 days into the future.  

First, follow the steps below to download ~15 years of historical data on the stock price of your favorite company.

1. Go to [Yahoo Finance](https://finance.yahoo.com/).
2. Enter a stock symbol into the search field (e.g., AAPL for Apple).
3. Select it in the search results to view it.
4. Click Historical Data.
5. For the Time Period, please enter 01.01.2008 to 10.04.2023.
6. Make sure the Frequency is Daily.
6. Click Apply.
7. Click Download.

For this assignment, you are free to choose any company you like as long as it has 15 years of data (from 01.01.2008 to 10.04.2023). Examples of such companies include: Apple (AAPL), Google (GOOG), Amazon (AMZN), Nvidia (NVDA), Intel (INTC), Microsoft (MSFT), Adobe (ADBE), Netflix (NFLX), etc. You can also choose an ETF, such as the S&P 500 ETF (SPY).  


After you downloaded the historical stock data for a company of your choice, open the `.csv` file with Excel. You should be able to see seven columns: Date, Open, High, Low, Close, Adj Close, Volume.

You should also have 3968 rows in your dataset. The first row contains the headers, and the remaining 3967 rows contain daily stock prices. Note that stock prices are recorded on business days only (not weekends), so the first data point corresponds to 1.2.2008.

If everything looks good, close your Excel file and upload the `.csv` file on your Google Drive, so you can easily import it to your Colab Notebook.

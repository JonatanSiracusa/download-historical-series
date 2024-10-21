# Historical prices download   

In this notebook we will be downloading the historical series of a list of stocks.
In this case, we will download Byma´s stock prices from Yahoo Finance. 

The tickers and Yahoo Finance's tickers to be downloaded are specified in a .xlsx file.

In addition, we will find the next calculations for each asset price:

1. Daily simple (discrete) returns.
2. Daily log (continuous) returns.
3. Volatilities for options strategies: based on the last 40 trading days and Log Returns.

Returns are based on Adj. Close values.

Two files in .csv and .xlsx formats are downloaded.
One contains the Adj. Close prices. The second, contains the Adj. Close prices and the calculations for every value.

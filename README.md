# S-P500-Analysis-for-Year-2017-in-Python
S&amp;P500 Analysis for Year 2017 in Python

This analysis is interested in answering how did 9 tech companies perform relative to the S&P500 Index for Year 2017.

For the S&P500, we'll answer these questions:
1,) Which ticker had the minimum adjusted closing price
2.) Which ticker had the maximum adjusted closing price
3.) Which ticker had the maximum trading volume

For our 9 technology companies, we'll answer these questions:
1.) What is the daily closing price
2.) What is the simple daily percentage change
3.) What is the daily trading volume
4.) What is the daily cumulative return
5.) Which correlated best & least with the S&P500 index
6.) And finally, which tickers out-performed the S&P500 index

The 9 chosen technology companies are Apple, Adobe, AMD, Facebook, F5 Networks, IBM, Google, Microsoft, and Amazon.

To get our data, we'll scrape Yahoo Finance for all of the S&P500 financial tickers and place them into a pandas dataframe. While we could set our time frame for any number of days or years, we'll limit it to just those ones for year 2017.

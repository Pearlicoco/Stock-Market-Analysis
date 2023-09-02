Brief Overview

In this project I will be looking at data from the stock market, particularly some technology stocks like Apple, Microsoft, Amazon and Google. The stock data used for this analysis was imported directly from the web i.e the data was uptodate and not fake data. It was imported from yfinance, a popular open source library to collect stock market data. 

Objectives

1. To Look at a few ways of analyzing the risk of a stock, based on its previous performance history.
2. To check the correlation between the stock prices 
3. To predict future stock prices through the bootstrap and Monte Carlo method!

Questions to be answered

1. What was the change in price of the stock over time?
2. What was the daily return of the stock on average?
3. What was the moving average of the various stocks?
4. What was the correlation between different stocks’ closing prices? 
5. What was the correlation between different stocks’ daily returns? 
6. How much value do we put at risk by investing in a particular stock?

NB: The stock data analyzed was for a year ( from 30/08/2022 to 30/08/2023 )

Tasks carried out

1. Importing the stock data from yfinance
2. Checking the Data Stats and Information
3. Plot out the Closing Price and Volume of the Stocks
4. Calculate the moving average for the stocks.
5. Daily Return Analysis
6. Risk Analysis

Key Findings

1. Using the Apple stock as a casestudy, with quantile method the 0.05 empirical quantile of daily returns is at -0.028. That means that with 95% confidence, our worst daily loss will not exceed 2.8%. For example, If we have a 1 million dollar investment, our one-day 5% VaR is 0.028 * 1,000,000 = $28,000
2. From the analysis, I looked at the 1% empirical quantile of the final price distribution to estimate the Value at Risk for the Google stock, which looks to be $5.41 for every investment of $111.03 (the price of one inital google stock). This basically means for every initial stock you purchase, you are putting about $5.41 at risk 99% of the time from our Monte Carlo Simulation.


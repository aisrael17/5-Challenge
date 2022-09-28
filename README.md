# 5-Challenge
Challenge 5 for the Columbia FinTech Bootcamp

## Technologies
For this project, I used Python 3 and the following external libraries:
* os
* requests
* json
* pandas
* dotenv
* alpaca_trade_api
* MCForecastTools

## Data

For this project, I used API calls to access price data for cryptocurrencies and stocks. 

I used the Free Crypto API endpoints to get closing price data for Bitcoin and Ethereum. 

I also used the Alpaca SDK to access closing price data for the SPDR S&P 500 ETF Trust ($SPY) and the iShares Core US Aggregate Bond ETF ($AGG). 

## Project Description

### Part 1
In part 1 of this project, I used API calls to pull the aforementioned data in order to calculate the value of the member's crypto + stock/bond portfolio. I then compared this target emergency fund value based on the member's monthly income to determine that they do have sufficient money in their portfolio to act as an emergency fund. 

### Part 2
In part 2 of this project, I used the Alpaca SDK to get price data on $SPY and $AGG since 2019. I used the MCSimulation function to simulate the returns of different portfolio weightings over different time horizons to determine whether weighting the portfolio different will allow the member to retire sooner.

# BacktestTrading
Backtesting a  simple trading strategy

I use data downloaded from Yahoo Finance to test the success rate of a 200 SMA + RSI trading strategy.

The requirements to BUY in this strategy are as follows:
1. Overall trend must be up (i.e. price is above the 200 SMA)
2. The 10 period RSI is below 30 (oversold)
3. Buy on next day's open after above criteria has been met
4. Hold position for 10 days before closing or close if RSI goes above 40


# mean-reversion-strategey
This Strategy is based on the concept of mean reversion. Everything in this universe has a tendency to return to its mean value.
This strategy is used for equity derivatives on NSE.
The major scans of this strategy are:
  1. CMP(current market price) > 200 SMA (simple moving average)
  2. % Change of a day prior > 3%
  3. RSI(2) > 50
The output of the script gives us the entry, stoploss and target price of the shortlisted stocks. 

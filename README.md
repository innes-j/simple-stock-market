# simple-stock-market
This code is a submission to the Super Simple Stocks assignment for J.P. Morgan.

# Requirements
Requirements
1. Provide working source code that will :-
  * For a given stock,
      * Given any price as input, calculate the dividend yield
      * Given any price as input, calculate the P/E Ratio
      * Record a trade, with timestamp, quantity of shares, buy or sell indicator and traded price
      * Calculate Volume Weighted Stock Price based on trades in past 15 minutes
  * Calculate the GBCE All Share Index using the geometric mean of prices for all stocks
  
  
# Constraints & Notes
1. Written in one of these languages:
    * Java, C#, C++, Python
2. No database or GUI is required, all data need only be held in memory
3. No prior knowledge of stock markets or trading is required – all formulas are provided below.

# Running the code
The application, written in Python can be run using a wrapper "StockApplication" that has some throwaway code for user input testing.

# Additional notes on the changes
Due to limited time constraints, there are some things that I would have liked to add, namely:<br><br>
Logging: Especially during the trade recording, logging would help with monitoring the trade execution, especially if the exchange was open to more users.<br>
Testing: There are no unit or integration tests, which would suit the application much more than the user inputs currently in place.<br>

# Pine Code Easy Strategy Long Only 
An example of strategy code in Pine Script.

Pine Script V. 5.0 

# How it works 
The condition is constructed as follows. You go long with 100% of the established capital and 0.03% commission. 
- First condition: minimum of the period under analysis falls below the opening level. 
- Second condition: the low of the period is below the low of the previous period.
- The third condition is that the close of the period is above the opening level. 
- Final condition: wants the current close to be higher than the previous open and higher than the previous close. 

I used a statistical approach in the creation of this script, some candlestick patterns that reflect these conditions are: Bullish Engulfing , Bullish Hammer and Morning Star. 

This strategy aims to help traders make more accurate decisions while using candlesticks or bars for their trading and scientifically demonstrates that candlesticks or bars are valid statistical tools for financial analysis. 

The initial capital set is €1,000 (You can change this from the "Properties" section of UI). 
Each individual trade uses 100% of the set capital, in this case €1,000. 
The default commission per trade is 0.03% (You can change this in the "Properties" section of UI). 

# User Interface (UI)
1) General backtest time settings: Set the history period to be analysed 
- StartDate: backtest start date 
- StartMonth: backtest start month 
- StartYear: backtest start year 
- EndDate: backtest end day 
- EndMonth: backtest end month 
- EndYear: backtest end year 
3) Stop Loss 
4) Take Profit 

# Backtesting Tesla 
- Backtesting Tesla 
- Timeframe 4H
- Take Profit: 4.60% 
- Stop Loss: 3.35% 
- Period: 1/1/2008 - 8/3/2022

![Schermata 2022-03-10 alle 20 42 47](https://user-images.githubusercontent.com/100917872/157742267-56167751-5060-405c-b3a4-00f90b5a4783.png)

# Disclaimer 
Be careful, the past is not a guarantee of future performance, so remember to use the script as a pure analysis tool. The developer takes no responsibility for any use other than research and analysis and can in no way be held liable for damages resulting from wrong use of this code.

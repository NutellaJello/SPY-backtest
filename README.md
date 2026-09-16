This introductory project introduces some key research topics involved in quantitative research. 
These ideas include: 
Moving averages and trend-following signals.
Transaction costs, including bid–ask spreads.
Look-ahead bias and correct trade timing.
Development and out-of-sample testing.
Data snooping, overfitting, and parameter sensitivity.
Performance measurement using returns, volatility, Sharpe ratios, and drawdowns.

General findings:
In general, holding SPY produced the highest cummulative return through the development period and test sample. 
A major issue was that the MA results for each pair changed drastically when using the test sample. 
The 50/200 strategy had higher cumulative return, lower volatility, higher sharpe and lower Max drawdown during the development 
as compared to SPY but has lower return, lower volaility, lower sharpe, and the same Max draw down during testing. 
Exact data can be found in the notebook.

This suggests that these strategies fit more towards historical trends rather than an actual strategy.

Parameter Sensitivity analysis revealed that as you increase the long MA, the sharpe ratio across all Short MA generally increased. 
The highest performances typically occured around 200-240 trading days, however, this was a broad tendency and not consistent for every pair. 

Research limitations
the conclusions may depend on the market conditions captured in each period.
Backtest assumptions: results depend on transaction costs, execution timing, treatment of dividends, and whether cash earns interest.
results for SPY may not generalize to other markets.

Future research
Examine how much history is needed for development and testing, and how different periods affect conclusions.
Use walk-forward evaluation. Select parameters using past data, lock them for the next test period, and repeat through time.
Investigate when MA strategies help or hurt. Examine individual trades during prolonged declines, fast recoveries, and sideways markets.

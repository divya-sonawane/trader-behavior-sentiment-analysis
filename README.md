Trader Behavior Analysis Using Market Sentiment
Project Overview

This project analyzes the relationship between market sentiment (Fear & Greed) and trader performance using historical trading data from Hyperliquid.
The goal is to understand how sentiment impacts profitability, risk, and trade behavior.

*Datasets

Historical Trader Data
Trade-level execution data including price, size, side, and closed PnL.
Bitcoin Fear & Greed Index
Daily sentiment labels representing overall market psychology.

*Objective

Study trader performance during Fear vs Greed periods
Identify patterns in profitability, win rate, and trade direction
Extract insights that can help design sentiment-aware trading strategies

*Tools & Technologies

Python
Pandas, NumPy
Matplotlib
Google Colab

*Data Preparation

Converted timestamps into datetime format
Created a common trade_date for merging datasets
Cleaned and renamed columns for consistency
Removed unnecessary columns and handled missing values
Merged trader data with sentiment data using trade date

*Key Insights

Trades during Greed periods show higher average profitability
Fear periods exhibit higher volatility and risk
BUY trades perform better during Greed, while SELL trades are relatively safer during Fear
Win rate is higher during Greed compared to Fear
Market sentiment acts as a strong contextual indicator for trade performance

*Limitations

Sentiment is analyzed at a daily level
No leverage or holding-time based strategy analysis
Observational analysis (not predictive)

*Future Scope

Add sentiment intensity scores
Trader-level behavior clustering
Sentiment-based strategy simulation
Risk-adjusted performance metrics

*How to Run

Open the notebook in Google Colab
Upload the required CSV files
Run cells sequentially

*Conclusion

This analysis demonstrates that market sentiment plays a meaningful role in trader performance.
Greed periods tend to be more profitable with higher win rates, while Fear periods introduce higher risk and uncertainty.
Understanding this relationship can help traders and platforms design more adaptive and sentiment-aware trading strategies.

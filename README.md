Trading Behavior Analysis vs Market Sentiment
Objective:-
Analyze how trading behavior (profitability, risk, leverage, size, timing) aligns or diverges from market sentiment (Fear vs Greed), using two main datasets:

Trade History (historical_data.csv)

Fear & Greed Index (fear_greed_index.csv)

Datasets:-
1. historical_data.csv
Contains detailed trade-level data:

Timestamp IST

Closed PnL

Leverage

Size USD / Size Tokens

Direction, Symbol, and other features

2. fear_greed_index.csv
Includes:

date

value → sentiment score (0–100)

classification → categories like Fear, Greed, Neutral

These were joined on date to add sentiment labels to each trade.

For insights kindly refer to the Insights.docs and the plots are stored in outputs folder

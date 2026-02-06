# PrimeTradeAI – Trader Behavior vs Market Sentiment

# Overview
This project analyzes how trader performance and behavior change based on market sentiment (Fear vs Greed).  
It also clusters traders into behavioral archetypes using trade-level features.

# Objectives
1. Compare performance across sentiment regimes:
   - PnL
   - Win rate
   - Loss frequency (drawdown proxy)

2. Analyze behavior changes:
   - Trade frequency
   - Trade size
   - Long/short bias

3. Build a simple predictive model.

4. Cluster traders into behavioral archetypes.



# Dataset
Two main sources:
- Trader-level trade data
- Daily sentiment classification (Fear / Greed)

Merged into a final dataset: `final_df`.



# Methodology

# 1. Feature Engineering
Created metrics per trader/day:
- `closed pnl`
- `trade_count`
- `avg_trade_size`
- `long_ratio`
- `win` and `loss` indicators

# 2. Sentiment Analysis
Grouped results by:
- Fear days
- Greed days

Compared:
- Average PnL
- Win rate
- Loss frequency
- Trade behavior



# 3. Trader Clustering
Used KMeans clustering on:
- Trade frequency
- Average trade size
- Long ratio
- Average PnL

Identified behavioral archetypes.



# Key Insights (Summary)
- Trader performance differs across sentiment regimes.
- Risk-taking increases during Greed periods.
- Some traders remain consistent across sentiment shifts.
- Clustering reveals distinct trader types.





#Objective
The goal of this project was to analyze how trader performance and behavior change under different market sentiment conditions, specifically during Fear and Greed periods, using trade-level data and a market sentiment index.

#Methodology
1.Data Preparation
2.Cleaned trade and sentiment datasets.
3.Converted timestamps to date format.
4.Merged trade data with daily sentiment classification.

#Feature Engineering
1.Created behavioral and performance metrics:
2.Daily closed PnL
3.Win and loss indicators
4.Trade count per day
5.Average trade size
6.Long/short ratio

#Performance Analysis
1.Compared key metrics across Fear vs Greed days:
2.Average PnL
3.Win rate
4.Loss frequency (drawdown proxy)

#Behavioral Analysis
1.Evaluated how trader actions changed across sentiment:
2.Trade frequency
3.Position sizing
4.Directional bias

#Clustering (Exploratory)
Attempted to group traders into behavioral archetypes using aggregated features such as:
-Average PnL
-Trade size
-Long ratio
-Trading frequency

#Key Insights
-Performance varied across sentiment regimes
-Traders showed differences in average PnL and win rates between Fear and Greed periods.
-Loss frequency tended to increase during more extreme sentiment conditions, indicating higher volatility and risk.
-Behavioral shifts were visible during sentiment changes
-Trade frequency and average trade size changed between Fear and Greed days.
-Directional bias (long vs short) also shifted, suggesting traders adapt strategies based on market mood.
-Distinct trader behavior patterns exist
-Some traders were high-frequency, small-size participants.
-Others took fewer but larger positions.
-These patterns indicate the presence of different trader archetypes in the dataset.

#Strategy Recommendations
1. Sentiment-Adaptive Position Sizing
Reduce average trade size during extreme Fear or Greed periods.Increase exposure during neutral or stable sentiment.
This can help control drawdowns during volatile phases.

2. Behavioral-Based Trader Segmentation
Classify traders into behavioral archetypes (e.g., high-frequency, directional, conservative).
Apply different risk limits or strategy rules for each segment.
This allows more targeted risk management and performance optimization.


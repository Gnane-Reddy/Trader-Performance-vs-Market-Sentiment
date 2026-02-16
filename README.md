Trader Behavior & Market Sentiment Analysis

1.Overview

This project analyzes trader performance and behavior using historical trading data and examines market sentiment trends from the Bitcoin Fear & Greed Index to derive actionable insights.

2.Datasets

Fear & Greed Index: Daily sentiment classifications (Fear / Greed), 2018–2025

Trader Historical Data: Trade-level PnL and direction (Long / Short)

⚠️ Note: Trade timestamps were irreversibly mapped to Unix epoch (1970-01-01), so direct date-based merging was avoided to maintain data integrity.

3.Methodology

Data cleaning and standardization

Trader performance analysis (PnL, win rate, directional bias)

Independent sentiment trend analysis

Bonus:

Profitability bucket prediction

PnL volatility classification

Behavioral clustering using KMeans

4.Key Insights

Trader profitability is highly skewed with frequent small losses

Long and short trades show distinct performance patterns

Sentiment regimes highlight prolonged Fear and Greed cycles

Behavioral clustering reveals conservative vs aggressive archetypes

5.How to Run

Open the notebook in Google Colab

Upload:

fear_greed_index.csv

historical_data.csv

Run all cells from top to bottom

6.Tech Stack

Python, pandas, numpy, matplotlib, seaborn, scikit-learn

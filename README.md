# Data Science Assignment: Trader Behavior Insights

## Overview
This repository contains the submission for the Junior Data Scientist assignment focused on analyzing the relationship between Bitcoin Market Sentiment and Historical Trader Data from Hyperliquid.

**Objective:** Explore how trader profitability (PnL) and volume align or diverge from the daily Fear & Greed Index to identify strategic trading signals.

## Deliverables
* `notebook_1.ipynb`: The primary analysis script (linked via Google Colab).
* `ds_report.pdf`: Summarized findings and strategic recommendations.
* `outputs/`: Contains the generated visualizations of the analysis.

## Analysis Steps
1.  **Data Preparation:** Cleaned and merged daily sentiment data with daily aggregated trader performance (PnL and Volume).
2.  **EDA:** Analyzed the average daily profitability and average daily trading volume across the five sentiment classifications (Extreme Fear, Fear, Neutral, Greed, Extreme Greed).
3.  **Key Finding:** Discovered a clear contrarian signal: the highest profits are realized during periods of Fear, while the largest losses are incurred during periods of Greed.

## Setup
All required libraries can be installed via the standard Conda or Pip setup.
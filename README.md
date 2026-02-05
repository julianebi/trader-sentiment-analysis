# Trader Performance vs Market Sentiment

## Objective
Analyze how market sentiment (Fear/Greed) impacts trader behavior and performance on Hyperliquid, and derive actionable trading insights.

## Datasets
- Bitcoin Market Sentiment (Fear / Greed Index)
- Historical Trader Data from Hyperliquid

## Methodology
1. Cleaned and validated both datasets (missing values, duplicates).
2. Aggregated trader activity to daily level.
3. Merged trader metrics with daily market sentiment.
4. Computed KPIs such as:
   - Daily PnL
   - Win rate
   - Trade frequency
   - Average trade size
   - Long/short bias
5. Analyzed behavioral and performance changes across sentiment regimes.

## Key Insights
- Trading activity spikes during Fear, but average PnL declines.
- Greed periods show fewer trades with higher profitability.
- Emotional overtrading during Fear negatively impacts performance.
- Conviction-based trading during Greed improves outcomes.

## Strategy Recommendations
- Reduce leverage and trade frequency during Fear periods.
- Increase position size selectively during Greed with strong setups.
- Apply sentiment-aware risk scaling to improve capital preservation.

## How to Run
pip install -r requirements.txt

Open analysis.ipynb inside the Notebook folder and run all cells.

## Outputs
outputs/sentiment_summary.csv

Visual insights embedded in the notebook

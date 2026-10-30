# Commodity News Coverage

How does the Guardian's coverage of geopolitical crises relate to commodity prices?

Group project for ST115 (Managing and Visualising Data), LSE, 2026. Group of four.

## What's in it
- **Data:** 6,515 Guardian articles (Jan 2020 – Mar 2026, via the Guardian API) and weekly
  prices for Brent oil, gold, natural gas and wheat (via yfinance)
- **Analysis:** data quality checks, cleaning, exploratory analysis and visualisations answering:
  1. How does coverage change around geopolitical events?
  2. Which commodities get the most attention, and how has that shifted?
  3. Is there a visible relationship between coverage and prices?

## Run it
Add your own Guardian API key to `keys.json` as `{"guardian": "YOUR_KEY"}`,
then open `st115-merged.ipynb`.

Built with Python, pandas and matplotlib.

# Trader Performance Under Bitcoin Market Sentiment

This project explores how Bitcoin market sentiment (Fear vs Greed) affects trader
behavior and performance on Hyperliquid.

Rather than trying to predict Bitcoin price, I treat sentiment as a **market regime**
and analyze how traders adapt (or fail) when conditions change.

# Datasets
1.Daily Bitcoin Fear–Greed sentiment data
2.Trade-level historical data from Hyperliquid

# What I Focused On
- Performance differences between Fear and Greed regimes
- The role of leverage in trader drawdowns
- Identifying traders whose performance is stable across regimes

# Key Insight
Most traders perform well during Greed but give back profits during Fear.
The strongest traders are not the most aggressive ones, but those who adjust risk
when sentiment shifts.

# Files
- `analysis.ipynb` – full analysis and results
- `requirements.txt` – Python dependencies
- `data/` – dataset folder (data not included)

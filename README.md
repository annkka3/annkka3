# Anna Gromyko

**Data Analyst · Quant Analytics · Prop Trading Platforms**

I build end-to-end analytics systems for financial data — from synthetic data generation and SQL pipelines to feature engineering, scoring frameworks, and visual reporting. My recent work focuses on prop trading platform analytics: trader quality, funnel economics, and anomaly detection.

---

## Featured Projects

### [AI-btc-indicator](https://github.com/annkka3/BTC_indicator)
End-to-end ML system for Bitcoin price forecasting across 1h, 4h, and 24h horizons. Combines OHLCV data, perpetuals (funding rate, OI, liquidations), DXY, and ETF flows into a feature pipeline that predicts log-residual deviation from trend. Delivered as a Telegram bot with explainable report cards, regime detection, and divergence signals. Architecture: Clean Architecture with FastAPI, RabbitMQ workers, SQLite (WAL), Docker Compose, and walk-forward validation with leakage guards.

`Python` `FastAPI` `CatBoost` `LightGBM` `Docker` `RabbitMQ` `SQLite` `Telegram Bot API`

---

### [trader-performance-analytics](https://github.com/annkka3/trader-performance-analytics)
Quant analytics case study for a challenge-based prop trading platform. Builds an interpretable multi-dimensional trader quality framework — expectancy, drawdown control, discipline, consistency, regime resilience — and shows why win rate alone is a poor quality signal.

`Python` `DuckDB` `SQL` `pandas` `matplotlib`

### [trader-anomaly-detection](https://github.com/annkka3/trader-anomaly-detection)
Anomaly detection system for identifying coordinated account rings and suspicious payout patterns. Produces a composite suspicious score (0–100) from five behavioural components, with review priority segmentation and channel-level risk breakdown.

`Python` `DuckDB` `SQL` `feature engineering`

### [prop-product-ab-testing](https://github.com/annkka3/prop-product-ab-testing)
A/B test analysis for a challenge type expansion on a prop trading platform. Covers conversion, funded rate, payout rate, and challenge mix economics — including the nuance that higher conversion in the treatment group can offset a lower average fee per purchaser.

`Python` `DuckDB` `SQL` `A/B testing` `revenue analysis`

---

## Stack

| Area | Tools |
|---|---|
| Data & SQL | Python, DuckDB, SQL (CTEs, window functions) |
| Analysis | pandas, NumPy, scikit-learn |
| Visualisation | matplotlib, seaborn |
| Workflow | Jupyter, Git |

---

## Languages

Русский · English

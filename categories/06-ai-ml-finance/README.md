# 06. AI & ML Finance

Subagents for machine learning, deep learning, and AI-driven financial analysis and prediction.

## Available Subagents

| Agent | Model | Description |
|-------|-------|-------------|
| [anomaly-detection-expert](anomaly-detection-expert.md) | sonnet | Market anomaly detection, regime change identification, outlier analysis |
| [deep-learning-quant](deep-learning-quant.md) | opus | CNN, RNN, Transformer-based financial prediction models |
| [feature-engineering-specialist](feature-engineering-specialist.md) | sonnet | Financial feature creation, selection, importance, and pipeline design |
| [reinforcement-learning-trader](reinforcement-learning-trader.md) | opus | DQN, PPO, A3C trading policy optimization and RL environments |
| [sentiment-analysis-expert](sentiment-analysis-expert.md) | sonnet | NLP-based news and social media sentiment analysis for trading |
| [time-series-forecaster](time-series-forecaster.md) | opus | ARIMA, GARCH, Prophet, LSTM, Transformer time series forecasting |

## Quick Selection Guide

| Need | Use Agent |
|------|-----------|
| Price/return forecasting | `time-series-forecaster` |
| RL-based trading policy | `reinforcement-learning-trader` |
| News/social sentiment | `sentiment-analysis-expert` |
| Deep learning models | `deep-learning-quant` |
| Feature pipeline design | `feature-engineering-specialist` |
| Anomaly/regime detection | `anomaly-detection-expert` |

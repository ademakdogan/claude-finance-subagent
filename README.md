# 📈 Claude Finance Subagents

The definitive collection of finance-focused Claude Code subagents — specialized AI assistants for technical analysis, trading strategies, risk management, fundamental analysis, quantitative methods, and AI-driven market intelligence.

![Subagent Count](https://img.shields.io/badge/subagents-41+-blue?style=flat-square)
[![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)](LICENSE)

## Installation

### Option 1: Manual Installation

1. Clone this repository
2. Copy desired agent files to:
   - `~/.claude/agents/` for global access
   - `.claude/agents/` for project-specific use
3. Customize based on your project requirements

### Option 2: Selective Install
```bash
# Install specific category
cp categories/01-technical-indicators/*.md ~/.claude/agents/

# Install specific agent
cp categories/01-technical-indicators/rsi-analyst.md ~/.claude/agents/
```

## 📚 Categories

### [01. Technical Indicators](categories/01-technical-indicators/)

Subagents specialized in technical indicator calculation, interpretation, and strategy development.

- [**atr-volatility-expert**](categories/01-technical-indicators/atr-volatility-expert.md) — ATR-based volatility analysis and position sizing
- [**bollinger-bands-expert**](categories/01-technical-indicators/bollinger-bands-expert.md) — Bollinger Bands squeeze/breakout and bandwidth analysis
- [**ichimoku-cloud-expert**](categories/01-technical-indicators/ichimoku-cloud-expert.md) — Ichimoku Cloud multi-component trend analysis
- [**macd-strategist**](categories/01-technical-indicators/macd-strategist.md) — MACD crossover strategies and divergence detection
- [**moving-average-specialist**](categories/01-technical-indicators/moving-average-specialist.md) — SMA, EMA, WMA, DEMA, TEMA crossover strategies
- [**rsi-analyst**](categories/01-technical-indicators/rsi-analyst.md) — RSI overbought/oversold and divergence analysis
- [**stochastic-oscillator-pro**](categories/01-technical-indicators/stochastic-oscillator-pro.md) — Stochastic %K/%D analysis and signal generation
- [**volume-profile-analyst**](categories/01-technical-indicators/volume-profile-analyst.md) — VWAP, OBV, and volume profile analysis

### [02. Chart Patterns](categories/02-chart-patterns/)

Subagents for chart pattern recognition, support/resistance, and geometric analysis.

- [**candlestick-pattern-pro**](categories/02-chart-patterns/candlestick-pattern-pro.md) — Japanese candlestick pattern recognition and interpretation
- [**chart-pattern-detector**](categories/02-chart-patterns/chart-pattern-detector.md) — Classical chart pattern detection (H&S, triangles, wedges)
- [**elliott-wave-analyst**](categories/02-chart-patterns/elliott-wave-analyst.md) — Elliott Wave Theory wave counting and analysis
- [**fibonacci-specialist**](categories/02-chart-patterns/fibonacci-specialist.md) — Fibonacci retracement, extension, and fan analysis
- [**harmonic-pattern-expert**](categories/02-chart-patterns/harmonic-pattern-expert.md) — Harmonic pattern detection (Gartley, Butterfly, Bat, Crab)
- [**support-resistance-analyst**](categories/02-chart-patterns/support-resistance-analyst.md) — Support/resistance level detection and pivot points
- [**trendline-expert**](categories/02-chart-patterns/trendline-expert.md) — Trend line drawing, channels, and breakout analysis

### [03. Risk Management](categories/03-risk-management/)

Subagents for position sizing, portfolio risk, and drawdown control.

- [**correlation-risk-expert**](categories/03-risk-management/correlation-risk-expert.md) — Asset correlation analysis and systematic risk measurement
- [**drawdown-controller**](categories/03-risk-management/drawdown-controller.md) — Maximum drawdown monitoring and equity curve analysis
- [**portfolio-risk-manager**](categories/03-risk-management/portfolio-risk-manager.md) — Portfolio diversification and risk parity optimization
- [**position-sizing-expert**](categories/03-risk-management/position-sizing-expert.md) — Kelly Criterion, fixed fractional, and optimal f sizing
- [**stop-loss-strategist**](categories/03-risk-management/stop-loss-strategist.md) — Trailing stop, ATR-based, and time-based stop strategies
- [**var-analyst**](categories/03-risk-management/var-analyst.md) — Value at Risk calculation (historical, parametric, Monte Carlo)

### [04. Fundamental Analysis](categories/04-fundamental-analysis/)

Subagents for financial statement analysis, valuation, and macroeconomic assessment.

- [**earnings-analyst**](categories/04-fundamental-analysis/earnings-analyst.md) — Earnings estimates, EPS surprise, and guidance analysis
- [**financial-statement-analyst**](categories/04-fundamental-analysis/financial-statement-analyst.md) — Balance sheet, income statement, and ratio analysis
- [**macro-economist**](categories/04-fundamental-analysis/macro-economist.md) — Interest rates, inflation, GDP, and central bank policy
- [**sector-analyst**](categories/04-fundamental-analysis/sector-analyst.md) — Sector rotation, competitive analysis, and supply chain
- [**valuation-expert**](categories/04-fundamental-analysis/valuation-expert.md) — DCF, P/E, P/B, EV/EBITDA valuation models

### [05. Quantitative Strategies](categories/05-quantitative-strategies/)

Subagents for backtesting, algorithmic trading, and quantitative strategy development.

- [**algorithmic-trading-expert**](categories/05-quantitative-strategies/algorithmic-trading-expert.md) — Algo trading engine design and execution optimization
- [**backtesting-engineer**](categories/05-quantitative-strategies/backtesting-engineer.md) — Backtest framework, walk-forward, and Monte Carlo simulation
- [**mean-reversion-specialist**](categories/05-quantitative-strategies/mean-reversion-specialist.md) — Mean reversion strategies, half-life, and z-score analysis
- [**momentum-strategist**](categories/05-quantitative-strategies/momentum-strategist.md) — Momentum factor, trend following, and breakout strategies
- [**pairs-trading-expert**](categories/05-quantitative-strategies/pairs-trading-expert.md) — Pairs selection, hedge ratio, and entry/exit signals
- [**statistical-arbitrage-pro**](categories/05-quantitative-strategies/statistical-arbitrage-pro.md) — Statistical arbitrage, cointegration, and spread trading

### [06. AI & ML Finance](categories/06-ai-ml-finance/)

Subagents for machine learning, deep learning, and AI-driven financial analysis.

- [**anomaly-detection-expert**](categories/06-ai-ml-finance/anomaly-detection-expert.md) — Market anomaly detection and regime change identification
- [**deep-learning-quant**](categories/06-ai-ml-finance/deep-learning-quant.md) — CNN, RNN, Transformer-based financial prediction
- [**feature-engineering-specialist**](categories/06-ai-ml-finance/feature-engineering-specialist.md) — Financial feature creation, selection, and importance analysis
- [**reinforcement-learning-trader**](categories/06-ai-ml-finance/reinforcement-learning-trader.md) — DQN, PPO, A3C trading policy optimization
- [**sentiment-analysis-expert**](categories/06-ai-ml-finance/sentiment-analysis-expert.md) — NLP-based news and social media sentiment analysis
- [**time-series-forecaster**](categories/06-ai-ml-finance/time-series-forecaster.md) — ARIMA, GARCH, Prophet, LSTM, Transformer forecasting

### [07. Market Data](categories/07-market-data/)

Subagents for market data engineering, order book analysis, and alternative data.

- [**alternative-data-specialist**](categories/07-market-data/alternative-data-specialist.md) — Satellite, social, web scraping, and non-traditional data
- [**market-data-engineer**](categories/07-market-data/market-data-engineer.md) — Data collection, normalization, real-time feeds, and APIs
- [**order-book-analyst**](categories/07-market-data/order-book-analyst.md) — Level 2 data analysis, market microstructure, and liquidity

## 🤖 Understanding Finance Subagents

Finance subagents are specialized AI assistants that enhance Claude Code's capabilities by providing deep financial domain expertise. They act as dedicated helpers for specific areas of financial analysis and trading.

### What Makes Finance Subagents Special?

**Domain-Specific Intelligence**
Each subagent is equipped with carefully crafted instructions specific to its financial domain — from technical indicator formulas to risk model mathematics.

**Independent Context Windows**
Every subagent operates within its own isolated context, preventing cross-contamination between different analytical tasks.

**Inter-Agent Collaboration**
Subagents can reference and work with each other. For example, `backtesting-engineer` can invoke `rsi-analyst` for indicator calculation within a strategy backtest.

### Getting Started
```bash
> Have the rsi-analyst analyze AAPL's daily chart for divergences
> Ask the backtesting-engineer to backtest a MACD crossover strategy
> Use the reinforcement-learning-trader to optimize a trading policy
```

## 📖 Subagent Structure

Each subagent follows a standardized template:

```yaml
---
name: subagent-name
description: When this agent should be invoked
tools: Read, Write, Edit, Bash, Glob, Grep
model: opus
---

You are a [role description and expertise areas]...

[Agent-specific checklists, patterns, and guidelines]...

## Communication Protocol
Inter-agent communication specifications...

## Development Workflow
Structured implementation phases...
```

## ⚠️ Disclaimer

These subagents are educational tools and should not be considered financial advice. Trading and investing involve substantial risk of loss. Always do your own research and consult with qualified financial professionals before making investment decisions.

## 🤝 Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

- Submit new subagents via PR
- Improve existing definitions
- Report issues and bugs

## 📄 License

MIT License — see [LICENSE](LICENSE)

# 01. Technical Indicators

Subagents specialized in technical indicator calculation, interpretation, and trading strategy development.

## Available Subagents

| Agent | Model | Description |
|-------|-------|-------------|
| [atr-volatility-expert](atr-volatility-expert.md) | sonnet | ATR-based volatility measurement, volatility-adjusted stop-losses, and position sizing |
| [bollinger-bands-expert](bollinger-bands-expert.md) | sonnet | Bollinger Bands squeeze/breakout detection, bandwidth analysis, and %B calculations |
| [ichimoku-cloud-expert](ichimoku-cloud-expert.md) | sonnet | Full Ichimoku Cloud system analysis with Tenkan-sen, Kijun-sen, Senkou Span, Chikou Span |
| [macd-strategist](macd-strategist.md) | sonnet | MACD line/signal crossover strategies, histogram analysis, and divergence detection |
| [moving-average-specialist](moving-average-specialist.md) | sonnet | SMA, EMA, WMA, DEMA, TEMA calculations, crossover strategies, and dynamic support/resistance |
| [rsi-analyst](rsi-analyst.md) | sonnet | RSI calculation, overbought/oversold analysis, bullish/bearish divergence detection |
| [stochastic-oscillator-pro](stochastic-oscillator-pro.md) | sonnet | Stochastic %K/%D analysis, overbought/oversold signals, and crossover strategies |
| [volume-profile-analyst](volume-profile-analyst.md) | sonnet | VWAP, OBV, volume profile, accumulation/distribution, and volume-price analysis |

## Quick Selection Guide

| Need | Use Agent |
|------|-----------|
| Momentum measurement | `rsi-analyst`, `stochastic-oscillator-pro` |
| Trend identification | `macd-strategist`, `moving-average-specialist`, `ichimoku-cloud-expert` |
| Volatility analysis | `bollinger-bands-expert`, `atr-volatility-expert` |
| Volume analysis | `volume-profile-analyst` |
| Multi-indicator system | `ichimoku-cloud-expert` |
| Divergence detection | `rsi-analyst`, `macd-strategist` |
| Stop-loss placement | `atr-volatility-expert` |

## Usage Examples

```
> Have the rsi-analyst check for divergences on AAPL daily chart
> Ask the macd-strategist to design a crossover strategy for crypto
> Use the bollinger-bands-expert to identify squeeze setups
> Get the ichimoku-cloud-expert to provide a full trend analysis
```

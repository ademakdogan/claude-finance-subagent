# 03. Risk Management

Subagents for position sizing, portfolio risk analysis, drawdown control, and risk quantification.

## Available Subagents

| Agent | Model | Description |
|-------|-------|-------------|
| [correlation-risk-expert](correlation-risk-expert.md) | opus | Asset correlation analysis, beta calculation, and systematic risk measurement |
| [drawdown-controller](drawdown-controller.md) | sonnet | Maximum drawdown monitoring, equity curve analysis, and capital preservation |
| [portfolio-risk-manager](portfolio-risk-manager.md) | opus | Portfolio diversification, risk parity, and multi-asset risk optimization |
| [position-sizing-expert](position-sizing-expert.md) | sonnet | Kelly Criterion, fixed fractional, optimal f, and volatility-based sizing |
| [stop-loss-strategist](stop-loss-strategist.md) | sonnet | Trailing stop, ATR-based stop, time-based stop, and exit strategy design |
| [var-analyst](var-analyst.md) | opus | Value at Risk (historical, parametric, Monte Carlo), CVaR, Expected Shortfall |

## Quick Selection Guide

| Need | Use Agent |
|------|-----------|
| How much to risk per trade | `position-sizing-expert` |
| Portfolio-level risk | `portfolio-risk-manager` |
| Stop-loss placement | `stop-loss-strategist` |
| Drawdown monitoring | `drawdown-controller` |
| Value at Risk calculation | `var-analyst` |
| Correlation and beta analysis | `correlation-risk-expert` |

## Usage Examples

```
> Have the position-sizing-expert calculate optimal size for a $50k account
> Ask the var-analyst to compute 95% VaR for my portfolio
> Use the drawdown-controller to analyze my equity curve for risk breaches
> Get the stop-loss-strategist to design ATR-based trailing stops
```

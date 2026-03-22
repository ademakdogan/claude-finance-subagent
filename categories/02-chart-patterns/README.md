# 02. Chart Patterns

Subagents for chart pattern recognition, support/resistance analysis, and geometric price analysis.

## Available Subagents

| Agent | Model | Description |
|-------|-------|-------------|
| [candlestick-pattern-pro](candlestick-pattern-pro.md) | sonnet | Japanese candlestick pattern recognition (doji, engulfing, hammer, etc.) |
| [chart-pattern-detector](chart-pattern-detector.md) | sonnet | Classical chart patterns (Head & Shoulders, triangles, wedges, flags) |
| [elliott-wave-analyst](elliott-wave-analyst.md) | opus | Elliott Wave Theory wave counting and impulse/corrective analysis |
| [fibonacci-specialist](fibonacci-specialist.md) | sonnet | Fibonacci retracement, extension, fan, arc, and time zone analysis |
| [harmonic-pattern-expert](harmonic-pattern-expert.md) | opus | Harmonic pattern detection (Gartley, Butterfly, Bat, Crab, Shark) |
| [support-resistance-analyst](support-resistance-analyst.md) | sonnet | Automated support/resistance detection and pivot point analysis |
| [trendline-expert](trendline-expert.md) | sonnet | Trend line drawing, channel construction, and breakout analysis |

## Quick Selection Guide

| Need | Use Agent |
|------|-----------|
| Support/resistance levels | `support-resistance-analyst` |
| Trend direction and channels | `trendline-expert` |
| Price targets with Fibonacci | `fibonacci-specialist` |
| Reversal candlestick signals | `candlestick-pattern-pro` |
| Complex harmonic patterns | `harmonic-pattern-expert` |
| Wave structure analysis | `elliott-wave-analyst` |
| Classical patterns (H&S, triangles) | `chart-pattern-detector` |

## Usage Examples

```
> Have the support-resistance-analyst find key levels on BTC daily
> Ask the fibonacci-specialist for retracement levels after the recent swing
> Use the harmonic-pattern-expert to scan for Gartley patterns
> Get the elliott-wave-analyst to count the current wave structure
```

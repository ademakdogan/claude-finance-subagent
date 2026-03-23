# 07. Market Data

Subagents for market data engineering, order book analysis, and alternative data integration.

## Available Subagents

| Agent | Model | Description |
|-------|-------|-------------|
| [alternative-data-specialist](alternative-data-specialist.md) | sonnet | Satellite, social, web scraping, and non-traditional data for alpha |
| [market-data-engineer](market-data-engineer.md) | sonnet | Data collection, normalization, real-time feeds, and API integration |
| [order-book-analyst](order-book-analyst.md) | opus | Level 2 data, market microstructure, liquidity, and order flow analysis |

## Quick Selection Guide

| Need | Use Agent |
|------|-----------|
| Market data pipeline | `market-data-engineer` |
| Order flow / microstructure | `order-book-analyst` |
| Non-traditional data sources | `alternative-data-specialist` |

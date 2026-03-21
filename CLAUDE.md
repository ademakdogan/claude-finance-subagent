# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a curated collection of finance-specific Claude Code subagent definitions — specialized AI assistants designed for financial analysis, trading, risk management, and AI-driven market intelligence. Subagents are markdown files with YAML frontmatter that Claude Code can load and use.

## Repository Structure

```
categories/
  01-technical-indicators/    # RSI, MACD, Bollinger, Moving Averages, etc.
  02-chart-patterns/          # Support/Resistance, Fibonacci, Elliott Wave, etc.
  03-risk-management/         # Position sizing, VaR, drawdown control, etc.
  04-fundamental-analysis/    # Financial statements, valuation, macro economics
  05-quantitative-strategies/ # Backtesting, algo trading, statistical arbitrage
  06-ai-ml-finance/           # Reinforcement learning, time series, sentiment
  07-market-data/             # Market data engineering, order book, alt data
```

## Subagent File Format

Each subagent follows this template:

```yaml
---
name: agent-name
description: When this agent should be invoked (used by Claude Code for auto-selection)
tools: Read, Write, Edit, Bash, Glob, Grep
model: opus
---

You are a [role description]...

[Agent-specific checklists, patterns, guidelines]

## Communication Protocol
[Inter-agent communication specs]

## Development Workflow
[Structured implementation phases]
```

### Tool Assignment by Role Type

- **Read-only** (analysts, reviewers): `Read, Grep, Glob`
- **Research** (market researchers): `Read, Grep, Glob, WebFetch, WebSearch`
- **Code writers** (engineers, developers): `Read, Write, Edit, Bash, Glob, Grep`
- **Documentation**: `Read, Write, Edit, Glob, Grep, WebFetch, WebSearch`

### Model Selection by Complexity

| Model | When It's Used | Examples |
|-------|----------------|----------|
| `opus` | Deep financial reasoning — risk modeling, derivatives pricing | `var-analyst`, `statistical-arbitrage-pro`, `reinforcement-learning-trader` |
| `sonnet` | Standard analysis — indicators, pattern detection, backtesting | `rsi-analyst`, `macd-strategist`, `backtesting-engineer` |
| `haiku` | Quick tasks — data checks, simple calculations | `market-data-engineer`, `volume-profile-analyst` |

## Contributing a New Subagent

When adding a new agent, update these files:

1. **Main README.md** — Add link in appropriate category (alphabetical order)
2. **Category README.md** — Add detailed description, update Quick Selection Guide table
3. **Agent .md file** — Create the actual agent definition

Format for main README: `- [**agent-name**](path/to/agent.md) - Brief description`

## Subagent Storage in Claude Code

| Type | Path | Scope |
|------|------|-------|
| Project | `.claude/agents/` | Current project only |
| Global | `~/.claude/agents/` | All projects |

Project subagents take precedence over global ones with the same name.

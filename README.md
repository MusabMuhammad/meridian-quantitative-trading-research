# MERIDIAN
### A Quantitative Investigation into Systematic Trading

**What happens when a systematic trading system trades four markets that are all falling?**

Between January and September 2026, MERIDIAN was evaluated across Bitcoin, Ethereum, gold, and silver in a single-account historical backtest.

The results raised a more interesting question than profitability alone:

**Was the observed performance evidence of a genuine trading edge—or a product of how the system was developed and tested?**

This paper investigates that question.

---

## The Research

The study evaluates a proprietary systematic trading program across four CFD markets, using five-minute historical data and a shared portfolio with explicit risk constraints.

The analysis examines:

- Performance across 716 closed trades
- Profitability across markets, months, and trade directions
- Drawdown, compounding, and position sizing
- Transaction costs and execution assumptions
- Bootstrap resampling and sensitivity to trade sequencing
- Statistical uncertainty, parameter selection, and backtest overfitting

The trading rules and parameters remain proprietary. The objective is to present the empirical findings and examine their limitations without disclosing the underlying strategy.

## Selected Results

| Metric | Historical backtest |
|---|---:|
| Evaluation period | Jan–Sep 2026 |
| Markets | BTCUSD, ETHUSD, XAUUSD, XAGUSD |
| Closed trades | 716 |
| Simulated net return | +339.9% |
| Maximum mark-to-market drawdown | 13.5% |
| Profit factor | 1.39 |
| Positive calendar months | 9 of 9 |
| Broker | Exness |

*These figures represent hypothetical historical backtest performance, not live trading results. The system was refined using the evaluation sample, and independent out-of-sample validation has not yet been established.*

## Read the Full Paper

**The complete research paper is the sole publication in this repository.**

It documents the testing framework, empirical results, robustness analysis, risk characteristics, development history, and the reasons the findings must be interpreted cautiously.

Rather than presenting a performance number in isolation, the paper examines the evidence behind it—and what remains unproven.

**[→ Read the MERIDIAN Research Paper](./MERIDIAN_Research_Paper.pdf)**

## About MERIDIAN

MERIDIAN is a quantitative research initiative focused on systematic trading, empirical evaluation, and risk-aware portfolio design.

The research prioritizes measurable evidence, reproducible calculations, and transparent discussion of model limitations while keeping proprietary trading rules confidential.

## Disclaimer

This repository is provided for research and informational purposes only. All performance figures are hypothetical and derived from historical backtesting. They do not represent actual trading results or guarantee future performance. Backtests are subject to selection bias, execution assumptions, transaction costs, and market-regime limitations. Leveraged CFDs carry substantial risk. Nothing in this repository constitutes investment advice or an offer to invest.

© 2026 Meridian. All rights reserved.

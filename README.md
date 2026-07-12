# Qualbot — Live-Config Backtest Reports

Interactive backtest report for a long-only momentum-breakout swing strategy (Qullamaggie-style),
deployed live on Alpaca (US equities).

- **[Alpaca — US equities](https://boraodbsi.github.io/qualbot-backtests/alpaca-live-baseline/)**

Click any trade in the report to open its entry/exit candlestick chart.

- Period 2023-01-01 → 2026-06-19, daily point-in-time universe snapshots (survivorship-bias-controlled).
- Matches the deployed live configuration, **including the industry-group strength gate** (signals from
  industry groups below the 25th percentile by 63-day return + breadth are rejected).
- Costs modeled: 0.15% breakout slippage + 0.035% commission.
- Backtested, not live, results.

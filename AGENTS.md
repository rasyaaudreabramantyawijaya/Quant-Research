# Quant Lab Rules

This repository is for applied computational finance, quant research, quant development, Admin Lab PKT / Pemrograman Komputasi Terapan learning, Predictive Modelling final-project work, backtesting, ML/DL/RL strategy research, and execution-system design.

Use the local Codex skill `quant-research-lab` for quant finance, quant development, alpha research, mathematical learning, ML/DL/RL strategy design, paper-to-experiment planning, backtest validation, and execution-system research.

For Admin Lab PKT or Predictive Modelling final-project tasks, Codex must use `quant-research-lab` and load the relevant references:
- `pkt-ta-track.md` for PKT math/CS learning priorities.
- `arya-wijaya-research-map.md` for Pak Arya Yudhi Wijaya stock-prediction paper anchors.
- `market-reading-indicators.md` for technical indicators and discretionary market-reading features.

When making claims about Pak Arya's papers, cite the source page or DOI. Treat Google Scholar as discovery, not the final citation source.

Preferred TA direction:
- Reproduce a serious stock-prediction paper first.
- Convert market-reading ideas into explicit, timestamp-safe features.
- Compare simple baselines before deep learning.
- Use ablation, walk-forward validation, and leakage checks before trusting results.

Codex must ask for human approval before:
- Using real broker credentials or API keys
- Downloading large paid datasets
- Running long backtests or GPU-heavy training jobs
- Changing execution or risk logic
- Promoting a strategy from research to paper trading
- Promoting a strategy from paper trading to live trading
- Deleting datasets, model checkpoints, logs, or backtest results

Research workflow:
1. Define hypothesis
2. Validate data source and leakage risk
3. Build baseline strategy/model
4. Backtest with transaction costs and slippage
5. Walk-forward / out-of-sample validation
6. Stress test by regime
7. Human review checkpoint
8. Paper trading only after approval
9. Live execution only after explicit approval

Never present backtest results as reliable unless leakage, survivorship bias, lookahead bias, costs, liquidity, and multiple-testing risk are addressed.

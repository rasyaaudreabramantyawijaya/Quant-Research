# Quant Lab Rules

This repository is for applied computational finance, quant research, quant development, backtesting, ML/DL/RL strategy research, and execution-system design.

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

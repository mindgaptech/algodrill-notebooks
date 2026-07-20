# AlgoDrill Notebooks

Runnable Jupyter companions to the code walkthroughs on [algodrill.app](https://algodrill.app/code).

Every notebook mirrors a walkthrough page and its recorded, version-pinned results — same code,
same fixed tickers and date ranges, so outputs are reproducible. Open any notebook directly in
Google Colab via the badge at the top of the notebook (no local setup), or run locally:

```bash
uv venv .venv && uv pip install -p .venv vectorbt yfinance pandas alpaca-py jupyter
.venv/bin/jupyter notebook
```

| Notebook | Companion page |
|---|---|
| [first_trading_bot.ipynb](notebooks/first_trading_bot.ipynb) | https://algodrill.app/code/first-trading-bot |
| [fetch_market_data.ipynb](notebooks/fetch_market_data.ipynb) | https://algodrill.app/code/fetch-market-data-python |
| [sma_crossover_backtest.ipynb](notebooks/sma_crossover_backtest.ipynb) | https://algodrill.app/code/sma-crossover-backtest |
| [position_sizing.ipynb](notebooks/position_sizing.ipynb) | https://algodrill.app/code/position-sizing-python |
| [walk_forward_split.ipynb](notebooks/walk_forward_split.ipynb) | https://algodrill.app/code/walk-forward-split-python |
| [reading_backtest_stats.ipynb](notebooks/reading_backtest_stats.ipynb) | https://algodrill.app/code/reading-backtest-stats |
| [alpaca_paper_first_order.ipynb](notebooks/alpaca_paper_first_order.ipynb) | https://algodrill.app/code/alpaca-paper-first-order |

The Alpaca notebook is the one exception to "runnable": its code cell ships unexecuted.
AlgoDrill never holds broker credentials, so there is no account for it to run against at
publish time — add your own Alpaca paper API keys as environment variables (or Colab secrets)
and run the cell yourself.

Nothing here is investment advice. Backtests are historical simulations with known limitations —
see [algodrill.app/backtesting-pitfalls](https://algodrill.app/backtesting-pitfalls).

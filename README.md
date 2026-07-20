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
| (remaining 6 walkthroughs to be converted) | https://algodrill.app/code |

Nothing here is investment advice. Backtests are historical simulations with known limitations —
see [algodrill.app/backtesting-pitfalls](https://algodrill.app/backtesting-pitfalls).

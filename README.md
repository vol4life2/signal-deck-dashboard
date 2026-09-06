# Signal Deck

Auto-updated, read-only view of the BTC/USD and ETH/USD trading signals from the [tradingBot](https://github.com/vol4life2/tradingBot) project.

This repo is intentionally small and public: it holds only the static `index.html` page and the generated `signals.json` snapshot. It never contains the trading strategy source, API credentials, or trade history - those stay in the private `tradingBot` repo.

`signals.json` is committed here every ~15 minutes by `tradingBot`'s `check-signals.yml` workflow (a plain, deterministic, read-only script - it never places an order). The page itself never talks to Alpaca or any trading API directly; it only reads this JSON file.

Published via GitHub Pages at the repo's Pages URL.

# CRYPTOSCAN — Scalper Gate

A zero-dependency browser scanner for Binance Spot USDT pairs.

## What it checks
- 1H trend using EMA20/EMA50
- 15M liquidity sweep and structure confirmation
- Volume expansion
- RSI momentum
- 5M/15M entry confirmation
- ATR volatility filter
- BTC 1H regime alignment
- Entry, stop, target and minimum R:R
- Configurable fee + slippage assumptions

The app intentionally keeps the **major-news gate manual** because Binance public market-data endpoints do not provide a dependable all-news/event-risk feed.

## Data
Uses Binance public REST market-data endpoints from the browser. No Binance API key is required for this scanner.

## Important
This is a screening/analysis tool, not an execution system or guarantee of profitable trades.
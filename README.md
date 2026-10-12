# Margin Muse

**Margin Muse** is a lightweight futures P&L calculator for estimating potential profit, loss, leverage impact, risk/reward, and scale-out selling scenarios.

It is designed for quick trade planning without connecting to a trading account or placing orders.

## Features

- Live BTC, ETH, and SOL price lookup
- Long and short position calculations
- Entry price, margin, leverage, and position size inputs
- Side-by-side Scenario A and Scenario B comparison
- Risk/reward calculation
- Three-batch scale-out selling planner
- Automatic price updates when the step size changes
- Responsive layout for desktop and mobile screens
- No account login, private API key, or order execution

## Getting Started

No build step or package installation is required.

1. Clone or download this repository.
2. Open `margin-muse.html` in a browser.
3. Enter your trade parameters and review the calculated results.

For local development, you can also serve the folder with any static web server:

```bash
python3 -m http.server 8000
```

Then open [http://localhost:8000/margin-muse.html](http://localhost:8000/margin-muse.html).

## Market Data

The calculator requests public ticker prices from Binance:

- Binance Futures API
- Binance Spot API as a fallback

Only public market prices are requested. The application does not access account balances, positions, orders, or private user data.

## Files

| File | Description |
| --- | --- |
| `margin-muse.html` | English version of the calculator with the background SVG embedded directly in the page |
| `index.html` | Original Chinese version |
| `vecteezy_wood-texture-abstract-background-vector-illustration_23651611.svg` | Original background asset |

## Disclaimer

This tool is for calculation and educational purposes only. It does not provide financial advice, guarantee results, or execute trades. Always verify prices, fees, funding rates, and liquidation conditions before making a trading decision.

## License

No license has been specified yet. Add a license file before redistributing the project publicly.


# Variational Alpha Terminal

**Variational Alpha Terminal** is a high-fidelity, real-time trading dashboard designed to extract market alpha. By analyzing live ticker statistics from the Variational API, it identifies market inefficiencies through a proprietary Alpha Scoring system that combines Open Interest (OI) and Bid-Ask Spreads.

## Key Features

- **Alpha Scoring Engine**: Automatically calculates asset efficiency. High scores indicate tickers with low liquidity (wide spreads) relative to their open interest—prime targets for market-making or contrarian strategies.

- **Smart Liquidity Filtering**: Real-time spread range controls to filter.

- **Visual Intensity Bars**: Instant visual recognition of market heat via dynamic progress bars and radial glow effects.

- **Live Protocol Sync**: Automated data fetching every 30 seconds with a visual "Flash Update" notification upon successful sync.

## Tech Stack

- **Engine**: React 18 (Lightweight CDN deployment)

- **Styling**: Tailwind CSS with custom Utility-First animations

- **Connectivity**: Native Variational Production API Integration.

## Quick Start
1. **Clone the repository**:
   ```bash
   git clone [https://github.com/ATK-zk/variational-alpha-terminal.git](https://github.com/ATK-zk/variational-alpha-terminal.git)  
2. **Launch**:
   Simply open index.html in any modern web browser.
3. **Deployment**:
   This project is optimized for GitHub Pages or Vercel. Just upload the index.html and it's ready to go.

## How to Use

- **Set Volume**: Use the Min/Max spread inputs to define your trading universe.

- **Identify Efficiency**: Look for tickers with a high Alpha Score. These are currently experiencing high "Trading Intensity" relative to their spread.

## License
This project is licensed under the **MIT License**.

Copyright (c) 2024-2026 [ATK-zk]

Disclaimer: This terminal is a data visualization tool. The information provided does not constitute financial advice. Trading cryptocurrency involves significant risk. The Alpha Score is a mathematical derivative and not a guaranteed indicator of price action.

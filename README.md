# 🛡️ Variational Alpha Terminal

**Variational Alpha Terminal** is a real-time dashboard designed to extract market alpha by analyzing ticker statistics directly from the Variational API. This terminal specializes in identifying market extremes and sentiment imbalances in the crypto derivatives market.



## 🚀 Key Features
- **Inverse Sentiment Strategy**: Purpose-built for contrarian traders.
  - 🔴 **SHORT (Bullish Data)**: Highlights assets with high Long/Short ratios (overcrowded longs).
  - 🟢 **LONG (Bearish Data)**: Highlights assets with high Short/Long ratios (overcrowded shorts).
- **Smart Volume Filtering**: Custom range controls to filter between high-cap stability and low-cap volatility.
- **Activity Metrics**: Real-time calculation of Volume/Open Interest (OI) ratio to detect unusual trading intensity.
- **Live Sync**: Automated data fetching every 45 seconds to ensure you stay ahead of the curve.

## 🛠️ Tech Stack
- **Frontend**: React 18 (via CDN for lightweight deployment)
- **Styling**: Tailwind CSS with Glassmorphism UI effects
- **Typography**: JetBrains Mono (Data) & Plus Jakarta Sans (Interface)
- **Data Connectivity**: Variational Production API

## 📂 Quick Start
1. **Clone the repository**:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/variational-alpha-terminal.git](https://github.com/YOUR_USERNAME/variational-alpha-terminal.git)  
2. **Launch**:
   Simply open index.html in any modern web browser.
3. **Deployment**:
   This project is optimized for GitHub Pages or Vercel. Just upload the index.html and it's ready to go.

## ⚙️ How to Use
- **Set Volume Range**: Define the liquidity profile you want to monitor (e.g., $100k to $10M).
- **Monitor Dominance**: Watch the "Dominance Power" bar. When one side exceeds 70-80%, the probability of a reversal typically increases.
- **Track Activity**: A higher Activity score relative to peers indicates a ticker is currently the "hot money" focus.
- **Disclaimer**: This terminal is a data visualization tool. The information provided does not constitute financial advice. Trading cryptocurrency involves significant risk.

## ⚖️ License
This project is licensed under the **MIT License**.

Copyright (c) 2024 [Your Name/Github Username]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

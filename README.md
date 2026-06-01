[![GitHub stars](https://img.shields.io/github/stars/YOUR_USERNAME/trading-bot-dashboard)](https://github.com/YOUR_USERNAME/trading-bot-dashboard/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/YOUR_USERNAME/trading-bot-dashboard)](https://github.com/YOUR_USERNAME/trading-bot-dashboard/network)
[![GitHub issues](https://img.shields.io/github/issues/YOUR_USERNAME/trading-bot-dashboard)](https://github.com/YOUR_USERNAME/trading-bot-dashboard/issues)
# Athena Trading Core - Multi-Timeframe Signal Engine

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Chart.js](https://img.shields.io/badge/Chart.js-4.4.0-FF6384?logo=chartdotjs)](https://www.chartjs.org/)

A real-time trading dashboard for crypto, commodities, and currency with multi-timeframe signal analysis and geopolitical risk overlay.

## 🚀 Features

- **Real-time price simulation** for Gold, Silver, WTI Crude, Bitcoin, Ethereum, and EUR/USD
- **Multi-timeframe signals**: 1m (scalp), 5m (intraday), 15m (swing), 1h (trend)
- **Geopolitical risk index** with automatic circuit breaker logic
- **Live price charts** with volatility tracking
- **Execution log** with real-time trading decisions
- **Risk-aware position sizing** that adapts to market tension

## 🎯 Asset Coverage

| Asset | Type | Icon |
|-------|------|------|
| Gold (XAU/USD) | Commodity | 🪙 |
| Silver (XAG/USD) | Commodity | 💎 |
| WTI Crude Oil | Commodity | 🛢️ |
| Bitcoin (BTC/USD) | Crypto | ₿ |
| Ethereum (ETH/USD) | Crypto | Ξ |
| EUR/USD | Forex | 💵 |

## 🛠️ Technologies Used

- HTML5 / CSS3 (Glassmorphism design)
- JavaScript ES6+
- Chart.js for real-time visualization
- Font Awesome 6 icons
- Google Fonts (Inter)

## 🚦 Signal Interpretation

| Signal | Meaning |
|--------|---------|
| 🟢 LONG | Bullish momentum - consider buying |
| 🔴 SHORT | Bearish momentum - consider selling |
| 🟡 NEUTRAL | No clear direction - wait |

The **confluence strength** (0-4) indicates how many timeframes agree on the signal direction.

## ⚠️ Risk Management

- **Geopolitical Risk Index** (0-100): Real-time tension simulation
- **Circuit Breaker**: Activates when risk > 72, reducing position sizes
- **Volatility Tracking**: Monitors realized volatility in real-time

## 🖥️ How to Use

1. Clone this repository:
```bash
git clone https://github.com/YOUR_USERNAME/trading-bot-dashboard.git

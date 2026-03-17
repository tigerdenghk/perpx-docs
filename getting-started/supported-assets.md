# Supported Assets

PerpX DEX supports **full-category asset trading** through decentralized oracle integration. All assets are traded as perpetual contracts with USDC as the settlement currency.

## Asset Categories

| Category | Examples | Oracle Source |
| --- | --- | --- |
| **Cryptocurrencies** | BTC, ETH, SOL, ARB, OP, ... | Pyth + Chainlink |
| **US Equities** | AAPL, TSLA, NVDA, AMZN, ... | Oracle aggregation |
| **Precious Metals** | XAU (Gold), XAG (Silver) | Oracle aggregation |
| **Commodities** | Crude Oil (WTI), Natural Gas | Oracle aggregation |
| **Forex** | EUR/USD, GBP/USD, USD/JPY | Oracle aggregation |
| **Indices** | S&P 500, NASDAQ 100 | Oracle aggregation |

## Trading Parameters

| Parameter | Value |
| --- | --- |
| Settlement Currency | USDC |
| Maximum Leverage | Up to 100x (varies by asset) |
| Trading Hours | 24/7 (crypto), market hours (traditional assets) |
| Minimum Position | Varies by asset |
| Fee Structure | Dynamic (AI-optimized) |

## Price Feed

PerpX uses a **multi-source oracle aggregation system** combining Pyth Network and Chainlink, with TWAP anti-manipulation protection and AI anomaly detection to ensure accurate, tamper-resistant pricing.

---

> **Note:** Asset availability is continuously expanding. New assets can be proposed and listed through DAO governance. Check the app for the latest supported trading pairs.

# Introduction

Stock SDK is a stock market TypeScript SDK for frontend and Node.js with zero dependencies, a Lightweight distribution, and one unified API surface for multiple market data workflows.

## Project Origin and Open Source

Stock SDK is an open-source TypeScript project maintained by [chengzuopeng](https://github.com/chengzuopeng). It started from a practical need: making stock market data easy to use directly from frontend and Node.js projects. The project focuses on browser + Node.js compatibility, zero runtime dependencies, and a unified typed API.

This project is open sourced under the [ISC License](https://github.com/chengzuopeng/stock-sdk/blob/master/LICENSE). You may use, modify, and distribute the code as long as you comply with the license terms.

## Features

- Works in both browser and Node.js 18+
- Ships ESM and CommonJS builds
- Covers A-share, HK, US, mutual funds, futures, and options
- Provides real-time quotes, K-line, timeline, sector data, dividend details, and trading calendar
- Includes MA, MACD, BOLL, KDJ, RSI, WR, BIAS, CCI, ATR, OBV, ROC, DMI, SAR, and KC
- Supports retry, rateLimit, circuitBreaker, and `providerPolicies`
- Full TypeScript types with frontend-friendly APIs

## Data Sources

- Tencent: real-time quotes, code lists, search, trading calendar, fund flow, and intraday timeline
- Eastmoney: A-share / HK / US historical K-line, minute K-line, sectors, dividend details, futures, and part of the options data
- Sina: part of the ETF option minute data and supplemental option workflows

Stock SDK is a wrapper for requesting, parsing, and typing market data. It does not produce original market data and is not affiliated with any market data provider or trading institution. Please follow the terms of service, robots policy, and rate limits of the corresponding data source websites.

Market data may be delayed, missing, corrected later, or affected by upstream API changes. This project does not provide investment advice and does not guarantee that the data is suitable for live trading, quantitative trading, or any financial decision.

## Good Fits

- Frontend quote dashboards and charting
- Node.js scheduled jobs and trading-day automation
- Indicator analysis and quant prototypes
- Futures and options monitoring
- Dividend event and calendar-based reminders

## Next Steps

- [Installation](/en/guide/installation)
- [Quick Start](/en/guide/getting-started)
- [Request Governance](/en/guide/request-governance)
- [API Overview](/en/api/)

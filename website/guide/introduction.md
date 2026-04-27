# 介绍

Stock SDK 是一个为前端和 Node.js 设计的股票行情 TypeScript SDK，提供零依赖、轻量发布包和统一的多市场接口。

## 项目来源与开源说明

Stock SDK 是由 [chengzuopeng](https://github.com/chengzuopeng) 维护的开源 TypeScript 项目，最初源于“前端和 Node.js 项目也能直接获取股票行情数据”的需求。项目以浏览器和 Node.js 双端可用、零运行时依赖、统一类型定义为主要目标。

本项目采用 [ISC License](https://github.com/chengzuopeng/stock-sdk/blob/master/LICENSE) 开源。你可以在遵守许可证的前提下自由使用、修改和分发本项目代码。

## 特性

- 支持浏览器和 Node.js 18+ 双端运行
- 同时提供 ESM 与 CommonJS
- 覆盖 A 股、港股、美股、公募基金、期货和期权
- 提供实时行情、K 线、分时走势、板块数据、分红派送和交易日历
- 内置 MA、MACD、BOLL、KDJ、RSI、WR、BIAS、CCI、ATR、OBV、ROC、DMI、SAR、KC
- 支持 retry、rateLimit、circuitBreaker 和 `providerPolicies`
- 完整 TypeScript 类型和面向前端的调用方式

## 数据来源

- 腾讯财经：实时行情、代码列表、搜索、交易日历、资金流向、分时走势
- 东方财富：A 股 / 港股 / 美股历史 K 线、分钟 K 线、板块、分红派送、期货、部分期权
- 新浪：部分 ETF 期权分钟数据和补充期权链路

Stock SDK 只是行情数据的调用、解析和类型封装工具，不生产原始行情数据，也不代表任何数据源或交易机构。使用时请遵守对应数据来源网站的服务条款、robots 策略和访问频率限制。

行情数据可能存在延迟、缺失、修正或接口变更。本项目不提供投资建议，也不保证数据适用于实盘交易、量化交易或任何金融决策。

## 适合的工作流

- 前端行情看板与图表
- Node.js 定时抓取和交易日调度
- 指标分析与量化原型
- 期货 / 期权策略观察
- 分红派送与事件驱动提醒

## 下一步

- [安装](/guide/installation)
- [快速开始](/guide/getting-started)
- [请求治理](/guide/request-governance)
- [API 总览](/api/)

<div align="center">

```
██╗    ██╗██╗ ██████╗██╗  ██╗
██║    ██║██║██╔════╝██║ ██╔╝
██║ █╗ ██║██║██║     █████╔╝ 
██║███╗██║██║██║     ██╔═██╗ 
╚███╔███╔╝██║╚██████╗██║  ██╗
 ╚══╝╚══╝ ╚═╝ ╚═════╝╚═╝  ╚═╝
```

**Headless Web Components for trading interfaces.**

[![MIT License](https://img.shields.io/badge/license-MIT-00ffa3?style=flat-square)](https://github.com/wick-trading/Wick/blob/main/LICENSE)
[![Components](https://img.shields.io/badge/components-31-00ffa3?style=flat-square)](https://wick-trading.github.io/Wick/#components)
[![Frameworks](https://img.shields.io/badge/frameworks-4-00ffa3?style=flat-square)](https://wick-trading.github.io/Wick/#code)
[![Exchanges](https://img.shields.io/badge/exchanges-10-00ffa3?style=flat-square)](https://wick-trading.github.io/Wick/#components)

</div>

---

**Wick** is an open-source library of 31 unstyled, framework-agnostic Web Components built for trading interfaces. Think shadcn/ui — but for traders.

```bash
npm install @wick/order-book @wick/price-ticker @wick/trade-feed
```

### Components

| Category | Components |
|---|---|
| **Market Data** | Order Book, Price Ticker, Trade Feed, Depth Chart, Funding Rate, Open Interest, Liquidation Feed, DOM Ladder |
| **Charts** | Candlestick, Mini Chart, Volume Profile, Drawing Tools, Correlation Matrix, Indicators |
| **Heatmaps** | Order Book Heatmap, Market Heatmap |
| **Execution** | Order Ticket, Order Manager, Position Sizer |
| **Portfolio** | Positions, P&L, Trade History, Risk Panel |
| **Market Overview** | Watchlist, Screener, Symbol Search, Market Clock |
| **Alerts & Intel** | Alerts, News Feed, Economic Calendar, Connection Status |

### Framework Support

Works natively in **React**, **Vue**, **Svelte**, **Angular**, and **Vanilla JS**.

```tsx
// React
import { OrderBook, PriceTicker } from '@wick/react';

// Vue / Svelte / Angular / Vanilla
import '@wick/order-book';
```

### Theming

Three built-in themes — drop in one line:

```ts
import '@wick/theme/dark';    // Binance / Bybit style
import '@wick/theme/glass';   // Glassmorphism
import '@wick/theme/minimal'; // Linear / Stripe aesthetic
```

Override any token at the `:root` or component level via CSS custom properties.

---

<div align="center">

[**Site**](https://wick-trading.github.io/Wick) · [**Docs**](https://wick-trading.github.io/Wick/docs) · [**npm**](https://www.npmjs.com/org/wick) · [**MIT License**](https://github.com/wick-trading/Wick/blob/main/LICENSE)

</div>

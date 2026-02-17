# 📊 Mini Bloomberg Terminal - 👩🏻‍💻 `BloomZ`

A web-based financial terminal interface inspired by Bloomberg terminals, providing real-time market data, financial analysis, and interactive charts.

![Mini Bloomberg Terminal](https://img.shields.io/badge/Version-4.0-orange)
![License](https://img.shields.io/badge/License-MIT-green)

## Features

### Market Data & Analysis
- **Real-time Market Dashboard** - Live indices, crypto, and sector performance
- **World Equity Indices (WEI)** - Global market overview across Americas, Europe, and Asia-Pacific
- **Global Performance (GP)** - Multi-asset tracking including crypto, commodities, FX, and bonds
- **Stock Matrix (STX)** - Comprehensive screener with 50+ securities
- **Sector Performance (SECF)** - Real-time sector rotation analysis

### Company Analysis
- **Company Description (DES)** - Detailed company profiles with:
  - Price performance metrics
  - Valuation multiples (P/E, P/S, EV/EBITDA)
  - Financial health indicators
  - Growth metrics
  - Analyst recommendations
  - Integrated TradingView charts (for select tickers like RKLB)
- **Financial Analysis (FA)** - Comprehensive FA view with:
  - Dynamic color-coded metric cards
  - 52-week range visualization
  - Profitability & returns analysis
  - Risk metrics (Beta, Audit Risk, etc.)
  - Cash flow analysis

### Specialized Views
- **ETF Themes (ETF)** - Innovation, Technology, Healthcare, Finance, Energy, and Space/Defense ETFs
- **Crypto Market (CRYP)** - Top 10 cryptocurrencies with market data
- **Bond Outlook (BOND)** - Rates, credit markets, and yield spreads
- **Economic Calendar (ECO)** - Upcoming economic events and indicators
- **Top News (TOP)** - Aggregated news from major tickers

### User Interface
- **Bloomberg-style Terminal Aesthetic** - Dark theme with orange accents
- **Rolling Ticker Tape** - Real-time price updates
- **Command-line Interface** - Terminal-style commands with autocomplete
- **Quick Access Buttons** - One-click command execution
- **Responsive Design** - Works on desktop and mobile devices

## Commands

| Command | Description | Example |
|---------|-------------|---------|
| `WEI` | World Equity Indices | `WEI` |
| `GP` | Global Performance | `GP` |
| `STX` | Stock Matrix | `STX` |
| `CRYP` | Crypto Market View | `CRYP` |
| `BOND` | Rates & Bond Outlook | `BOND` |
| `TOP` | Top News | `TOP` |
| `ECO` | Economic Calendar | `ECO` |
| `SECF` | Sector Performance | `SECF` |
| `ETF` | Thematic ETFs | `ETF` |
| `DES [TICKER]` | Company Description | `DES AAPL` |
| `FA [TICKER]` | Financial Analysis | `FA MSFT` |
| `HELP` | Show Help | `HELP` |
| `CLEAR` / `CLS` | Clear Screen | `CLEAR` |

## Installation

1. **Clone or download** the HTML file
2. **Open** `index.html` in any modern web browser
3. **No build process required** - Pure HTML/CSS/JS

```bash
# Optional: Serve with a local server for development
python -m http.server 8000
# or
npx serve .
```

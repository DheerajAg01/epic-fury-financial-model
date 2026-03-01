# 💥 Operation Epic Fury — Geopolitical Financial Impact Model

> **An interactive, real-time financial analysis dashboard modeling the market impact of the US–Israel strikes on Iran (Operation Epic Fury, February 28, 2026)**

🔴 **Live Demo:** [dheerajag01.github.io/epic-fury-financial-model](https://dheerajag01.github.io/epic-fury-financial-model/)

---

## 📊 Overview

This is a fully interactive, browser-based financial model built to analyze the multi-dimensional economic and market impact of one of the most significant geopolitical events in recent history — the joint US–Israel strikes on Iran, the killing of Supreme Leader Khamenei, and the resulting global financial shockwaves.

No installation required. No Python environment. No server. Just open the HTML file in any browser.

---

## 🚀 Features

| Tab | What It Does |
|-----|-------------|
| 📊 **Overview** | Live KPI cards, sector heat map, asset allocation, historical oil shock comparisons |
| 🏭 **Sectors** | 12 sectors — Table, Radar, and Bar views with buy/sell signals |
| 💹 **Asset Classes** | Correlation matrix, oil trajectory, bond yields, safe haven flow analysis |
| 🏢 **Companies** | 17 named companies — Winners vs Losers with scenario-adjusted return estimates |
| 🌍 **Countries** | GDP & inflation impact for 12 countries with individual risk meter cards |
| ⚙️ **Financial Model** | 8 interactive sliders — recalculates S&P impact, gold target, CPI, GDP, portfolio P&L live |
| 🛡 **Strategies** | 6 sector-specific corporate playbooks with step-by-step action items |
| 📅 **Timeline** | Event tracker, decision triggers, historical recovery comparisons |

---

## 🎮 How to Use

### Option 1 — Live Website
Click the live demo link above. Runs instantly in your browser.

### Option 2 — Run Locally
```bash
git clone https://github.com/dheerajag01/epic-fury-financial-model.git
cd epic-fury-financial-model
# Just open index.html in your browser — no server needed
open index.html        # Mac
start index.html       # Windows
xdg-open index.html    # Linux
```

---

## 🔀 Scenario Switcher

The model supports **3 conflict scenarios** — switch between them at the top of the dashboard and every chart, table, and number recalculates instantly:

| Scenario | Probability | Brent Crude | S&P 500 Impact | Description |
|----------|------------|-------------|----------------|-------------|
| 🟢 **A — Quick Resolution** | 35% | $73–$80 | –3% to –8% | Conflict contained within weeks |
| 🟡 **B — Protracted War** | 45% | $82–$95 | –10% to –20% | Extended conflict, no Hormuz closure |
| 🔴 **C — Hormuz Closure** | 20% | $100–$130+ | –25% to –40% | Strait blocked — global recession risk |

---

## ⚙️ Interactive Financial Model

Use the **8 sliders** to build your own custom scenario:

- 🛢️ Oil Price (Brent $/bbl)
- ⏱️ Conflict Duration (months)
- 🚢 Hormuz Closure Probability (%)
- 💻 Iranian Cyberattack Probability (%)
- 📉 Risk-Off Intensity (1–10)
- 🏭 OPEC+ Response Level (0–10)
- 💼 Portfolio Oil Exposure (%)
- 🛡️ Portfolio Defense Exposure (%)

All outputs — S&P drawdown, gold target, CPI impact, GDP delta, and **full portfolio P&L in dollars** — update in real time.

---

## 📈 Key Data Points Modeled

- **12 Economic Sectors** with short & medium-term return estimates
- **17 Individual Companies** (Winners: LMT, RTX, XOM, CRWD | Losers: DAL, ZIM, TSLA, MAR)
- **12 Countries** — GDP impact, inflation delta, conflict risk exposure
- **Asset Classes** — Oil, Gold, USD, Treasuries, Bitcoin, Defense stocks
- **Historical Comparables** — 1973 Oil Embargo, 1990 Gulf War, 2003 Iraq, 2022 Ukraine, Jun 2025 Iran Strikes
- **Monte Carlo** oil price distribution (500 simulations)
- **Sensitivity Analysis** — which variables move markets most

---

## 🛠️ Tech Stack

```
HTML5 / CSS3 / Vanilla JavaScript
Chart.js 4.4.1          — All charts and visualizations
D3.js 7.8.5             — Correlation matrix
Google Fonts            — IBM Plex Mono + IBM Plex Sans
Zero dependencies       — No npm, no build step, no framework
```

---

## 📁 File Structure

```
epic-fury-financial-model/
│
├── index.html       ← Entire application (single file)
└── README.md        ← This file
```

---

## ⚠️ Disclaimer

This model is for **educational and analytical purposes only**. All figures, estimates, and projections are based on historical geopolitical conflict patterns, analyst reports, and scenario modeling — they do not constitute financial or investment advice. Consult a qualified financial advisor before making investment decisions.

---

## 🤝 Contributing

Pull requests welcome. If you want to:
- Add new scenarios
- Expand the country coverage
- Add more companies
- Connect to live market data APIs

Fork the repo, make your changes, and submit a PR.

---

## 📜 License

MIT License — free to use, modify, and distribute.

---

<div align="center">
  <strong>Built with Claude AI · March 2026</strong><br>
  <em>For educational and analytical purposes only</em>
</div>

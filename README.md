# ZENKAI Bias Battlecard

Pre-NY Open trading dashboard built on Smart Money Concepts (SMC) analysis.

## What's in here

| File | Description |
|------|-------------|
| `zenkai-bias-battlecard.html` | Main battlecard — open this in your browser before the NY session |
| `ny-open-dashboard.html` | Original NY Open dashboard (v1) |
| `skill/SKILL.md` | The Claude AI skill that generates a fresh battlecard each session |

## How to use

1. Run `/nyopen` in your Claude session to generate a new battlecard with live data
2. Open `zenkai-bias-battlecard.html` in your browser
3. Each pair section has a live TradingView chart + SMC analysis + trade setup

## What the battlecard includes

- Live TradingView H1 charts for all 6 pairs: XAUUSD, EURUSD, GBPJPY, NAS100, NZDJPY, AUDCAD
- Session H/L analysis (Asian + London) with NY sweep detection for XAUUSD
- Supply & demand zones per pair
- SVG trade ladder showing SL / Entry / TP1 / TP2
- Retail sentiment bars (contrarian SMC interpretation)
- Star ratings (1–5) and direction bias per pair
- Economic calendar news strip (high/medium impact events)
- Political & macro risk banner with per-pair context

## Pairs covered

| Pair | Asset Class |
|------|-------------|
| XAUUSD | Gold |
| EURUSD | Forex |
| GBPJPY | Forex |
| NAS100 | Index |
| NZDJPY | Forex |
| AUDCAD | Forex |

---

*Analysis is for educational purposes only. Not financial advice. Always manage your own risk.*

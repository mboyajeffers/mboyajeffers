# Mboya Jeffers

**Automated market intelligence for hedge funds, crypto funds, energy operators, and institutional buyers.**

I build and operate a live data platform that generates branded, verifiable analytics reports across 9 industry verticals — weekly, monthly, and quarterly — with every number traceable to a public API source pulled at generation time.

[![Reports](https://img.shields.io/badge/Sample_Reports-89_PDFs-6366f1?style=flat-square)](https://github.com/mboyajeffers/financial-market-analysis)
[![Portfolio](https://img.shields.io/badge/Portfolio-20M+_Rows-3b82f6?style=flat-square)](https://github.com/mboyajeffers/Data-Engineering-Portfolio)
[![CI](https://github.com/mboyajeffers/financial-data-engineering/actions/workflows/ci.yml/badge.svg)](https://github.com/mboyajeffers/financial-data-engineering/actions)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/mboya-jeffers-6377ba325)

---

## What the platform delivers

Institutional-quality analytics reports in three formats — weekly snapshots, monthly deep-dives, and quarterly outlooks — built from live API data and rendered as branded PDFs with auditable data lineage.

**9 verticals covered:**

| Vertical | Data Sources | Key Metrics |
|----------|-------------|-------------|
| Finance | Yahoo Finance, FRED | Sector returns, macro environment, yield curve, volatility |
| Crypto | CoinGecko | Price, market cap, 24h + 30d performance, concentration |
| Oil & Gas | EIA API, Yahoo Finance | Crude/NG production, WTI/Henry Hub spot, supply trends |
| Media & Streaming | Yahoo Finance, FRED | Equity performance, consumer sentiment, sector momentum |
| Gaming | Yahoo Finance | Market leaders, sector returns, platform rotation |
| Sports & Betting | ESPN API, Yahoo Finance | League standings, operator equities, market structure |
| Solar | Open-Meteo, NREL | Capacity factor, peak sun hours, irradiance trends |
| Weather | Open-Meteo | Temperature, precipitation, climate anomalies |
| Compliance | FRED | Credit spreads, yield curve, macro risk indicators |

Every metric traces back to a verifiable public source. No synthetic data. No proprietary claims.

---

## White-glove demos

The sharpest thing the platform does: **I build a live-data demo report tailored to a specific firm — before they commit to anything.**

Three examples — all generated with real data pulled at time of delivery:

- **$9.9B AUM hedge fund** — live equity + macro report built around their portfolio style
- **$1B+ crypto fund** — CoinGecko live market intelligence scoped to their asset class
- **500-well energy operator** — EIA production data + futures prices framed around their exposure

If you know a firm that would find their own data in a report before they've agreed to pay for it — that's the pitch. [See the demo package →](https://github.com/mboyajeffers/financial-market-analysis#white-glove-demonstrations)

---

## Sample reports + pricing

89 branded PDFs across finance, crypto, energy, and sports. Weekly, monthly, and quarterly cadence. Service tiers from $150 to $8,000/month.

[**View samples and service tiers →**](https://github.com/mboyajeffers/financial-market-analysis)

---

## The platform

Production infrastructure running on GCP — not a script, not a prototype.

```
Platform Architecture:
├── 9 industry data pipelines (live API pulls at report generation time)
│   ├── FRED — 50+ macro series (GDP, CPI, yield curve, labor, rates)
│   ├── Yahoo Finance — equities, ETFs, commodities, futures
│   ├── CoinGecko — crypto markets, market cap, volatility
│   ├── EIA API v2 — crude production, natural gas, spot prices
│   ├── Open-Meteo — weather and solar irradiance (hourly + daily)
│   ├── NREL PVWatts — solar generation modeling
│   ├── ESPN API — league standings, team performance
│   ├── SEC EDGAR — XBRL financial facts, filing patterns
│   └── Custom extractors — pagination, rate limiting, retry logic
├── Kimball star schema modeling (30+ dimension and fact tables)
├── Data quality framework — 6 validation rule types (completeness, range, uniqueness, consistency)
├── Automated PDF report generation — industry color schemes, auditable source tables
├── ML trading signal pipeline — direction classification + GARCH(1,1) VaR (paper trading live)
├── GCP infrastructure — Terraform, PostgreSQL, Nginx, systemd, CI/CD
└── Native macOS desktop app (Electron) — dashboard UI wrapper
```

**ML & Trading Systems**

| System | Models | Accuracy | Status |
|--------|--------|----------|--------|
| Day trading signals | Momentum classifier, scalp variant, intraday VaR, volume anomaly | 78.3% (momentum) | Live — 25 tickers, daily |
| Swing trading | Direction classifier v2, GARCH(1,1) VaR | 69.1% in-sample / walk-forward validated | Paper trading active |

Both systems run end-to-end: feature engineering from daily OHLCV bars → model inference → risk sizing → broker API.

---

## Numbers

| Metric | Value |
|--------|-------|
| Data processed | **20M+ rows** (public portfolio) |
| Verticals | **9 industry coverage areas** |
| Live data sources | **9 public APIs** |
| Intelligence reports | **89 branded PDFs + 3 white-glove demos** |
| ML models deployed | **6** (day trading + swing — paper trading live) |
| Automated tests | **500+** |

---

## Repositories

| Repo | What's in it |
|------|-------------|
| [**financial-market-analysis**](https://github.com/mboyajeffers/financial-market-analysis) | 89 sample reports (PDFs), 3 white-glove demos, report generators, service tiers + pricing |
| [**Data-Engineering-Portfolio**](https://github.com/mboyajeffers/Data-Engineering-Portfolio) | 8 projects across 8 industries, 20M+ rows, ML trading pipeline, platform infrastructure docs |
| [**financial-data-engineering**](https://github.com/mboyajeffers/financial-data-engineering) | 8 API extractors, Kimball star schema, ML pipeline (backtester + signal generator), 200+ tests |

---

## For sales partners and BD

If you work with data-hungry firms in finance, energy, or crypto and you're looking for something differentiated to offer your network — let's talk.

**What you'd be selling:** Automated intelligence reports from a production platform that's already built and running. Weekly, monthly, and quarterly cadence. Branded PDFs with live data and verifiable sourcing. White-glove demos available for qualified prospects before any commitment.

**Who buys it:** Hedge funds and asset managers, crypto funds, energy operators, compliance teams, sports analytics operations, gaming publishers.

**Arrangement:** Open to rev-share, referral fees, or introductions. No volume commitment required to start.

**Contact:** MboyaJeffers9@gmail.com

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-4C72B0?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/CI/CD-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![WeasyPrint](https://img.shields.io/badge/WeasyPrint-FF6B35?style=flat-square)

---

## Contact

**Mboya Jeffers** — Data & ML Engineer

- **Email:** MboyaJeffers9@gmail.com
- **LinkedIn:** [linkedin.com/in/mboya-jeffers-6377ba325](https://linkedin.com/in/mboya-jeffers-6377ba325)
- **GitHub:** github.com/mboyajeffers
- **Location:** Remote (US-based)

*Analytics consulting and embedded data partnerships. All sample code is publicly runnable.*

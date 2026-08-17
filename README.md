# Mboya Jeffers

**AI Engineering Consultant — production data and AI pipelines across 10 industries.**

I build production data and AI pipelines: a scoped, working pipeline in 5 business days, or embedded engineering capacity for ongoing work — finance, energy, healthcare, gaming, crypto, and more, all running on the same tested extraction and platform layer. Deepest specialization: quant funds, prop desks, and crypto funds that need a second engineer to own their data or signal pipeline. Every pattern below — Terraform-managed infrastructure, CI/CD, RBAC, SLO monitoring, incident response — runs in my own production system first, before it's offered to a client.

[![CI](https://github.com/mboyajeffers/financial-data-engineering/actions/workflows/ci.yml/badge.svg)](https://github.com/mboyajeffers/financial-data-engineering/actions)
[![Portfolio](https://img.shields.io/badge/Portfolio-4.3M+_Rows-3b82f6?style=flat-square)](https://github.com/mboyajeffers/Data-Engineering-Portfolio)
[![Platform](https://img.shields.io/badge/Platform-IaC_%7C_CI%2FCD_%7C_SLO_%7C_RBAC-2f6f62?style=flat-square)](https://github.com/mboyajeffers/Data-Engineering-Portfolio/tree/main/platform)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/mboya-jeffers-6377ba325)

---

## Work with me

Scoped data pipeline builds and embedded engineering capacity — one engineer, production discipline, not a chatbot wrapper or a generic "AI strategy" engagement. Full detail: [**ai-systems-consulting**](https://github.com/mboyajeffers/ai-systems-consulting).

| Service | Price |
|---------|-------|
| Custom Data Pipeline & Automation Build | $3,000–$6,000, scoped on a call · 5 business days |
| Embedded AI & Data Systems Partner | From $2,500/month, scoped in the discovery call |
| Custom Research & Outreach Agents | Scoped on a call — same pattern as [Jack](https://github.com/mboyajeffers/ai-systems-consulting), the agent I run for my own sales pipeline |

Strongest fit: quant/prop shops and crypto funds that need a second engineer to own their data or signal pipeline — the deepest proof below is built for exactly that.

**What one engineer, done right, actually covers:**

| Capability | Evidence |
|------------|----------|
| **Platform engineering** | Terraform IaC on GCP, systemd services, Nginx reverse proxy |
| **CI/CD** | 5-job pipeline — lint, test, security scan (bandit + pip-audit), SBOM, build |
| **Observability** | SLO monitoring with error-budget alerting across 3 tracked SLIs |
| **Security** | 4-role RBAC, immutable append-only audit trail, secrets management |
| **Data engineering** | 10 ETL pipelines, Kimball star schema modeling, 4.3M+ verified rows |
| **Operational discipline** | Automated backups, deploy/rollback scripts, runbooks, ADRs |

Full breakdown, with real code: [**Data-Engineering-Portfolio/platform**](https://github.com/mboyajeffers/Data-Engineering-Portfolio/tree/main/platform)

---

## What I've built

Institutional-quality analytics reports and ETL pipelines pulling live data from public APIs, rendered as branded PDFs with auditable data lineage.

**10 verticals covered — Finance, Crypto, Ecommerce, and Solar are the four this business is built around; the rest demonstrate the same extraction pattern reused, not duplicated, across a wide industry surface:**

| Vertical | Data Sources | Key Metrics |
|----------|-------------|-------------|
| Finance | Yahoo Finance, FRED | Sector returns, macro environment, yield curve, volatility |
| Crypto | CoinGecko, DefiLlama | Price, market cap, DeFi TVL, 24h + 30d performance, concentration |
| Ecommerce | Yahoo Finance, FRED | Sector equity performance, consumer sentiment, retail sales |
| Solar | Open-Meteo (real archive irradiance) | Peak sun hours, trailing-365-day resource assessment, PV economics |
| Oil & Gas | EIA API, Yahoo Finance | Crude/NG production, WTI/Henry Hub spot, supply trends |
| Media & Streaming | Yahoo Finance, FRED | Equity performance, consumer sentiment, sector momentum |
| Gaming | Yahoo Finance | Market leaders, sector returns, platform rotation |
| Sports & Betting | ESPN API, Yahoo Finance | League standings, operator equities, market structure |
| Weather | Open-Meteo | Temperature, precipitation, climate anomalies |
| Compliance | FRED | Credit spreads, yield curve, macro risk indicators |

Every metric traces back to a verifiable public source. No synthetic data. No proprietary claims.

**ML & Trading Systems**

| System | Models | Accuracy | Status |
|--------|--------|----------|--------|
| Swing trading | Direction classifier v2, GARCH(1,1) VaR | 69.1% in-sample / walk-forward validated | Paper trading active |

Both systems run end-to-end: feature engineering from daily OHLCV bars → model inference → risk sizing → broker API.

**Agents**

Jack — a research/outreach agent (find → research → score → draft, IP-safe by construction) that I built and run for my own sales pipeline, and the working prototype behind the Custom Research & Outreach Agents service above. Case study: [ai-systems-consulting](https://github.com/mboyajeffers/ai-systems-consulting).

---

## Also: analytics consulting

Alongside the engineering, I run **white-glove market intelligence** for hedge funds, crypto funds, energy operators, and institutional buyers — the sharpest thing this does: I build a live-data demo report tailored to a specific firm before they commit to anything.

96 branded PDFs across finance, crypto, energy, and sports. Weekly, monthly, and quarterly cadence. Service tiers from $150 to $8,000/month. [View samples and service tiers →](https://github.com/mboyajeffers/financial-market-analysis)

**For sales partners and BD:** if you work with data-hungry firms in finance, energy, or crypto and want something differentiated to offer your network — open to rev-share, referral fees, or introductions, no volume commitment required. Contact below.

---

## Numbers

| Metric | Value |
|--------|-------|
| Data processed | **4.3M+ rows** (public portfolio) |
| Verticals | **10 industry coverage areas** |
| Live data sources | **9 public APIs** |
| Intelligence reports | **96 branded PDFs + 3 white-glove demos** |
| ML models deployed | **6** (day trading + swing — paper trading live) |
| Automated tests | **195** (public repos, all passing — verified directly, not by trusting the README) |

---

## Repositories

| Repo | What's in it |
|------|-------------|
| [**ai-systems-consulting**](https://github.com/mboyajeffers/ai-systems-consulting) | Consulting service repo — scoped pipeline builds, embedded partner tier, research/outreach agents, Jack case study |
| [**Data-Engineering-Portfolio**](https://github.com/mboyajeffers/Data-Engineering-Portfolio) | 10 projects across 10 industries, 4.3M+ rows, production platform infrastructure (Terraform/CI/RBAC/SLO), ML trading pipeline |
| [**financial-data-engineering**](https://github.com/mboyajeffers/financial-data-engineering) | 9 API extractors, Kimball star schema, ML pipeline (backtester + signal generator), 127 tests, CI passing |
| [**financial-market-analysis**](https://github.com/mboyajeffers/financial-market-analysis) | 96 sample reports (PDFs), 3 white-glove demos, report generators, service tiers + pricing |
| [**mboyajeffers.github.io/market-pulse**](https://mboyajeffers.github.io/market-pulse/) | Live, scheduled dashboard — Finance, Crypto/DeFi, Ecommerce, Solar, regenerated by a GitHub Action on a cron |
| [**pipeline-reliability-patterns**](https://github.com/mboyajeffers/pipeline-reliability-patterns) | 4 real pipelines (Finance/Crypto/Ecommerce/Solar), 8 realistic production failure modes found, fixed, and test-pinned — each proven twice via `pytest`. Rendered at [reliability-patterns](https://mboyajeffers.github.io/reliability-patterns/) |

---

## Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![statsmodels](https://img.shields.io/badge/statsmodels-4C72B0?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/CI/CD-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white)
![WeasyPrint](https://img.shields.io/badge/WeasyPrint-FF6B35?style=flat-square)

---

## Contact

**Mboya Jeffers** — AI Engineering Consultant

- **Website:** [mboyajeffers.github.io](https://mboyajeffers.github.io)
- **Email:** MboyaJeffers9@gmail.com
- **LinkedIn:** [linkedin.com/in/mboya-jeffers](https://linkedin.com/in/mboya-jeffers-6377ba325)
- **GitHub:** github.com/mboyajeffers
- **Location:** Remote (US-based)

*Open to scoped consulting engagements and embedded partnerships. All sample code is publicly runnable.*

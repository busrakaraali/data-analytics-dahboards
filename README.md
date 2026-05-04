# Data Analytics Dashboards

A collection of business intelligence dashboards built with **Power BI** and **Tableau** using mock datasets. Each dashboard is designed to answer real business questions and communicate insights clearly to non-technical stakeholders.

---

## Dashboards

### 1. Payment Transaction Analytics — Power BI
> Analysing payment transaction patterns across countries, networks, and card types

### 2. Mobile App Performance — Tableau
> Executive summary of app install, revenue, and profitability metrics across networks and countries


---

## Dashboard Screenshots
### PowerBI

### Overview — Transaction Volume & Fee Distribution
![Transaction Overview](screenshots/dash1.png)

*Interactive filters: Country, Funding Source, Card Type, Network, Transaction Regionality, Month, Day*

Key visuals:
- **Map** — Number of transactions by country (NL, DE, GB, US)
- **Donut chart** — Total fee in EUR by card type (Standard leads at 36%)
- **Bar chart** — Total transaction value by regionality and network
- **Detail table** — Breakdown by network, funding source, card type, and country

---

### Interchange Analysis — Adyen vs Previous Issuer
![Interchange Analysis](screenshots/dash2.png)

Key visuals:
- **Line chart** — Daily Adyen vs Previous Issuer interchange revenue across April
- **Summary tables** — Average interchange advantage by card type, country, funding source, network, and regionality

**Key insight:** Adyen consistently outperforms previous issuer rates across all segments, with Fleet cards showing the highest advantage (109 EUR avg vs Standard at 32 EUR avg).


### Tableau


### Executive Summary
![Executive Summary](screenshots/Tableau_Dashboard.png)

---

Key Insights

- **Revenue peaks** in November-December, suggesting strong seasonal effect
- **Netherlands dominates** net revenue at 92,630 — far ahead of other markets
- **App 174** leads in both installs (47,416) and revenue ($142,322) over the year
- **Adspend efficiency** varies significantly across apps — some apps generate strong returns, others run near break-even
- **Profit per install** of $0.47 provides a clear benchmark for evaluating new app additions


---

## Tools Used

| Tool | Purpose |
|---|---|
| Power BI + DAX | Interactive dashboards, KPI tracking, financial analysis |
| Tableau | Executive summary, trend analysis, geographic breakdown |
| Python (pandas) | Mock data generation |

---

## Repository Structure

```
data-analytics-dashboards/
├── README.md
├── powerbi/
│   ├── README.md
│   ├── data/
│   │   └── payment_transactions.csv
│   └── screenshots/
│       ├── dash1.png
│       └── dash2.png
└── tableau/
    ├── README.md
    ├── data/
    │   └── app_performance.csv
    └── screenshots/
        └── Tableau_Dashboard.png
```

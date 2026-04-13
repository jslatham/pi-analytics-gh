# PI Analytics Platform

A multi-dashboard analytics app for Personal Injury Law Firms, built for the Swyft × Sigma hackathon.

## Dashboards

| # | Dashboard | Data Source | ETL |
|---|-----------|-------------|-----|
| 1 | 📞 **Intake Leak Monitor** | CallRail → Lead Docket | Call-to-Lead Matcher |
| 2 | 📊 **Full-Funnel Marketing ROI** | Google Ads + Lead Docket + Filevine | Attribution Spine |
| 3 | 🏷 **Marketing Source Quality** | Lead Docket | Source Normalization |
| 4 | 💰 **Case Cost Analysis** | QuickBooks GL | GL Account Classifier |

## Key Findings

- **87% of inbound calls** (2,976 of 3,421) never create a Lead Docket record — representing ~238 missed case opportunities
- **Referral sources** convert at 17.5% avg vs 5.8% for digital — a 3× gap invisible in existing reports
- **Advertising** is the firm's #2 expense at $4M+ with no dashboard connecting it to signed cases

## Tech Stack

- Vanilla JS + [Chart.js 4.4.1](https://www.chartjs.org/)
- Single self-contained HTML file (no build step, no dependencies to install)
- Designed for embedding via [Sigma Computing Plugin SDK](https://help.sigmacomputing.com/docs/intro-to-plugins)

## Live Demo

🔗 https://jslatham.github.io/pi-analytics-platform/

---

Built by [Swyft](https://swyft.co) · Sigma Hackathon 2026

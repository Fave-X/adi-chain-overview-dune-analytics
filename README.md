# ADI Chain — Dune Analytics

SQL-based on-chain analytics for ADI Chain, published as a Dune dashboard, tracking 30 days post mainnet interactions.

**Live dashboard:** https://dune.com/favedigitals/adi-chain-overview

![ADI Chain Dashboard](dashboard_screenshot.png)

---

## Queries included

- `daily_transactions.sql` — This shows the daily transaction trend of ADI Chain for the last 30 days post mainnet
- `active_addresses.sql` — Total Active address on ADI Chain for the last 30 days post mainnet
- `cumulative_addresses.sql` — growth of unique addresses over time
- `volume_by_day.sql` — on-chain volume aggregated daily
- `network_health.sql` — composite view of key network metrics

## About

Built with Dune Analytics v2 (Spark SQL). Data sourced directly from ADI Chain 
(Chain ID: 36900). These queries power the live dashboard and are published here 
for transparency and community use.

Built by [Tabugbo Chiagoziem Favour](https://twitter.com/FaveDigitalsHQ).

**Made with love ❤️ for the ADI community**

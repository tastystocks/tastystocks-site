# Tasty Stocks

**Expert stock picks, options trades, ETFs, and equity research — delivered daily.**

[tastystocks.com](https://tastystocks.com) · [Subscribe on Substack](https://tastystocks.substack.com/subscribe)

---

## About

Tasty Stocks is a financial newsletter with 200+ publications, a 95%+ win rate, 3,000+ total trades, and three years of consistent results. Covering stocks, options, ETFs, and equities with daily trade alerts.

## What's in This Repo

Source for **tastystocks.com** — a GitHub Pages site built with vanilla HTML, CSS, and JavaScript.

| File | Description |
|------|-------------|
| `index.html` | Main homepage |
| `features.html` | What You Get — full feature breakdown |
| `track-record.html` | Track Record — stats and win/loss distribution |
| `positions.html` | Closed Positions — live CSV-powered trades table |
| `pricing.html` | Pricing — plans, comparison table, and inline FAQ |
| `faq.html` | Frequently Asked Questions |
| `terms-of-service.html` | Terms of Service — legal, indemnification, disclaimer |
| `trades.csv` | Closed positions data — powers the live Closed Positions table |
| `sitemap.xml` | XML sitemap for search engine crawlers |
| `robots.txt` | Crawl directives for bots |
| `llms.txt` | AI-readable site description for LLM crawlers |
| `CNAME` | Custom domain config for GitHub Pages |

## trades.csv Format

The Closed Positions table on positions.html auto-loads from `trades.csv`. Expected columns:

```
Sold Date,Ticker,Type,Contract,Expiration,P&L,Position,Status
```

`Status` values: `Win`, `Loss`, `Open`

To add new trades, append rows to `trades.csv` and push to `main`.

## Deployment

Deployed via **GitHub Pages**. Every push to `main` goes live at [tastystocks.com](https://tastystocks.com) within minutes.

## What Subscribers Get

- Daily stock recommendations with entry/exit targets
- Options trade alerts (calls, puts, spreads) with exact strikes & expirations
- Pre-market and post-market analysis
- Short options / theta gang strategies
- ETF and equity research
- 401(k) strategy guidance
- Full closed positions log — every trade, wins and losses

## Pricing

| Plan | Price | Includes |
|------|-------|----------|
| Free | $0/mo | Weekly overview + select picks |
| Monthly | $8/mo | Full daily alerts + all features |
| Annual | $80/yr | Everything in Monthly — saves $16 |

## Disclaimer

Not financial advice. Past performance is not indicative of future results. All investing involves risk of loss.

---

© 2026 TastyStocks LLC

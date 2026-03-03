# FIS Platform Intelligence Map

Interactive visualization of FIS (Fidelity National Information Services) business structure, platform topology, transaction flows, and money lifecycle.

## What's Inside

- **Business Segments** — Banking Solutions ($7.3B) and Capital Markets ($3.2B) with expandable product lines
- **Platform Topology** — 7-layer architecture diagram from cloud infrastructure to customer channels
- **Money Lifecycle** — Flow map across Money at Rest → in Motion → at Work
- **Transaction Flows** — 6 interactive flow diagrams (Card Payment, Account Opening, Money Movement, Lending, Capital Markets, Treasury)
- **Industry Glossary** — 24 key fintech/banking terms
- **Value Delivery Matrix** — How FIS delivers value to banks, customers, and capital markets clients
- **Strategic Timeline** — Key moves from Worldpay divestiture through Issuer Solutions acquisition

## Deploy to Fly.io

```bash
fly auth login
fly launch --name fis-platform-map --region iad --no-deploy --yes
fly deploy
```

Auto-deploys on push to `main` via GitHub Actions (requires `FLY_API_TOKEN` secret).

## Tech Stack

- Single `index.html` — zero dependencies, pure HTML/CSS/JS
- Google Fonts (Inter + JetBrains Mono)
- nginx Alpine container
- Fly.io deployment

## Sources

- [Fintech Wrapup: Deep Dive into FIS's Technology Stack](https://www.fintechwrapup.com/p/deep-dive-unwrapping-fiss-technology)
- [FIS 10-K Annual Report 2025](https://www.stocktitan.net/sec-filings/FIS/10-k-fidelity-national-information-services-inc-files-annual-report-faa6cf780c27.html)
- [FIS Global Products](https://www.fisglobal.com/products)

### Hi, I'm Tao Zhu

I'm the independent developer behind **LocalLedger Studio** and **RiskOps Lab**. Ignore the auto-generated `-bot` suffix on this GitHub handle — real human here, writing plain JavaScript and Node.js without a VC deck or a sales team.

Two stubborn beliefs sit behind everything I ship:

> **Financial files shouldn't be uploaded to random clouds, and vendor security claims should be checked against live DNS instead of marketing PDFs.**

---

### Live Free Tools & Open Research (No Signup, No Tracking)

| Project | What it does | Link |
| :--- | :--- | :--- |
| **AdPack HTML5** | Free 0-upload browser HTML5 Ad ZIP Pre-Flight Validator (Google Ads 600 KB, IAB 150 KB, DV360, Adform, App Campaigns + sandboxed preview) & Figma pure-CSS banner exporter | [Free ZIP Validator](https://adpack.localledgerstudio.xyz/) · [vs Bannerify](https://adpack.localledgerstudio.xyz/bannerify-alternative) |
| **LocalLedger Studio** | Browser-local single-file workbenches: EInvoiceLocal (XRechnung / ZUGFeRD), CRAGuard (EU CRA SBOM), PropGuard, TradeGuard & YC DNS datasets | [www.localledgerstudio.xyz](https://www.localledgerstudio.xyz/) |
| **RiskOps MCP Suite** | Zero-dependency Node.js stdio MCP server + free web portal (`audit_vendor_security`, SEC 8-K filings, Google OSV.dev CVEs, IEEE-754 quant math) | [Repo](https://github.com/qq459538565-bot/riskops-mcp-suite) · [Portal](https://qq459538565-bot.github.io/riskops-mcp-suite/) |
| **LocalLedger Bank PDF -> CSV** | Converts digital US/UK/EU (`1.234,56 €`, `DD.MM.YYYY`) & Amex bank PDFs to QuickBooks/Xero CSV inside your browser tab — works with Wi-Fi off | [Try Live Demo](https://qq459538565-bot.github.io/riskops-mcp-suite/bank-converter/index.html) |
| **TickTieLocal** | Offline audit PDF tick-and-tie matcher for solo CPAs and small firms who don't want a five-figure annual DataSnipper contract | [Try Live Demo](https://qq459538565-bot.github.io/riskops-mcp-suite/tick-tie/index.html) |
| **112-SaaS & 24-AI DNS Benchmark** | Weekly Cloudflare DoH audit of DMARC, SPF, CAA, MX & Vanta/Drata Trust Centers (open CSV & JSON, CC BY 4.0) | [Read Report](https://qq459538565-bot.github.io/riskops-mcp-suite/reports/state-of-saas-security-2026.html) |

---

### Hosted MCP Servers & Commercial JS SDKs

- **5 Pay-Per-Event Apify MCP Actors** ([apify.com/durative_hairstreak](https://apify.com/durative_hairstreak)) — batch & scheduled endpoints for SEC EDGAR Form 8-K risk signals, SaaS Statuspage SLA uptime math, bulk B2B vendor DNS/Trust Center audits, OSS supply-chain CVE + CISA KEV checks, and deterministic DCF/Kelly/Sharpe finance math.
- **LocalLedger-JS Bank Statement Parser SDK** ([Codester #76737](https://www.codester.com/items/76737/localledger-js-bank-statement-parser-sdk)) — zero-dependency ES module (`statementParser.mjs`, 10/10 passing `node --test` specs) for teams embedding offline bank PDF parsing into their own apps.
- **QuantCalc-JS Financial Analysis Widget** ([Codester #76738](https://www.codester.com/items/76738/quantcalc-js-financial-analysis-widget)) — drop-in 4-tab JS widget (5-yr DCF + 5×5 sensitivity grid, Sharpe/Sortino/Max Drawdown/VaR, Half-Kelly sizing, Loan & Newton-Raphson IRR).

---

### What I Won't Pretend These Tools Do

- **No camera-photo OCR.** LocalLedger reads native selectable-text PDFs straight from online banking portals. If you feed it a crooked phone photo of a paper statement, it flags `SCANNED_PDF_DETECTED` honestly instead of guessing digits.
- **No cloud accounts or forced subscriptions.** Local tools run in browser memory so client numbers never touch my servers. Hosted Apify Actors charge per event only when you run bulk jobs.
- **Public data only.** Every security and filing tool queries official public sources (`data.sec.gov`, Cloudflare DoH, Atlassian Statuspage JSON, Google OSV.dev, CISA KEV) — zero scraping behind logins, zero personal PII.

---

### Reach Me Directly

Found a bug in a parser, spotted a stale DNS record, or want to compare notes on local-first accounting tools and MCP servers?

- Email: [qq459538565@gmail.com](mailto:qq459538565@gmail.com)
- Web: [localledgerstudio.xyz](https://www.localledgerstudio.xyz/) · [riskops-mcp-suite](https://qq459538565-bot.github.io/riskops-mcp-suite/)

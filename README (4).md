<p align="center">
  <img src="assets/brand/freclean-logo.jpg" alt="FreClean logo" width="120">
</p>

<h1 align="center">freclean-investor-book</h1>

<p align="center">
  <b>Official FreClean investor book covering the company, products, services, market opportunity, business model, growth strategy, risks, and investment thesis.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/License-MIT%20(docs%20%26%20code)-blue.svg" alt="License: MIT for documentation and code">
  <img src="https://img.shields.io/badge/Status-v1.0.0-success.svg" alt="Status: v1.0.0">
  <img src="https://img.shields.io/badge/Financials-Illustrative%20Scenarios%20Only-orange.svg" alt="Financials: illustrative scenarios only">
</p>

---

## What this repository is

This repository contains the official FreClean Investor Book: a standalone, evidence-based publication covering FreClean's company profile, market opportunity, products, services, customers, business model, operations, technology, brand, distribution, financial framework, funding, risk, growth strategy, and investment thesis.

Start reading at [`INVESTOR_BOOK.md`](INVESTOR_BOOK.md), or open the compiled [`FreClean_Investor_Book.pdf`](FreClean_Investor_Book.pdf) (65 pages) for a single-file, publication-formatted version.

## What this repository is not

- Not a marketing brochure: every claim is labeled by verification status (Confirmed / Planned / TBD / Not Yet Verified / Concept / Illustrative Scenario / Assumption). See [Appendix A](book/appendices/appendix-a-verification-status-legend.md).
- Not a promise of investment returns; see [`INVESTMENT_THESIS.md`](INVESTMENT_THESIS.md).
- Not dependent on any other FreClean repository: this book is self-contained; every fact it relies on is restated directly within it.

## Repository structure

```
freclean-investor-book/
├── README.md
├── INVESTOR_BOOK.md              Cover, table of contents, full book entry point
├── FreClean_Investor_Book.pdf    Compiled, publication-ready PDF (65 pages)
├── EXECUTIVE_SUMMARY.md
├── INVESTMENT_THESIS.md
├── COMPANY_PROFILE.md
├── MARKET_ANALYSIS.md
├── BUSINESS_MODEL.md
├── FINANCIAL_FRAMEWORK.md
├── RISK_ANALYSIS.md
├── GROWTH_STRATEGY.md
├── ROADMAP.md
├── FUNDING_STRATEGY.md
├── INVESTOR_FAQ.md
├── CHANGELOG.md
├── LICENSE
├── .gitignore
│
├── book/
│   ├── chapters/          19 parts, full book content in reading order
│   ├── appendices/        Verification-status legend, glossary
│   └── references/        Pointer to sources/REFERENCES.md
│
├── diagrams/               12 original Mermaid diagrams (source + rendered SVG)
│   ├── business-model/  ├── operating-model/      ├── geographic-expansion/
│   ├── value-chain/     ├── growth-strategy/       ├── organization/
│   ├── customer-flow/   ├── distribution/          ├── capital-flow/
│   ├── ecosystem/       ├── revenue-model/         └── product-lifecycle/
│
├── charts/                 Real sourced-data chart + one labeled illustrative chart
├── tables/                 Competitive matrix, product status, financial scenarios, KPI framework
├── assets/
│   ├── brand/              Official logo
│   ├── products/           Labeled CONCEPT product visuals
│   ├── company/             (empty: no authentic company photography exists yet)
│   └── investor/            Book cover graphic
├── sources/
│   └── REFERENCES.md       Every external citation used in this book
└── releases/
    └── RELEASE_NOTES_v1.0.0.md
```

## How to read this book

- **Full read:** start at [`INVESTOR_BOOK.md`](INVESTOR_BOOK.md), which links all nineteen parts in order.
- **Quick read:** [`EXECUTIVE_SUMMARY.md`](EXECUTIVE_SUMMARY.md) → [`INVESTMENT_THESIS.md`](INVESTMENT_THESIS.md) → Part XVII, [What Still Needs to Be Proven](book/chapters/17-what-still-needs-to-be-proven.md).
- **Topic-specific:** any of the standalone root-level documents (Market Analysis, Business Model, Financial Framework, Risk Analysis, Growth Strategy, Investor FAQ).

## Diagrams

Every diagram is genuine Mermaid source representing a specific business concept: none are decorative. GitHub renders the Mermaid code embedded in each chapter automatically; rendered SVG versions are also available in [`diagrams/`](diagrams/) for reuse outside GitHub (e.g., in a slide deck).

## Financial data

**No FreClean financial data (revenue, cost, margin) has been published.** [`FINANCIAL_FRAMEWORK.md`](FINANCIAL_FRAMEWORK.md) and [`book/chapters/14-financial-framework.md`](book/chapters/14-financial-framework.md) contain clearly labeled **Illustrative Scenarios**, worked examples using stated hypothetical assumptions, meant only to demonstrate the calculation method. Do not read any number in either document as an actual FreClean figure.

## Sources

Every external (non-FreClean) statistic in this book is cited in [`sources/REFERENCES.md`](sources/REFERENCES.md), including full publisher names, report titles, and dates.

## License

Documentation, diagrams, charts, and code in this repository are released under the [MIT License](LICENSE). The FreClean name and logo remain proprietary; see [`freclean-brand/TRADEMARK.md`](https://github.com/FreClean/freclean-brand/blob/main/TRADEMARK.md).

---

<p align="center"><i>Clean Today. Sustain Tomorrow.</i></p>

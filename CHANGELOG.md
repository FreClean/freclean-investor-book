# Changelog

## [1.1.0] - 2026-08-09

### Changed
- Full repository-wide terminology migration from cUSD to USDm, reflecting the Mento Protocol's late-2025 rebrand of its stablecoin family. Every reference was reviewed in context rather than blindly replaced; three references intentionally retain the historical name "cUSD" where explaining the rebrand itself required it (`book/appendices/appendix-b-glossary.md`, `book/chapters/11-technology.md`, `INVESTOR_FAQ.md`).
- Rewrote the Digital Payments and "CELO and USDm Integration" sections of Part XI (Technology) for clearer, more natural prose, and added coverage of the Valora wallet, which was previously unmentioned despite being part of FreClean's stated payment stack.
- Removed every em dash from the book (262 instances across 45 files) and replaced each with punctuation suited to its specific sentence: colons for structural labels and headers, semicolons and commas for prose asides, and full sentence breaks where a passage was really joining two independent thoughts.
- Rewrote `EXECUTIVE_SUMMARY.md` and reworked passages in `INVESTMENT_THESIS.md`, `FINANCIAL_FRAMEWORK.md`, and multiple chapters where mechanical punctuation replacement had produced awkward double-colon constructions, restoring natural sentence flow.
- Updated four Mermaid diagrams (Business Model Canvas, Customer Journey, Operating Model, Value Chain) to use USDm in place of cUSD, and re-rendered their SVG and PNG outputs.
- Regenerated `FreClean_Investor_Book.pdf` with corrected diagram rendering (a sizing bug had previously caused most diagrams to render as blank or near-invisible thumbnails, which in turn produced several genuinely blank pages), a proper list-formatted table of contents, and FreClean-branded typography via a new stylesheet at `pdf/pdf-style.css`.

### Fixed
- A diagram-rendering bug that caused 11 of 12 Mermaid diagrams to be exported as tiny, effectively blank images, and caused 8 fully blank pages in the PDF (pages 47 through 53 and page 65 of the previous build). Root cause: an SVG-to-PNG conversion step that mis-measured each diagram's true dimensions before rendering. Fixed by rendering every diagram against a large, fixed-size container instead of a guessed one.
- The PDF's table of contents, which had collapsed into a single unreadable paragraph due to a Markdown list that relied on single line breaks pandoc's parser does not honor; converted to a proper Markdown list.

## [1.0.0] - 2026-08-08

### Added
- Complete 19-part investor book under `book/chapters/`, covering Company, Problem & Opportunity, Products, Services, Customers, Business Model, Products+Services Ecosystem, Market, Competitive Landscape, Operations, Technology, Brand, Distribution & Expansion, Financial Framework, Funding, Risk, What Still Needs to Be Proven, Growth Strategy, and Investment Thesis.
- Two appendices: verification-status legend and glossary.
- Standalone root-level documents: Executive Summary, Investment Thesis, Company Profile, Market Analysis, Business Model, Financial Framework, Risk Analysis, Growth Strategy, Roadmap, Funding Strategy, Investor FAQ.
- Twelve original Mermaid diagrams (source `.mmd` + rendered `.svg`), each addressing a distinct, real business concept: Business Model Canvas, Value Chain, Customer Journey, Product+Services Ecosystem, Revenue Model, Distribution Network, Operating Model, Growth Strategy Timeline, Geographic Expansion, Ecosystem Structure, Investor Capital Flow, and Product Development Lifecycle.

### Documentation
- Full source citation list (`sources/REFERENCES.md`) covering global cleaning-products market-size research (six independent publishers) and Haiti macroeconomic/diaspora-remittance data (World Bank, Trading Economics, IHSI/The Haitian Times).
- Structured, reusable reference tables: competitive matrix, product status matrix, financial scenario framework, and KPI framework.

### Assets
- Official FreClean logo copied into `assets/brand/`.
- Two labeled CONCEPT product visuals reused from `freclean-products` under `assets/products/`.
- One chart built from real, sourced market-research data and one explicitly labeled Illustrative Scenario chart under `charts/`.
- An original investor-book cover graphic under `assets/investor/`.

### Infrastructure
- MIT `LICENSE` for documentation/code, with a trademark carve-out note for the FreClean name and logo.
- `.gitignore` for common OS/editor/build artifacts.

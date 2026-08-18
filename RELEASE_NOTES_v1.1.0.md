# FreClean Investor Book v1.1.0 - Editorial and Technical Refactor

## Overview

This release is a complete editorial and technical review of the v1.0.0 investor book, focused on three things: migrating payment terminology from cUSD to USDm across the entire repository, rewriting mechanical or awkward prose into natural, human-edited language, and fixing a diagram-rendering defect that had left the PDF with eight blank pages.

## What Changed

### USDm terminology migration

Every reference to cUSD, CUSD, or cusd was reviewed in its original context, not replaced blindly. The vast majority described FreClean's stated payment acceptance and were updated to USDm directly. Three references were deliberately left mentioning "cUSD" by name, each one specifically explaining the Mento Protocol's late-2025 rebrand of cUSD to USDm, since removing the old name would have made the historical explanation incoherent. Those three live in the glossary, in Part XI (Technology), and in the Investor FAQ.

Part XI's payments section was substantially rewritten, not just find-and-replaced: it now explains USDm's practical role, distinguishes it clearly from the more volatile CELO token, and adds coverage of the Valora wallet, which FreClean's materials name as the recommended way to hold and send both assets but which the previous edition of this book never mentioned.

### Editorial pass

Every em dash in the book, 262 of them across 45 files, was removed and replaced with punctuation suited to the specific sentence: colons for headers and labeled definitions, semicolons and commas for prose asides, and full sentence breaks where two independent thoughts had been awkwardly joined. A first mechanical pass introduced some double-colon constructions; those were found and hand-corrected afterward, along with a full rewrite of `EXECUTIVE_SUMMARY.md` and targeted rewrites in `INVESTMENT_THESIS.md`, `FINANCIAL_FRAMEWORK.md`, and several chapters.

### PDF defect fix

The v1.0.0 PDF had 8 fully blank pages (pages 47 through 53 and page 65), caused by a bug in the SVG-to-PNG conversion step used to embed diagrams: the script measured a diagram's dimensions incorrectly before rendering it, which for most diagrams produced a nearly invisible 40x40 pixel image and, for one, a 42x840 pixel sliver that forced seven blank pages around it. All twelve diagrams were re-rendered against a correctly sized container, verified individually, and the PDF was rebuilt with a proper list-formatted table of contents (the previous version had collapsed into a single unreadable paragraph) and a new stylesheet, `pdf/pdf-style.css`, applying FreClean's brand colors to headings and tables throughout.

## Quality & Validation

Performed and confirmed on this release:
- Repository-wide search for "cUSD", "CUSD", "cusd": 3 results, all intentional and reviewed individually.
- Repository-wide search for em dashes: 0 results.
- Repository-wide search for common AI-generated stock phrases ("rapidly evolving," "cutting-edge," "game-changing," and similar): 0 results.
- Every internal Markdown link checked programmatically: 0 broken links.
- All 16 SVG files (12 diagrams, cover art, 2 concept product visuals, plus the palette-independent brand logo) confirmed well-formed.
- Every PDF page rendered and scanned for blank content; the 2 pages that scored as mostly white were manually reviewed and confirmed to be normal short chapter-transition text, not defects.

## Not Changed

The book's 19-part structure was kept as-is. It already answers the twenty investor questions this review was asked to check for, and restructuring it would not have added clarity. No new financial figures, customers, partnerships, or certifications were added; none exist to add. Fragrance and perfumery products, mentioned as a possible topic in this review's brief, do not appear anywhere in FreClean's published product catalog, so this book does not describe them; adding them would have been fabrication.

## Related Repositories

This book remains fully self-contained and does not reference or depend on any other FreClean repository.

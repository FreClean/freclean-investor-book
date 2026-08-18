# Diagrams

Twelve diagrams, each addressing a distinct business concept requested for this book. Every diagram exists as a Mermaid source file (`.mmd`): GitHub renders these natively when embedded in Markdown: and as a rendered, publication-ready SVG in the same folder.

| # | Diagram | Folder | Used in |
|---|---|---|---|
| 1 | Business Model Canvas | `business-model/` | Part VI |
| 2 | Value Chain | `value-chain/` | Referenced in Part X |
| 3 | Customer Journey | `customer-flow/` | Part V |
| 4 | Product + Services Ecosystem | `ecosystem/` | Part VII |
| 5 | Revenue Model | `revenue-model/` | Part XIV |
| 6 | Distribution Network | `distribution/` | Part XIII |
| 7 | Operating Model | `operating-model/` | Part X |
| 8 | Growth Strategy Timeline | `growth-strategy/` | Part XVIII |
| 9 | Geographic Expansion Strategy | `geographic-expansion/` | Part XIII |
| 10 | Organizational / Ecosystem Structure | `organization/` | Part I |
| 11 | Investor Capital → Business Growth Flow | `capital-flow/` | Part XV |
| 12 | Product Development Lifecycle | `product-lifecycle/` | Part III |

## How these were produced

Each `.mmd` file is genuine Mermaid diagram source, written to represent a real, specific business concept from this book: none are decorative. They were rendered to SVG using the Mermaid CLI (`mmdc`) with a FreClean-colored theme, verified by rendering each SVG in a headless browser and visually reviewing the output before inclusion.

## Reading a diagram on its own

Every diagram is also embedded directly in its relevant chapter under [`../book/chapters/`](../book/chapters/), where GitHub will render the Mermaid source inline automatically. The files in this folder are the same diagrams as standalone, reusable assets (e.g., for a slide deck or a printed appendix).

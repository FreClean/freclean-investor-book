# PDF Build Assets

`pdf-style.css` is the stylesheet used to typeset [`../FreClean_Investor_Book.pdf`](../FreClean_Investor_Book.pdf) from the book's Markdown source (via `pandoc` + `wkhtmltopdf`). It applies FreClean's brand colors to headings, tables, and blockquotes so the PDF matches the visual identity defined in `freclean-brand`.

This file is kept so the PDF can be rebuilt after future edits to the book's Markdown content, without having to reverse-engineer the styling from scratch.

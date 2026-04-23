# Included Studies — PDF Storage

Storage folder for full-text PDFs of included studies. Naming convention:

```
S###-citationkey.pdf
```

For example:
- `S001-kim2019kbs.pdf`
- `S002-larsen2013behavioral.pdf`
- `S013-bratu2006integrated.pdf`

## Note on PDF availability

All 142 included studies are documented in `../included-studies-list.xlsx`
with full bibliographic details. PDFs should be retrieved through institutional
library access using the citation details in that spreadsheet.

If publisher licensing restricts redistribution, add the following to avoid
accidentally committing PDFs:

```
04-included-studies/pdfs/*.pdf
```

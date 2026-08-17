# Resume / CV — Tamim Hmizi

LaTeX sources and compiled PDFs. Written for Overleaf (pdfLaTeX).

| File | Language | Output |
| --- | --- | --- |
| `resume-en.tex` | English | `resume-en.pdf` |
| `cv-fr.tex` | French | `cv-fr.pdf` |

Both share the same layout: single column, Charter, ATS-safe encoding
(`glyphtounicode`, T1). The French source additionally loads
`babel[french]` for hyphenation and typographic spacing.

## Updating

1. Edit the `.tex` file.
2. Compile in Overleaf with **pdfLaTeX**.
3. Download the PDF and commit it here under the matching name.
4. Copy it into the portfolio site as well — `Portfolio/public/resume-en.pdf`
   and `Portfolio/public/cv-fr.pdf` are what the download buttons serve.

Keep the two languages in sync: any change to a role, project, or metric
belongs in both files.

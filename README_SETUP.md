# MMSC Dissertation LaTeX Setup

This project is configured around the Oxford OCIAM thesis class supplied with the original Overleaf project.

## Main file

Compile `main.tex`.

## Structure

- `acknowledgements.tex` - acknowledgements front matter
- `abstract.tex` - abstract placeholder
- `ai-declaration.tex` - AI-use declaration placeholder
- `chapters/` - Chapters 1-8
- `appendices/` - Appendices A-D
- `figures/` - dissertation figures
- `refs.bib` - BibTeX database
- `ociamthesis.cls` - Oxford OCIAM class
- `oxlogo.png` - Oxford logo used by the title page

## Formal format settings

- 12pt document class
- OCIAM text area: 6 in (15.24 cm) wide and 9 in (22.86 cm) high; this is the official class supplied by Oxford and matches the handbook's stated OCIAM-compliance route
- `baselinestretch = 1.25`
- title page and required front matter
- Roman numbering for contents/list pages and Arabic numbering restarted at Chapter 1

## Useful LaTeX facilities already loaded

- `amsmath`, `amssymb`, `amsthm`, `mathtools`
- `booktabs`, `array`
- `algorithm`, `algpseudocode`
- `graphicx`
- `hyperref`, `cleveref`
- `microtype`

The theorem-like environments `theorem`, `proposition`, `lemma`, `corollary`, `definition`, `assumption`, and `remark` are already defined.

## Overleaf

After uploading/replacing the revised files, set `main.tex` as the Main document if Overleaf does not select it automatically.

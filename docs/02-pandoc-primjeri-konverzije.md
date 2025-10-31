---
title: "Uvod u Pandoc"
author: "Martin Prtenjača"
date: "31. 10. 2025."
lang: "hrvatski"
---

# Pandoc
Pandoc je besplatni, univerzalni konverter za dokumente, koristi se za pretvorbu jednog markup formata u drugi. Postoje formati za koje je moguća pretvorba samo u njih ili iz njih, ali većina formata funkcionira na način da možemo neki format pretvoriti u njih, ili njih pretvoriti u neki drugi. Konverziju radimo u command promptu.

## Neki od ključnih primjera konverzije:

### .md -> .html

```
pandoc -f markdown -t html5 -o output.html input.md -c style.css
```
- pandoc -> poziva pandoc konverter dokumenata
- -f markdown -> specificira da je format koji unosimo markdown
- -t html5 -> označava da je format koji želimo html5
- -o output.html -> diktira pandocu kako želimo da se nova datoteka zove (output.html)
- input.md -> naziv datoteke koju smo ubacili u konverter
- -c style.css -> linka CSS file (style.css) u HTML izlaznu datoteku (dodaje <link rel="stylesheet" href="style.css"> u glavni dio datoteke (<head>)


### .md → .pdf
#### Zahtijeva LaTex distribuciju: TeX Live((Linux/macOS), MikTeX(Windows), MacTeX (macOS)
```
pandoc input.md -o output.pdf
```
- pandoc -> pali i poziva pandoc konverter za dokumente
- input.md -> označava datoteku koju želimo mijenjati
- -o output.pdf -> kaže ime nove datoteke

### .md → .docx
```
pandoc input.md -o output.docx
```
- pandoc -> pali i poziva pandoc konverter za dokumente
- input.md -> označava datoteku koju želimo mijenjati
- -o output.docx -> kaže ime nove datoteke

### Korisni linkovi
- [Pandoc](https://pandoc.org/)
- [Neki primjeri konverzije](https://pandoc.org/demos.html)

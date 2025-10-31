---
title: "Uvod u Markdown"
author: "Martin Prtenjača"
date: "31. 10. 2025."
lang: "hrvatski"
---

# Markdown
Markdown je lightweight markup jezik koji se koristi za formatiranje običnih tekstova s ciljem da dokumentacija bude čitljiva i neupadljiva. Najveća razlika između markdowna i WYSIWYG editora (poput Microsoft Worda) je ta što ne klikamo gumbove da bi formatirali tekst, već koristimo određenu sintaksu, neku od koje ćemo se dotaknuti u nastavku.
Zašto koristiti markdown? 
1. Jer je sveprisutan i koristi se na platformama poput GitHub-a
2. Ima pravi omjer snage i jednostavnosti
3. Dovoljno je moćan za stvaranje tehničke dokumentacije, dokumenata i knjiga
4. Postoje specifični alati koji ga koriste
5. Mnoga radna mjesta imaju kao uvjet poznavanje Markdowna

## Osnovna sintaksa
### Naslovi (Headings)
Koriste znakove hash (`#`); broj znakova definira razinu naslova (H1 <-> H6).
```
# Glavni naslov (H1)
## Sekundarni naslov (H2)
### Tercijarni naslov (H3)
```

### Isticanje (Emphasis)
Za isticanje se koriste asteriski (`*`) ili podvlake (`_`).
```
**Podebljani tekst**
__Podebljani tekst__

*Kurzivni tekst*
_Kurzivni tekst_

***Podebljano i kurziv***
```

### Popisi (Lists)
Popisi mogu biti numerirani ili nenumerirani. Koristimo tabulator ili četiri razmaka da ih indentamo.

**Numerirani popis (Ordered Lists)**
```
1. Prvi korak
2. Drugi korak
3. Treći korak
```

**Nenumerirani popis (Unordered Lists)**
```
- Prva stavka (Može se koristiti i * ili + umjesto -)
- Druga stavka
```

### Računalni kod
Za označavanje riječi ili fraze kao kod koristimo (` `` `).
```
Naredba `nano` je korisna.
```

## Poveznice
Tekst linka ide u uglate( [] ), a URL u okrugle ( () ) zagrade, i možete dodati i tooltip(naslov).
```
Posjetite [StormHB Markdown guide](https://stormhb.github.io/pandoc-markdown/ "Moj Markdown vodič")
```

## Slike
Kao i linkovi uz dodatak uskličnika (!) ispred svega.
```
![Tux slika](main/Tux.png)
```

## Proširena sintaksa
Dodaje funkcionalnosti (tablice, liste zadataka, itd...) koje nisu bile u originalnom Gruberovom dizajnu, ne podržavaju ih sve aplikacije pa ih se nećemo dotaknuti, ali možete sami provjeriti.


## Za više informacije sami pogledajte:
### [Markdown Tutorial](https://www.markdowntutorial.com/)
### [Markdown Guide](https://www.markdownguide.org/getting-started/)

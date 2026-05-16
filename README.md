# Portfolio Cees ALO

Dit is een statische portfolio-website voor GitHub Pages.

De website hoort bij mijn afstudeerfase aan de HAN ALO en gaat over:

- LUK 9 – Visie ontwikkelen en uitdragen
- LUK 10 – Professionele bekwaamheid onderhouden en profileren

## Bestanden

De website bestaat uit:

```text
portfolio-cees-alo/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    └── bewijzen/
        ├── kernkwadrant.pdf
        ├── voetbal-vs-zaal.pdf
        ├── reflectieverslag.pdf
        ├── checklist.pdf
        ├── lesvoorbereidingen.pdf
        ├── lesverslagen.pdf
        ├── gezond-fit.pdf
        └── onderzoeksverslag.pdf
```

## Lokaal bekijken

Je kunt de website lokaal openen door dubbel te klikken op:

```
index.html
```

De website opent dan in je browser.

## Bewijsstukken toevoegen

Plaats je bewijsstukken in deze map:

```
assets/bewijzen/
```

Gebruik dezelfde bestandsnamen als in index.html, of pas de links in index.html aan.

Voorbeeld:

```html
<a href="assets/bewijzen/kernkwadrant.pdf">Bekijk bewijsstuk</a>
```

## Publiceren via GitHub Pages

### Stap 1: Maak een repository

1. Ga naar GitHub.
2. Maak een nieuwe repository.
3. Geef de repository bijvoorbeeld deze naam:
   ```
   portfolio-cees-alo
   ```
4. Zet de repository op **Public**.
5. Maak de repository aan.

### Stap 2: Upload de bestanden

Upload deze bestanden naar de hoofdmap van de repository:

- `index.html`
- `style.css`
- `script.js`
- `README.md`

Maak daarna deze mappenstructuur aan:

```
assets/bewijzen/
```

Upload daar later je bewijsstukken.

### Stap 3: Zet GitHub Pages aan

1. Ga in je repository naar **Settings**.
2. Klik links op **Pages**.
3. Kies bij **Source** voor **Deploy from a branch**.
4. Kies bij **Branch** voor **main**.
5. Kies bij map voor **/ (root)**.
6. Klik op **Save**.

### Stap 4: Open je website

Na ongeveer een minuut verschijnt er een link naar je website.

De link ziet er ongeveer zo uit:

```
https://jouwgebruikersnaam.github.io/portfolio-cees-alo/
```

## Aanpassen

De inhoud staat vooral in `index.html`.

De vormgeving staat in:

```
style.css
```

De kleine interactieve functies staan in:

```
script.js
```

## Belangrijke TODO's

Op de website staan nog twee TODO-blokken:

1. Een concrete lessituatie toevoegen bij ethische vraagstukken.
2. Concrete feedbackmomenten toevoegen bij de ontwikkelcyclus.

Deze onderdelen kun je later aanvullen in `index.html`.

## Footer

De footer van de website is:

```
Portfolio Cees ALO | LUK 9 & 10 | Cees Zwartkruis
```

---

## Mappenstructuur voor GitHub

Maak dit aan:

```text
portfolio-cees-alo/
├── index.html
├── style.css
├── script.js
├── README.md
└── assets/
    └── bewijzen/
```

Je bewijsstukken kun je later in `assets/bewijzen/` zetten. Let op: als een knop naar `assets/bewijzen/kernkwadrant.pdf` verwijst, moet het bestand ook precies zo heten.

# Ensemble · XVII — nettside

En statisk, responsiv nettside for et ensemble med sopran, viola da gamba og cembalo. Klar for GitHub Pages. Ingen byggeverktøy eller JavaScript kreves.

## 1. Legg inn egne filer

Bytt ut plassholderfilene ved å legge inn følgende **eksakte filnavn**:

- `assets/images/ensemble-1.jpg` — hovedbilde (helst liggende, minst 1800 px bredt)
- `assets/images/ensemble-2.jpg` — stort galleribilde
- `assets/images/ensemble-3.jpg` — galleribilde
- `assets/images/ensemble-4.jpg` — galleribilde
- `assets/audio/bernier-diane-sats-2.mp3` — Bernier, *Diane*, andre sats
- `assets/audio/la-barre-esperance.mp3` — La Barre, *Si c’est un bien que l’espérance*

Før filene er lagt inn, vil bildene ikke vises og lydspillerne ikke kunne spille av. Bilder og lyd følger **ikke** med i pakken.

## 2. Tilpass tekst

Åpne `index.html` og erstatt:
- `ENSEMBLE · XVII` med ensemblets virkelige navn (to steder, samt sidetittelen)
- `[Legg gjerne inn navnene ...]` med navn og eventuelt biografier
- `kontakt@example.com` med riktig e-postadresse (både lenke og synlig tekst)
- Bildetekster og beskrivende alt-tekster slik at de passer bildene

Sitatet nederst er **ikke** et dokumentert historisk sitat og er derfor satt som en generell inspirasjonstekst. Erstatt eller fjern det hvis ønskelig.

## 3. Publiser på GitHub Pages

Opprett et nytt **public** GitHub-repository, for eksempel `ensemble-xvii`. Legg filene i repository-roten (ikke selve `barokktrio`-mappen rundt dem):

```bash
git init
git add .
git commit -m "Initial ensemble website"
git branch -M main
git remote add origin https://github.com/BRUKERNAVN/ensemble-xvii.git
git push -u origin main
```

På GitHub: **Settings → Pages → Build and deployment → Deploy from a branch**. Velg `main` og `/ (root)` og lagre.

Adressen blir normalt `https://BRUKERNAVN.github.io/ensemble-xvii/`.

GitHub Pages serverer statiske filer direkte. Sørg for at du har rettigheter til å publisere fotografiene og lydopptakene. Store MP3-filer kan påvirke lasting og repository-størrelse.

## 4. Lokal forhåndsvisning

Kjør i mappen:

```bash
python3 -m http.server 8000
```

Åpne `http://localhost:8000` i nettleseren.

## Design

- Typografi: Cormorant Garamond (tynn serif) + DM Sans (navigasjon og brødtekst), lastes fra Google Fonts.
- Farger: varm elfenben, dempet gull og mørk grønn.
- Responsivt oppsett, tastaturnavigasjon, hopp-til-innhold, semantiske overskrifter og innebygde HTML5-lydspillere.
- Nettstedet virker uten JavaScript. Fontene faller tilbake til lokale standardfonter hvis Google Fonts ikke kan nås.


Oppdatert 1. november 2026: Hovedbilde BELLAMORK_261029-5.jpeg med tekst nederst til venstre i varm elfenben (#fff4df), over en mørk gradering. Musikerportretter og CV for Karin Hannisdal og Lars Henrik Johansen er lagt til. Susannes CV avventer tekst. De to eksisterende WAV-filene følger med.
# ensemblexvii

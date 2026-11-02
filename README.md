<div align="center">

# ENSEMBLE · XVII

### *L’art de toucher le cœur*

Fransk kammermusikk fra slutten av 1600-tallet  
Sopran · Viola da gamba · Cembalo

— ✦ —

**Susanne Mørk** · **Karin Hannisdal** · **Lars Henrik Johansen**

</div>

## Musikk, poesi og retorikk

Ved det franske hoffet på slutten av 1600-tallet møttes poesi og musikk i en kunstform der hver gest, hver dissonans og hver ornamentering bar mening.

Ensemble XVII utforsker denne intime musikken med sopran, viola da gamba og cembalo — dens klanglige nyanser, dramatiske kontraster og særegne forbindelse mellom ord og tone.

Dette repositoriet inneholder ensemblets nettside: en presentasjon av musikerne, utvalgte innspillinger og fotografier fra Frogner hovedgård.

## Et rom for musikken

Nettsidens uttrykk henter farger fra fotografiene: varm elfenben, dempede gulltoner og dyp grønn. Store bilder, luftige tekstflater og den klassiske antikvaskriften *Cormorant Garamond* gir musikken en rolig ramme. *DM Sans* brukes til navigasjon og mindre tekster.

Nettsiden er laget med HTML og CSS, med tilpasninger for mobil, nettbrett og større skjermer. Lydopptakene spilles av med nettleserens innebygde lydspiller. Ingen installasjon eller bygging er nødvendig.

## Repertoaret på siden

| Komponist | Verk |
| :--- | :--- |
| Joseph Chabanceau de La Barre | *Si c’est un bien que l’espérance* |
| Nicolas Bernier | Andre sats fra kantaten *Diane* |

## Arbeide med nettsiden

Åpne `index.html` i en nettleser for en enkel forhåndsvisning. Skriftene lastes fra Google Fonts og krever internettilgang; uten tilkobling brukes reserveskrifter.

De sentrale filene er:

```text
.
├── index.html          Nettsidens innhold og struktur
├── styles.css          Typografi, farger og layout
├── .nojekyll           Lar GitHub Pages servere filene direkte
└── assets/
    ├── images/         Ensemblebilder, portretter og interiører
    └── audio/          Lydopptak
```

**Tekster og kontaktinformasjon** redigeres i `index.html`. Kontaktfeltet inneholder foreløpig `kontakt@example.com`; erstatt både den synlige adressen og adressen i `mailto:`-lenken før siden tas i bruk.

**Utseendet** redigeres i `styles.css`. Fargevariablene ligger i `:root` øverst i filen. Hovedbildet er angitt som bakgrunnsbilde i CSS, mens portrettene og galleribildene er angitt i HTML.

**Bilder og lyd** legges i de tilhørende undermappene. Oppdater filstiene når filnavn endres, og behold beskrivende alternativ tekst for bildene.

## Publisering

Siden kan publiseres som et statisk nettsted, blant annet med GitHub Pages. Ved publisering fra en gren skal mappen med `index.html`, `styles.css` og `assets/` brukes som nettstedets rot.

Fra prosjektmappen kan endringer lagres og lastes opp slik:

```bash
git add index.html styles.css assets/ README.md
git commit -m "Oppdater nettsiden"
git push origin main
```

## Fotografier og kreditering

Ensemblebilder og musikerportretter: **Bella Mørk**. Fotograferingen er gjort på **Frogner hovedgård**.

Interiørbildene har egne kilder og krediteringer som må ivaretas ved videre bruk. Repositoriet gir i seg selv ingen tillatelse til å gjenbruke fotografier, innspillinger eller annet innhold.

---

<div align="center">

*En stemme. To instrumenter. Et felles uttrykk.*

</div>

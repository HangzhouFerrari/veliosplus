# Velios+ - dé open-source website voor het leren van begrippen

```
Maak je eigen begrippensets, deel ze met anderen, leer bestaande sets en combineer meerdere sets tot één - kortom alles is mogelijk. Je hebt zelfs de optie om het uiterlijk aan te passen. Dit klink allemaal heel ingewikkeld om te realiseren tot een website, maar dat valt wel mee. De JavaScript zet .vset (JSON) bestanden om in digitale flitskaarten. Deze kan je in verschillende modi leren, wat het leren gepersonaliseerd maakt.
```

## URL-structuur

```
https://plus.velios.com/set?set=naam-set
```

Velios+ laadt dan `sets/naam-set.vset`.

## .vset bestanden

`.vset` bestanden zijn versleuteld — niet leesbaar als plain JSON.
Aanmaken via de nieuwe set knop op de startpagina, dan set downloaden vanuit de ontwikkelaars-console en tot slot in de `sets/` map zetten.

## Maak sets op jouw manier

1. Open `index.html` → **Nieuwe set**
2. Vul de begrippen en definities in.
3. Formateer de begrippen en definities tot wens en voeg evt. een afbeelding toe.
4. Klik op aanmaken.

## Fallback

Als het `.vset` bestand niet op de server staat, valt de app terug
op lokaal opgeslagen sets (localStorage van `index.html`).

# ba-demos

Publieke demo's, per onderwerp, (alleen demo-code) om in Safari te bekijken: https://nrchst.github.io/ba-demos/

- Eén map per demo, met een Code ↔ Run-schakelaar.
- Alleen openbare, read-only data. Niets tekenen, niets uitgeven.
- Nooit: holdings, wallet-adressen, sleutels, API-keys of andere geheimen.

## Bitcoin

| Demo | Fase | Bijgewerkt | Volgende stap | Run | Code |
|---|---|---|---|---|---|
| Bitmap Lab | Werkt | 28 sep 2026 | nog niet bepaald | [Run](https://nrchst.github.io/ba-demos/bitmap-lab/#run) | [Code](https://nrchst.github.io/ba-demos/bitmap-lab/#code) |
| Bitmap Wereld | Werkt | 16 okt 2026 | nog niet bepaald | [Run](https://nrchst.github.io/ba-demos/bitmap-wereld/#run) | [Code](https://nrchst.github.io/ba-demos/bitmap-wereld/#code) |
| Gratis bitmap-tool | Proef | 16 okt 2026 | adres-opzoeking testen | [Run](https://nrchst.github.io/ba-demos/bitmap-tool/#run) | [Code](https://nrchst.github.io/ba-demos/bitmap-tool/#code) |
| Bulletin-ontwerp bitmap.land | Ontwerp | 16 okt 2026 | schema van bitmap.land zoeken | [Run](https://nrchst.github.io/ba-demos/bulletin-ontwerp/#run) | [Code](https://nrchst.github.io/ba-demos/bulletin-ontwerp/#code) |

Bitmap Lab haalt data rechtstreeks van `https://0rdinals.com/r/…` (die host stuurt `Access-Control-Allow-Origin: *`), dus geen proxy nodig.

Bitmap Wereld en de bitmap-tool halen alles rechtstreeks van `https://0rdinals.com/…` en `https://mempool.space/api/…` (beide `Access-Control-Allow-Origin: *`); three.js komt van jsDelivr. Geen proxy. Het bulletin is alleen een ontwerp met plaatshouders.

Nieuw onderwerp? Voeg een `## Onderwerp`-kop met een eigen tabel toe, en op index.html een `<section>` met dezelfde opbouw.

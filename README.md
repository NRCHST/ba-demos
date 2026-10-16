# ba-demos

Publieke demo's (alleen demo-code) om in Safari te bekijken: https://nrchst.github.io/ba-demos/

- Eén map per demo, met een Code ↔ Run-schakelaar.
- Alleen openbare, read-only data. Niets tekenen, niets uitgeven.
- Nooit: holdings, wallet-adressen, sleutels, API-keys of andere geheimen.

| Demo | Run | Code |
|---|---|---|
| Bitmap Lab | [Run](https://nrchst.github.io/ba-demos/bitmap-lab/#run) | [Code](https://nrchst.github.io/ba-demos/bitmap-lab/#code) |
| Bitmap Wereld | [Run](https://nrchst.github.io/ba-demos/bitmap-wereld/#run) | [Code](https://nrchst.github.io/ba-demos/bitmap-wereld/#code) |
| Gratis bitmap-tool | [Run](https://nrchst.github.io/ba-demos/bitmap-tool/#run) | [Code](https://nrchst.github.io/ba-demos/bitmap-tool/#code) |
| Bulletin-ontwerp bitmap.land | [Run](https://nrchst.github.io/ba-demos/bulletin-ontwerp/#run) | [Code](https://nrchst.github.io/ba-demos/bulletin-ontwerp/#code) |

Bitmap Lab haalt data rechtstreeks van `https://0rdinals.com/r/…` (die host stuurt `Access-Control-Allow-Origin: *`), dus geen proxy nodig.

Bitmap Wereld en de bitmap-tool halen alles rechtstreeks van `https://0rdinals.com/…` en `https://mempool.space/api/…` (beide `Access-Control-Allow-Origin: *`); three.js komt van jsDelivr. Geen proxy. Het bulletin is alleen een ontwerp met plaatshouders.

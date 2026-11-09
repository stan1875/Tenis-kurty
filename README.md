# Tenisové kurty – Praha 7 a okolí

Statická webová appka (jeden `index.html`, vanilla JS) se seznamem tenisových kurtů:
status otevřeno/zavřeno podle otevíracích hodin a sezóny, tlačítka Zavolat, Trasa (Waze + další navigace), Rezervovat ↗.

- **Kurty** – statická data (ověřeno 8. 11. 2026), oblíbené ⭐, řazení „Nejblíž“ (GPS), aktuální cena „teď X Kč/h“
- **Mapa (beta)** – Leaflet + OpenStreetMap, polohy dohledány podle adresy

## Úprava dat
Pole `COURTS` na začátku `<script>` v `index.html`.

## Deploy
Netlify → Add new site → Import from GitHub → tento repo. Build command prázdný, publish directory `.`.

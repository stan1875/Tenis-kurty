# Tenisové kurty – Praha 7 a okolí

Statická webová appka (jeden `index.html`, vanilla JS) se seznamem tenisových kurtů:
status otevřeno/zavřeno podle otevíracích hodin a sezóny, tlačítka Zavolat, Trasa (Waze + další navigace), Rezervovat ↗.

- **Kurty** – v1, statická data (ověřeno 8. 11. 2026)
- **Mapa (beta)** – Leaflet + OpenStreetMap, polohy dohledány podle adresy
- **Termíny (beta)** – rezervační systém klubu vložený do appky

## Úprava dat
Pole `COURTS` na začátku `<script>` v `index.html`.

## Deploy
Netlify → Add new site → Import from GitHub → tento repo. Build command prázdný, publish directory `.`.

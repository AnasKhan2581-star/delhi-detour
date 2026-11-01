# Delhi Detour

Route planner for Delhi on **Sunday 1 Nov 2026** that never routes you through roads the Delhi Traffic Police closed or regulated:

- **INDIA bloc rally, Ramlila Maidan (10:00–17:00 IST):** BSZ Marg (ITO–Delhi Gate), JLN Marg (Rajghat–Delhi Gate–Guru Nanak Chowk–Ajmeri Gate), Asaf Ali Rd, Minto Rd, Ranjeet Singh Flyover, DBG Rd; congestion on DDU Marg, Barakhamba Rd, KG Marg, Firoz Shah Rd, Chelmsford Rd.
- **Padyatra, Hari Nagar → Tilak Nagar (09:00–15:00 IST):** Jail Road (Lajwanti Chowk–Tilak Nagar), Lal Sai Marg.

Live: https://anaskhan2581-star.github.io/delhi-detour/

Stack: Leaflet + CARTO tiles, Valhalla (FOSSGIS) routing with `exclude_polygons`, exact road shapes pulled from OpenStreetMap (Overpass) at load, Photon search. Single static `index.html`, no keys.

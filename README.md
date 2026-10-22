# Kampala Flood Replay

**Open it: https://gavacharles.github.io/kampala-flood-replay/**

The Kampala storm of 10–11 October 2026, replayed hour by hour on a 3D map:

- **Floodwater:** modelled depth on 30 m squares along the city's valley channels.
- **Buildings with water at the door,** and **roads under water.**
- **Settings you can change and run again:** rain multiplier, silt in the channels, and paving on the hills (today or as in 1990).
- **Search** any street or landmark, paste a Google Maps or Apple Maps link, or click the map: a card gives that spot's water hour by hour, how deep in body terms, how long it stayed, the nearest road under water and the nearest channel with its maintenance priority.
- **Day and night:** the light follows the time of the replay, or stays day or night.
- **Compare with clean channels:** shows in green the land, buildings and roads that desilted channels would have kept dry in the same storm.
- **Reports:** each news report of the storm is on the map, with a live check of whether the model agrees.
- **Embed and data:** see [developers.html](https://gavacharles.github.io/kampala-flood-replay/developers.html).

The model is the Kampala drainage screening model, run with hourly satellite rain. It reproduces the flooding reported at Lubigi and Kinawataka in the early hours of 11 October, and misses Banda. The depths are model estimates, not measurements: they show the pattern of the flood, not the depth at any one door.

## Sources

- **Rain:** PERSIANN-CCS hourly, CHRS, University of California, Irvine.
- **Ground heights and channels:** Copernicus DEM GLO-30; channel network and drainage model by this study.
- **Buildings and heights:** Microsoft Global ML Building Footprints.
- **Roads, names and base map:** © OpenStreetMap contributors, via OpenFreeMap; search by Photon (Komoot).
- **3D terrain:** AWS Terrain Tiles. **Satellite base:** Esri World Imagery.
- **Reports of the storm:** NTV, Daily Monitor, KFM, allAfrica.

Analysis and tool: Gava Charles. A screening tool: indicative, not for design or insurance.

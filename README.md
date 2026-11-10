# kampala-flood-replay

Static GitHub Pages site for Kampala Flood Replay, a 3D map that replays the 10–11 October 2026 storm hour by hour from a drainage screening model, with settings the viewer can change. Live at https://gavacharles.github.io/kampala-flood-replay/

## Contents

| Path | What it is |
|---|---|
| `index.html` | The replay application |
| `developers.html` | Embedding and data notes for developers |
| `data/` | Model and map data loaded by the page: vector tiles (`buildings.pmtiles`, `channels.pmtiles`), binary grids (`*.bin`, with `.gz` copies), rain grids and series, metadata, places and extras (`*.json`), and a cell raster (`cells.png`) |
| `.nojekyll` | Serve files as they are on GitHub Pages |

There is no build step in this repository. To view locally, serve the folder (`python -m http.server`) and open http://localhost:8000.

## Sources

Rain: PERSIANN-CCS hourly (CHRS, University of California, Irvine). Terrain: Copernicus DEM GLO-30; channel network and drainage model from the Kampala drainage study. Buildings: Microsoft Global ML Building Footprints. Roads, names and base map: © OpenStreetMap contributors via OpenFreeMap; search by Photon (Komoot). 3D terrain: AWS Terrain Tiles. Satellite base: Esri World Imagery. Storm reports: NTV, Daily Monitor, KFM, allAfrica.

Analysis and tool: Gava Charles. A screening tool: indicative, not for design or insurance.

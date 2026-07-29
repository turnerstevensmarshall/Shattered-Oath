# The Shattered Oath - World Map

Interactive map of the Shattered Oath campaign world, published from the
Obsidian vault. Pins show settlements (Capital / City / Town).

**Live map:** https://turnerstevensmarshall.github.io/Shattered-Oath/

## How it updates

- `index.html` - Leaflet map (image overlay, `L.CRS.Simple`).
- `markers.json` - generated settlement pins (name + type only).
- `WorldMap.png` - the world map image.

`markers.json` and `WorldMap.png` are regenerated from the vault by
`export_web_map.py` and pushed here. In Discord (GM channel) run
`!publishmap` to refresh the live map.

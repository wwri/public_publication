# FSIM NPS places — Interactive U.S. map

Interactive leaflet map for **wildfire hazard and significance** of cultural-resource places across the United States (structures and related properties intersecting FSIM burn probability surfaces), as described in the associated *Scientific Reports* manuscript.

## Files

### [`us_interactive_map.html`](us_interactive_map.html)

National point map (~full U.S. coverage) with layer toggles:

- **Burn hazard** (Low / Moderate / High)
- **Level of significance** (International, National, State, Local)
- **Property type** (NRHP category)

Popups summarize place name, state, hazard, significance, and property type. Marker size scales mildly with zoom. The overlay title uses responsive typography so the heading fits cleanly on laptops and phones.

**Map defaults:** CartoDB Positron basemap; view centered ~39°N, 96°W at zoom 4.

## Viewing online

If [GitHub Pages](https://docs.github.com/en/pages) is enabled for the **`public_publication`** repository **from the `main` branch (site root)** the map resolves at:

[`https://wri-science.github.io/public_publication/publication_htmls/fsim_nps_places/us_interactive_map.html`](https://wri-science.github.io/public_publication/publication_htmls/fsim_nps_places/us_interactive_map.html)

(If your org uses different Pages settings—e.g. `docs/` folder—adjust the `/publication_htmls/` segment accordingly.)

## Related repository

Authoring code and GIS inputs: [`WRI-Science/papers`](https://github.com/WRI-Science/papers) — `fsim_nps_places/scripts for publication/05-interactive-us-map.R`

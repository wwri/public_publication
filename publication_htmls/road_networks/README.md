# Road Networks - Evacuation Route Analysis

Interactive HTML visualizations for the Networks Paper evacuation route analysis.

## Files

### us_bivariate_map.html
National bivariate choropleth map showing evacuation risk for U.S. Census-designated places.

**Combines:**
- Egress capacity (number of boundary-crossing roads)
- Burn probability (wildfire likelihood)

**Color scheme:** 4x4 bivariate grid
- Dark purple/magenta = Highest risk (few exits + high burn probability)
- Light colors = Lower risk

**Map view:**
- Centered at 39°N, 96°W (US geographic center)
- Zoom level 4 - shows continental US with ocean edges and partial Alaska

**Data coverage:** ~30,000 Census-designated places across all 50 states + DC

**Generated:** February 2026

## Related Repository

Analysis scripts: https://github.com/wwri/papers/tree/main/roads/roads_processing_scripts

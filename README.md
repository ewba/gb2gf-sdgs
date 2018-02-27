# Imgur: A day in the life (everywhere)
This is a small Leaflet project aggregating daily stories from around the world.

**LIVE SITE: https://lynxlynx.info/aditl/**

## Tech
- Leaflet 1.3.1
- a modified version of [leaflet-control-window](https://github.com/mapshakers/leaflet-control-window)
  - relevant patches sent upstream, the rest visible [here](leaflet-control-window.diff)
- leaflet-markercluster
- leaflet-control-geocoder
- the standard fetch() and Promise polyfill from polyfill.io
- php to store the submission results (not shared for increased security)

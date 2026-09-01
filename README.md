# Leaflet vs MapLibre vs OpenLayers — Comparisons

A collection of minimal comparisons between **Leaflet 1.9.4**, **MapLibre GL JS 5.24.0**, and **OpenLayers 10.9.0**.

**Live demo:** https://mapdraw.github.io/leaflet-vs-maplibre-vs-openlayers

## Comparisons

### Large GeoJSON (100MB — USA zip codes)

| Demo                                                        | Renderer |
| ----------------------------------------------------------- | -------- |
| [Leaflet 1.9.4 (SVG)](geojson-large/leaflet-svg.html)       | SVG      |
| [Leaflet 1.9.4 (Canvas)](geojson-large/leaflet-canvas.html) | Canvas   |
| [MapLibre GL JS 5.24.0](geojson-large/maplibre.html)        | WebGL    |
| [OpenLayers 10.9.0](geojson-large/openlayers.html)          | Canvas   |

Every demo loads the same dataset at the same view, in the same colors. The two Leaflet pages use the same code, with `preferCanvas` switching Leaflet between its SVG and canvas renderer.

Dataset: [usa_zip_codes_geo_100m.json](https://github.com/ndrezn/zip-code-geojson) by ndrezn

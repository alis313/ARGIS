# AR-Links (installable web app)

## Update on GitHub
Upload ALL files in this folder to your repository (same names replace the old ones). Delete `lib/proj4.js` and `lib/dxf-parser.js` from the repository; they are no longer used. Then close the app completely and open it twice.

## Supported formats (only formats that state their own coordinate system)
- GeoJSON (WGS 84)
- KML (WGS 84)
- Shapefile as a .zip that contains the .prj file (any CRS, converted automatically)

Not supported: DXF, GPKG, TIFF and anything else.
A Shapefile ZIP without .prj is rejected, as is a GeoJSON that declares another CRS.

## How to use
Menu (☰) → Projects / Layers / Import layer. Project → Areas → Layers. Tap a layer to change name, color, line width and depth; use its checkbox to show or hide it.
MAP shows the plan on OpenStreetMap; AR shows the camera overlay.

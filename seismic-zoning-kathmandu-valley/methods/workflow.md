## Workflow (QGIS)
1) Load DMG seismic zoning polygons and fault/thrust line layers.
2) Set project CRS to WGS 84 (EPSG:4326) and standardize all layers to a single CRS.
3) Clean geometry (fix invalid geometries) and simplify symbology for clarity.
4) Fault/thrust emphasis:
   - style by type (fault vs thrust / major structures)
   - label major structures where appropriate
5) Sensor siting support (preliminary):
   - create buffers around fault/thrust lines or zones of interest
   - overlay with valley settlements/road access layers
6) Compose print layout and export to PDF.

### QGIS tools/plugins (suitable)
- **Georeferencer (GDAL)** (if any scanned/reference maps were georeferenced)
- **QuickMapServices** (optional basemap/context during drafting)
- **Topology Checker** (to validate digitized/edited linework)
- **Processing Toolbox (GDAL/SAGA)** for clip, dissolve, buffer, fix geometries
- **InaSAFE (optional)** if you later add hazard/exposure layers for communication

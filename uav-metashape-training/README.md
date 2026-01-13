# UAV Mapping
Photogrammetry products created during UAV mapping training using **Agisoft Metashape** 

## Included outputs
- Orthomosaic overview (PNG): `maps/01_orthomosaic_overview.png`
- DEM quicklook (PNG): `maps/02_dem_quicklook.png`
- DEM + contours (PNG): `maps/03_dem_with_contours.png`
- Contours (SHP): `data/processed/contours.shp`
- Sample raw photo (downsampled): `quicklook`

# Metadata

**UAV:** DJI Mavic 2 Pro  
**Software:** Agisoft Metashape (processing), QGIS (visualization/export)  
**GCPs:** 5 points

## Notes
- Training dataset; accuracy depends on GCP distribution and measurement quality.
- Contours are derived from DEM; interpret carefully in vegetated/occluded areas.
- Raw UAV imagery, dense clouds, and full Metashape project files are large and therefore not stored here. They can be shared upon request Downsized sample files are provided for reference.
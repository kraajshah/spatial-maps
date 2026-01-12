# Data notes (project coordinates)

This folder contains a **small sample** of survey-derived point data used to produce the accompanying map.  
The original survey was collected using a **Total Station**.

## Coordinate reference system (CRS)
- **CRS / Projection:** Nepal National Grid  
- Coordinates are provided as **Easting (E)** and **Northing (N)** in **meters**.
- The dataset is stored in **project coordinates** consistent with the map/CAD project settings.

## What is included
- `sample_points_project_crs.csv` (truncated sample only)

Recommended columns:
- `point_id`
- `easting_m`
- `northing_m`
- `elev_m`
- `feature` 
- `note`

## What is not included
- Full raw survey datasets and control points are not shared publicly.
- Sensitive identifiers may be removed or generalized.

## Privacy & sharing
This repository is intended for **academic demonstration**. Only a limited subset of points is shared to illustrate the workflow from field survey → GIS/CAD → map output.




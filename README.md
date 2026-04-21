# GIS Data Standardization Tool (ArcPy)

## Project Overview

This project presents an automated GIS data standardization pipeline built using ArcPy in ArcGIS Pro. 

The workflow processes multi-source geospatial data, including CSV, raster (ECW/DEM), and vector layers, and transforms them into analysis-ready datasets through coordinate system standardization, raster mosaicking, and spatial clipping.

The pipeline is implemented both as a Python script and as an ArcGIS Script Tool, enabling reproducible and user-friendly geospatial data processing.

---

## Project Workflow

- CSV → Point feature conversion
- ECW raster mosaicking
- Extent polygon generation (no 3D Analyst dependency)
- Projection to NAD83 UTM Zone 10N
- DEM clipping using spatial extent
- Vector clipping automation
- Logging + error handling
- ArcGIS Script Tool integration (UI-based execution)

---

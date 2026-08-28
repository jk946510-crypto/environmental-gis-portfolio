### 🛠️ Technical Specifications & Methodology

* **Software & Tools:** QGIS 3.x, GDAL/OGR, Open-source Geospatial Web Services
* **Coordinate Reference System (CRS):** `EPSG:3005` (NAD83 / BC Albers) – projected for accurate area and distance preservation across British Columbia.
* **Data Ingestion & Provenance:** 
  * *Wildfire Perimeters:* Streamed directly from **BC Map Services / DataBC Web Services** via live geospatial endpoints (ArcGIS REST / WMS), sourcing historical fire perimeter layers across the 2022, 2023, and 2024 fire seasons.
  * *Basemap Imagery:* High-resolution Google Satellite imagery service.
* **Cartographic & Spatial Workflows:**
  * Ingestion and filtering of live spatial layers across multi-year temporal attributes.
  * Multi-layer vector polygon overlay and layer rendering calibration.
  * Hierarchical year-over-year categorized styling with calibrated opacity for topographic visibility.
  * Publication layout design with dynamic metric scale bars, custom directional indicators, and formal data provenance attribution (300 DPI export).

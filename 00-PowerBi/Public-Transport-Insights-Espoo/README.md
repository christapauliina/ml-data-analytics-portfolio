# Public Transport Insights – Espoo

Interactive Power BI dashboard analyzing bus boarding trends in Espoo, Finland (2022–2024).  

<img width="435" height="761" alt="powerbi" src="https://github.com/user-attachments/assets/91852ea6-2cbc-4569-82b3-f24ef6090063" />

---

## Overview
The dashboard covers the full data lifecycle — from raw open data to interactive reporting.  
Data was sourced from HRI (Helsinki Region Infoshare) and processed using QGIS and Power Query.

**Key features:**
- Automated Power Query (M) transformations — refresh-ready when new data is added
- GIS processing with QGIS to extract stop coordinates from Geopackage and GeoJSON files
- Metro and light rail data filtered out to ensure consistent bus-only comparison across years
- Interactive year slicers (2022–2023–2024)
- Top 3 busiest stops with trend tracking
- DAX-powered tooltip views with Top 10 stop rankings
- 3D column map for spatial boarding visualization

**Repository structure:**
- `/data` — source data files for reference
- `/media` — screenshots and screen recording of the dashboard

---
## Tech Stack
Power BI (DAX, Power Query) · QGIS · HRI Open Data
---



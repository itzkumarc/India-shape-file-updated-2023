# 🗺️ India Shapefiles – 2023 Update

This repository provides updated and accurate shapefiles for **India's state and district boundaries** as of **2023**. These files are ideal for use in:

- Geographic Information Systems (GIS)
- Spatial analysis and research
- Data visualization and cartography
- Mapping projects at national, state, or district levels

## 🧭 Features

- Based on the latest administrative boundaries (as of 2023)
- High-resolution geometries for detailed analysis
- Compatible with **QGIS**, **ArcGIS**, **Python (GeoPandas)**, and **R (sf)**

## 🔧 Usage

### Python (GeoPandas)

```python
import geopandas as gpd

# Load state shapefile
states = gpd.read_file("India_State_Shapefile/India_State_Boundary.shp")

# Plot states
states.plot()
```

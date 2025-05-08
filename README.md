# spatial-analysis-with-geopandas
A spatial analysis using GeoPandas to calculate National Highway road density per district.

## Analyzing National Highway Road Density per District in Karnataka

This project calculates and visualizes the road density of National Highways in each district of Karnataka using GeoPandas and a GeoPackage file.

## 📂 Data

- **Karnataka_district** – Administrative boundaries of districts.
- **Karnataka_major_roads** – Road network including National Highways.

## 📊 Output

### 1. National Highways Overlay on District Map

This map shows the district boundaries with National Highways overlaid:

![Highways Overlay Map](images/highways_overlay_map.png)

---

### 2. National Highway Road Density per District

Choropleth map showing road density (km per sq. km) of National Highways in each district:

![Road Density Choropleth](images/road_density_choropleth.png)

---

## 📌 Tools Used

- Python
- GeoPandas
- Matplotlib
- Fiona
- JupyterLab


## 📁 Structure

```
├── data/
│   └── karnataka.gpkg
├── images/
│   ├── highways_overlay_map.png
│   └── road_density_choropleth.png
├── analysis.ipynb
└── README.md
```
=======
>>>>>>> 65b224ce3fb9132ec328339f68727b370979c9f1

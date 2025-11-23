# Eaton and Palisades False Color Imagery

### Author: Richard Montes Lemus 

## About

**Purpose:** This notebook uses false color imagery to visualize the aftermath of the Eaton and Palisades fires in Southern California Feb 23, 2025. 

**Highlights:**
- Plotting RGB true color map 
- Plotting False-color image map (SWIR‑NIR‑Red)
- Plotting False-color image map (SWIR‑NIR‑Red) with Eaton and Palisades parameters

## File Structure 
```
├── data
│   ├── Eaton_Perimeter_20250121
│   │   ├── Eaton_Perimeter_20250121.cpg
│   │   ├── Eaton_Perimeter_20250121.dbf
│   │   ├── Eaton_Perimeter_20250121.prj
│   │   ├── Eaton_Perimeter_20250121.shp
│   │   └── Eaton_Perimeter_20250121.shx
│   ├── landsat8-2025-02-23-palisades-eaton.nc
│   └── Palisades_Perimeter_20250121
│       ├── Palisades_Perimeter_20250121.cpg
│       ├── Palisades_Perimeter_20250121.dbf
│       ├── Palisades_Perimeter_20250121.prj
│       ├── Palisades_Perimeter_20250121.shp
│       └── Palisades_Perimeter_20250121.shx
├── hwk4-task2-false-color-MONTESLEMUS.ipynb
└── README.md

```
## Output
**File:**
- `hwk4-task2-false-color-MONTESLEMUS.ipynb`
  
**Description:**
Jupyter notebook containing code for producing false color imagery map with Eaton and Palisades fire perimeters.

## Data
### Fire Perimeter Data
**Files:**  
- `Eaton_Perimeter_20250121.shp`  
- `Palisades_Perimeter_20250121.shp`  

**Description:**  
Dissolved perimeter boundaries for the Eaton and Palisades fires in Los Angeles County.

**Access:**  
[ArcGIS Hub](https://hub.arcgis.com/datasets/lacounty::palisades-and-eaton-dissolved-fire-perimeters-2025/explore?layer=0&location=34.133156%2C-118.337781%2C10.75)

**Required Tools:**  
- Python: `geopandas`  
- Conda environment: `eds220`  

---

### Landsat 8 Remote Sensing Data
**File:**  
- `landsat8-2025-02-23-palisades-eaton.nc`  

**Description:**  
Atmospherically corrected surface reflectance and surface temperature imagery from Landsat 8.

**Access:**  
[Microsoft Planetary Computer](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2)

**Required Tools:**  
- Python: `xarray`, `netCDF4`  
- Conda environment: `eds220`

---

## References: 

[1] ArcGIS Online. Palisades and Eaton Dissolved Fire Perimeters as of 20250121 [Feature service]. Available: https://services.arcgis.com/RmCCgQtiZLDCtblq/arcgis/rest/services/Palisades_and_Eaton_Dissolved_Fire_Perimeters_as_of_20250121/FeatureServer/0
. [Accessed Nov 22, 2025].

[2] U.S. Geological Survery. _Landsat Collection 2 Level-2 Surface Reflectance (Microsoft Planetary Computer Version)_ [data file]. Available: https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2. [Accessed Nov 22, 2025]


# NDVI-Based Drought Assessment of Kasba Union, Nachole (2017–2025)

![NDVI Changes](NDVI.jpeg)

## Overview

This repository presents a **multi-temporal vegetation and drought analysis** of **Kasba Union, Nachole Upazila, Chapainawabganj District, Bangladesh** using **remote sensing and GIS techniques**.

The analysis uses **Landsat 8 satellite imagery** to calculate the **Normalized Difference Vegetation Index (NDVI)** for multiple years (2017, 2019, 2021, 2023, and 2025). These NDVI values were further used to derive the **Vegetation Condition Index (VCI)** to assess **vegetation health and drought conditions** over time.

This study demonstrates how **satellite data and geospatial analysis** can be used to monitor environmental changes and support **drought assessment and climate resilience planning**.

---

## Study Area

The study focuses on **Kasba Union**, located in **Nachole Upazila, Chapainawabganj District, Bangladesh**.

The region is known for its **agricultural dependency and susceptibility to drought**, making vegetation monitoring important for understanding environmental stress and agricultural sustainability.

---

## NDVI (Normalized Difference Vegetation Index)

NDVI is a widely used vegetation index that measures **vegetation greenness and health** using satellite imagery.

It is calculated using the formula:

```
NDVI = (NIR - Red) / (NIR + Red)
```

Where:

- **NIR** = Near Infrared Band  
- **Red** = Red Band

NDVI values range from **-1 to +1**:

| NDVI Value | Interpretation |
|-------------|---------------|
| < 0 | Water bodies |
| 0 – 0.2 | Bare soil / sparse vegetation |
| 0.2 – 0.5 | Moderate vegetation |
| > 0.5 | Dense vegetation |

Higher NDVI values indicate **healthier and denser vegetation**.

---

## Vegetation Condition Index (VCI)

To evaluate drought conditions, **Vegetation Condition Index (VCI)** was derived from NDVI values.

VCI measures **vegetation stress relative to historical NDVI conditions**, helping identify areas experiencing drought.

Lower VCI values indicate **vegetation stress or drought conditions**, while higher values represent **healthy vegetation conditions**.

---

## Data Source

Satellite data used in this analysis:

- **Satellite:** Landsat 8
- **Sensor:** OLI/TIRS
- **Years Analyzed:**
  - 2017
  - 2019
  - 2021
  - 2023
  - 2025

The data were obtained from **USGS EarthExplorer**.

---

## Methodology

The drought assessment followed these major steps:

1. Acquisition of Landsat 8 satellite imagery
2. Preprocessing and preparation of raster datasets
3. Extraction of spectral bands (Red and NIR)
4. Calculation of **NDVI**
5. Derivation of **Vegetation Condition Index (VCI)**
6. Spatial analysis and visualization of vegetation patterns
7. Comparison of NDVI values across multiple years

The analysis allowed identification of **temporal vegetation changes and drought conditions** within the study area.

---

## Tools & Software

The analysis and map preparation were conducted using:

- **ArcMap (ArcGIS Desktop)**
- Remote sensing raster processing tools
- GIS spatial analysis tools
- Cartographic visualization techniques

---

## Key Insights

The multi-temporal NDVI analysis reveals:

- Spatial variations in vegetation health across the study area
- Temporal fluctuations in vegetation conditions between 2017–2025
- Periods of **reduced vegetation health indicating potential drought stress**
- The usefulness of remote sensing for **environmental monitoring and drought assessment**

---

## Repository Contents

```
NDVI
│
├── NDVI.jpeg      # Multi-temporal NDVI maps (2017–2025)
├── README.md      # Project documentation
└── LICENSE        # MIT License
```

---

## Author

**Md. Habibullah Masbah**  
Undergraduate Student  
ID: 2107046
Department of Urban & Regional Planning  
Rajshahi University of Engineering & Technology (RUET), Bangladesh

---

## License

This project is licensed under the **MIT License**.

See the **LICENSE** file for more details.

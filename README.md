# SAVI Map – Roorkee (Kharif 2024)

A web map visualizing the **Soil Adjusted Vegetation Index (SAVI)** over crop fields around **Roorkee**, Uttarakhand, during the **Kharif season (August 2024)**.

🔗 **Live Map**: [https://goswamishreyas.github.io/SAVI_map_Roorkee/](https://goswamishreyas.github.io/SAVI_map_Roorkee/)

---

## What is SAVI?

**SAVI (Soil Adjusted Vegetation Index)** is a spectral vegetation index used to monitor crop health and vegetation cover, especially in regions with exposed soil. It’s calculated as:

\[
\text{SAVI} = \frac{(NIR - Red)}{(NIR + Red + L)} \times (1 + L)
\]

Where:
- **NIR** = Near-Infrared reflectance  
- **Red** = Red reflectance  
- **L** = Soil brightness correction factor (typically 0.5)

Unlike NDVI, SAVI is particularly useful for early crop stages or sparsely vegetated areas where soil influence is significant.

---

## Crops Around Roorkee – August (Kharif Season)

During the **Kharif** (monsoon) season, fields around Roorkee are typically planted with:
- **Paddy (rice)** 
- **Sugarcane**
- **Pulses** (e.g., urad, moong)

This map helps visualize crop vigor and soil-adjusted greenness during this critical growing season using SAVI data.

---

## Features

- 🌍 Interactive Leaflet map  
- 🖼️ SAVI raster layer rendered with color-coded legends  
- 📌 Pixel value popup on click  
- 🛰️ Base layers: OSM and Google Satellite

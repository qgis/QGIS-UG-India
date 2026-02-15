
---
type: "page"
title: "Comparison of Watershed Delineation Using SRTM and CartoDEM in QSWAT+: A Case Study of the Mula River Basin"
subtitle: "Local success stories"
draft: false
sidebar: true
thumbnail: "./img/watershed_delineation_5.webp"

---

{{< content-start >}}

# Comparison of Watershed Delineation Using SRTM and CartoDEM in QSWAT+: A Case Study of the Mula River Basin

Accurate watershed delineation and stream networks are essential for drainage planning, water resource management and flood risk assessment. The quality of the stream network and watershed  depends heavily on the quality of the input elevation data. This case study compares two elevation datasets (i) RADAR based SRTM DEM and (ii) stereo image based CartoDEM to determine which can produce higher spatial fidelity for practical applications.

## Study Area

The Mula River watershed is located  in  Mulshi and Haveli Talukas of Pune District. The area includes the Mulshi Reservoir upstream and a mix of rural and urban land cover, providing a good test for stream generation accuracy across different terrain types (Fig. 1).

<p align="center">
  <img src="../img/watershed_delineation_1.webp" alt="Location of Watershed">
</p>
<p align="center"><em>Fig. 1. Satellite view of the Mula River watershed. The study area spans from Mulshi Reservoir in the west to urban Pune in the east.</em></p>

## Approach

QGIS and the QSWAT+ plugin were used to generate stream networks and delineate sub-basins from two elevation sources:


Both datasets were processed using identical parameters (channel threshold: 50 acres, stream threshold: 2,500 acres). A barrage on the Mula River served as the outlet point. Outputs were compared against each other and validated against India-WRIS stream data.

<p align="center">
  <img src="../img/watershed_delineation_2.webp" alt="Delineated Sub-basins using QSWAT+ from CartoDEM Data">
</p>
<p align="center"><em>Fig. 2. Sub-basins delineated using SRTM data. There were 35 sub-basins generated from the 30-metre resolution SRTM elevation model.</em></p>

<p align="center">
  <img src="../img/watershed_delineation_3.webp" alt="Delineated Sub-basins using QSWAT+ from SRTM Data">
</p>
<p align="center"><em>Fig. 3. Sub-basins delineated using CartoDEM data. There were 15 sub-basins generated from the 10-metre resolution CartoDEM. Note the different sub-basin configuration due to finer terrain detail.</em></p>

## Findings

Higher-order streams aligned well between both datasets (Fig. 2 & 3). Differences appeared in lower-order tributaries, where CartoDEM captured finer drainage patterns.

Urban areas showed the most significant variation. CartoDEM streams aligned more closely with actual drainage on the ground, reflecting both higher resolution and more recent acquisition (Fig. 4).

<p align="center">
  <img src="../img/watershed_delineation_4.webp" alt="Comparison of Outputs at High-scale">
</p>
<p align="center"><em>Fig. 4. Comparison in urban areas. Blue/cyan: SRTM outputs. Green/yellow: CartoDEM outputs. The higher-resolution CartoDEM better captures drainage patterns in built-up areas.</em></p>

**India-WRIS streams appear to use a lower drainage initiation threshold, mapping many streams that do not exist on the ground (Fig. 5).**

<p align="center">
  <img src="../img/watershed_delineation_5.webp" alt="Comparison of Outputs with Streams from India-WRIS">
</p>
<p align="center"><em>Fig. 5. Comparison with India-WRIS stream data. India-WRIS streams (coloured by stream order) show significantly more drainage lines than either SRTM or CartoDEM outputs, many of which do not correspond to actual streams.</em></p>

CartoDEM produces more accurate results than SRTM for this watershed, particularly in urban areas.

## Why QGIS?

QGIS and QSWAT+ handled the complete workflow from raw elevation data to attributed sub-basin polygons. The open-source toolchain made it possible to run the same analysis twice with different inputs and compare outputs systematically, without licensing constraints.

## Resources

  QSWAT+ documentation: (https://swatplus.gitbook.io/docs/user/qswat+)
  SRTM data: (https://earthexplorer.usgs.gov) 
  India-WRIS: (https://indiawris.gov.in/wris/#/geoSpatialData) 
  CartoDEM: Available from ISRO/NRSC

## Author

Chinmay Shaligram is the Co-Founder of Terra Helix (https://terrahelix.io/), a geospatial consultancy based in Pune, India.

---

**Note**

*This case study was developed using entirely open-source geospatial tools and is intended to support learning, replication, and adaptation by the wider QGIS and disaster management communities.*

*Some datasets were derived from publicly available sources, while others were adapted or simulated for demonstration purposes. The results illustrate QGIS-based workflows and should not be used directly for operational disaster response without validation using authoritative local data.*

{{< content-end >}}

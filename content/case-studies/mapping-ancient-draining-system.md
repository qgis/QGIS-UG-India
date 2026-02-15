---
type: "page"
title: "Digital Documentation of an Ancient Drainage System in Betalbatim, Goa using QGIS and QField"
subtitle: "Regional scale study"
draft: false
sidebar: true
thumbnail: "./img/drainage_system_1.webp"

---

{{< content-start >}}

# Digital Documentation of an Ancient Drainage System in Betalbatim, Goa using QGIS and QField

This case study describes how **QGIS and QField** were used to identify, digitize, validate, and document a village-scale ancient drainage and water management system in Betalbatim, a coastal village in Goa. The project demonstrates the effectiveness of an **open-source GIS workflow** in uncovering hidden infrastructure assets and enabling evidence-based community governance.

## Project Background and Objectives

Betalbatim village has a long history of indigenous water management practices, including a network of ancient drainage channels, village ponds, and agricultural fields that together functioned as a **rainwater harvesting and flood mitigation system**. These systems are believed to have existed for several centuries.

<p align="center">
  <img src="../img/drainage_system_1.webp" alt="Well-preserved Section">
</p>
<p align="center"><em>Fig. 1. Well-preserved section of Betalbatim's centuries-old traditional drainage system.</em></p>

However, the last officially documented survey of the village exists only in a cadastral plan prepared in 1972. Over decades of rapid coastal development and tourism-driven urbanization, the visibility and institutional memory of this drainage system diminished, even though many channels continued to exist physically on the ground. As a result, several drains were partially blocked, encroached upon, submerged, or altered without recognition of their hydrological importance.

<p align="center">
  <img src="../img/drainage_system_2.webp" alt="Drainage Channel">
</p>
<p align="center"><em>Fig. 2. Drainage channel hidden by dense foliage, with mature tree growth inside the channel revealing decades of neglect.</em></p>

The project aimed to achieve the following objectives:

  Digitally document the drainage network using QGIS
  Validate its existence and condition through systematic field surveys using QField
  Understand the spatial relationships between drains, ponds, agricultural fields, and village topography
  Create a reliable geospatial dataset to support village-level planning, restoration, and governance

## Methodology

### Data Acquisition

SpatialCraft collected the historical Village Cadastral Plan from 1972. High-resolution aerial imagery was acquired through drone mapping along with a set of well-distributed ground control points throughout the village to provide an accurate and up-to-date spatial reference of the village landscape.

### Geo-referencing and Digitization in QGIS

The historical village plans were geo-referenced in QGIS using the high-resolution aerial imagery as a base. Once spatially aligned, the entire traditional drainage network was digitized as vector layers. This included primary and secondary drainage channels, connectivity between segments, and their spatial relationships with ponds, fields, and low-lying areas.

<p align="center">
  <img src="../img/drainage_system_3.webp" alt="Digitized Drainage Network">
</p>
<p align="center"><em>Fig. 4. Digitized drainage network in QGIS.</em></p>

### Field Validation Using QField

To ground-truth the digitized drainage network, SpatialCraft deployed QField for mobile field surveys. The QGIS project was prepared and synchronized for mobile use, allowing community volunteers to navigate directly to digitized drainage segments in the field.

<p align="center">
  <img src="../img/drainage_system_4.webp" alt="Geotagging and Field Data">
</p>
<p align="center"><em>Fig. 4. Geotagging and field data collection using QField at a heritage man-made pond functioning as a rainwater collection and recharge point within the drainage network.</em></p>

QField served two key purposes:
  Navigation to specific drainage features using mobile GIS
  Documentation of on-ground conditions through geotagged photographs and observations
  
This approach enabled efficient ground truthing of features that were partially visible, ambiguous, submerged, or obstructed.

### Data Integration and Analysis in QGIS

All field-collected data from QField was synchronized back into the QGIS desktop environment. Geotagged photographs, field notes, and updated attributes were analyzed alongside the digitized drainage network.
The analysis revealed the system’s complexity and intentional design, including:
  Interconnected drainage paths guiding water toward village ponds
  Integration with agricultural fields for controlled water dispersal
  Terrain-aware routing optimized for monsoon rainfall

## Outputs and Maps

The project resulted in:

  A validated GIS database of Betalbatim’s traditional drainage and water resources
  A comprehensive village-level water resource and drainage map
  A WebGIS map enabling interactive exploration of the drainage network
  Printed map layouts generated using Print Layout tool for use by the Village Panchayat
  
Additionally, areas with blocked drains, submerged sections, and locations where mature trees had grown within drainage paths were clearly identified and mapped.

<p align="center">
  <img src="../img/drainage_system_5.webp" alt="Interactive WebGIS Map">
</p>
<p align="center"><em>Fig. 5. Interactive WebGIS map with geotagged photo pop-ups and attribute reports, supporting evidence-based decision-making for the local governing body.</em></p>

### Outcomes and Impact

This QGIS and QField-based workflow transformed fragmented historical records and local knowledge into a spatially accurate, field-validated dataset. For the first time, the Village Panchayat and community stakeholders gained a clear visual and analytical understanding of the village’s traditional water management infrastructure.

These outputs now enable:

  Evidence-based planning for drainage revival and maintenance
  Identification of priority intervention zones
  Integration of heritage infrastructure considerations into development approvals
  Strategic planning for flood management and rainwater harvesting over the next planning cycle
  
The project also strengthened community engagement by reconnecting residents with forgotten infrastructure created by earlier generations.

<p align="center">
  <img src="../img/drainage_system_6.webp" alt="Community-led Effort">
</p>
<p align="center"><em>Fig. 6. Community-led effort bringing together youth volunteers, village elders, and elected representatives for a shared conservation initiative.</em></p>

## Conclusion

This case study demonstrates how QGIS and QField can be used effectively together to integrate historical data, modern aerial imagery, and field validation into a single, coherent geospatial workflow. Open-source GIS tools played a critical role in documenting previously invisible or undervalued infrastructure and translating them into actionable knowledge for community governance.

The approach can be replicated in other villages facing similar challenges with undocumented drainage systems, water resources, and heritage infrastructure under development pressure.

## Author

Malcolm Afonso is the Founder of SpatialCraft, a Goa-based geospatial technology company. He actively works with QGIS and open-source geospatial tools, focusing on GIS consulting, drone mapping, precision surveying, WebGIS, and community-led spatial planning for governance and sustainability. His company, SpatialCraft, extensively uses open-source geospatial technologies, particularly QGIS and QField, to deliver accurate, field-validated spatial intelligence for decision-making.


---

**Note**

*This case study was developed using entirely open-source geospatial tools and is intended to support learning, replication, and adaptation by the wider QGIS and disaster management communities.*

*Some datasets were derived from publicly available sources, while others were adapted or simulated for demonstration purposes. The results illustrate QGIS-based workflows and should not be used directly for operational disaster response without validation using authoritative local data.*

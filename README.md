# Forest-Cover-Change-Analysis-Tool
Monitoring Land Use Transitions for Sustainable Forest Management


## Table of Contents
- [Introduction](#Introduction)
- [Project Goals](#project_goals)
- [Data and Methods](#Data-and-methods).
- [Area Of Interest](#area-of-interest).
- [Project Workflow](#Project-Workflow)
- [Thematic Layer](#thematic-layer)
- [Correlation between LST and NDVI](#Correlation-between-LST-and-NDVI)
- [Land Use Land Cover](#land-use-land-cover)
- [Results](#results)

## Introduction
Forests are vital for maintaining ecological balance, providing habitat for wildlife, and serving as significant carbon sinks to mitigate climate change. However, they face various threats such as deforestation, degradation, and urban expansion. Understanding the changes in forest cover over time is essential for policymakers, conservationists, and researchers to make informed decisions that support sustainable forest management and conservation efforts.

The Forest Cover Change Analysis Tool is designed to facilitate this analysis by processing multi-temporal satellite raster data, identifying land use and land cover (LULC) transitions, and calculating the affected areas in hectares. This tool outputs both GeoTIFF files that visualize changes and Excel summaries that detail transition statistics.

## Project Goals
*** 1 Track and quantify forest cover loss and gain over specified time periods.<br>
Provide actionable data to assist in forest conservation and management strategies.<br>
Support environmental reporting and policymaking with reliable LULC transition metrics.



## Data and Methods
### Data Sources
Landsat 5 TM and Landsat 8 OLI/TIRS imagery for LST calculation.
Shapefiles and TIF files for spatial analysis.
### Methods Used
LST Calculation: Uses DN (Digital Numbers) to Radiance conversion and Brightness Temperature calculation.
NDVI Calculation: Utilizes Red and NIR bands to calculate vegetation index.
Regression Analysis: Compares LST values across different years.
GIS Mapping: Creates maps showing temperature variations.
## Area Of Interest
![Project Area](Images/Area.png)


## Project Workflow

![Workflow](Images/Workflow.png)



## Thematic Layer
<img src="Images/NDVI1999.png" alt="Sample Screenshot" width="500">
<img src="Images/NDVI2009.png" alt="Sample Screenshot" width="500">
<img src="Images/NDVI2019.png" alt="Sample Screenshot" width="500">

<img src="Images/LST1999.png" alt="Sample Screenshot" width="500">
<img src="Images/LST2009.png" alt="Sample Screenshot" width="500">
<img src="Images/LST2019.png" alt="Sample Screenshot" width="500">

## Correlation between LST and NDVI
<img src="Images/LST vs NDVI 1999.png" alt="Sample Screenshot" width="500">
<img src="Images/LST vs NDVI 2009.png" alt="Sample Screenshot" width="500">
<img src="Images/LST vs NDVI 1999.png" alt="Sample Screenshot" width="500">

## Land Use Land Cover
<img src="Images/LULC1999.png" alt="Sample Screenshot" width="500">
<img src="Images/LULC2009.png" alt="Sample Screenshot" width="500">
<img src="Images/LULC2019.png" alt="Sample Screenshot" width="500">


## Result
This study provides insights into the effects of urbanization on LST in Nagpur over two decades. Below are some key findings:

### Key Findings
**NDVI vs. LST Analysis**: NDVI values have shown a decline in green vegetation, while LST has increased, correlating with the urban expansion in Nagpur.<br>
**Regression Analysis**: The correlation between NDVI and LST highlights the impact of vegetation loss on urban temperatures.




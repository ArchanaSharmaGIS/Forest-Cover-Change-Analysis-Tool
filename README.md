# Forest-Cover-Change-Analysis-Tool
Monitoring Land Use Transitions for Sustainable Forest Management


## Table of Contents
- [Introduction](#Introduction)
- [Project Goals](#project_goals)
- [Theory and Background](#theory).
- [Methodology](#methodology).
- [Project Workflow](#Project-Workflow)
- [Thematic Layer](#thematic-layer)
- [Correlation between LST and NDVI](#Correlation-between-LST-and-NDVI)
- [Land Use Land Cover](#land-use-land-cover)
- [Results](#results)

## Introduction
Forests are vital for maintaining ecological balance, providing habitat for wildlife, and serving as significant carbon sinks to mitigate climate change. However, they face various threats such as deforestation, degradation, and urban expansion. Understanding the changes in forest cover over time is essential for policymakers, conservationists, and researchers to make informed decisions that support sustainable forest management and conservation efforts.

The Forest Cover Change Analysis Tool is designed to facilitate this analysis by processing multi-temporal satellite raster data, identifying land use and land cover (LULC) transitions, and calculating the affected areas in hectares. This tool outputs both GeoTIFF files that visualize changes and Excel summaries that detail transition statistics.

## Project Goals
**1**- Track and quantify forest cover loss and gain over specified time periods.<br>
**2**-Provide actionable data to assist in forest conservation and management strategies.<br>
**3**-Support environmental reporting and policymaking with reliable LULC transition metrics.



## Theory and Background
### Importance of Forest Cover Analysis
Forests contribute significantly to the environment by:<br>

**Regulating Climate**: Forests absorb CO2, helping to mitigate the effects of climate change.<br>
**Biodiversity Support**: They provide habitats for countless species, ensuring ecosystem health and resilience.<br>
**Water Cycle Regulation**: Forests play a crucial role in water retention and preventing soil erosion.<br>

Deforestation and forest degradation can have severe consequences, including loss of biodiversity, disruption of local climates, and contribution to global warming. Conversely, reforestation and afforestation efforts contribute to reversing these adverse effects. Analyzing LULC transitions helps to identify these changes and supports data-driven conservation efforts.

### Remote Sensing in Forestry
Satellite imagery and remote sensing technologies are powerful tools for monitoring changes in land cover over large areas and extended periods. By processing raster data (e.g., GeoTIFFs) captured at different times, it is possible to:<br>

**Detect areas of deforestation.**
**Monitor regrowth and reforestation initiatives.**
**Analyze trends and predict future land cover changes.**



## Methodology
### Input Data
The tool works with GeoTIFF raster files representing LULC classifications for different years. The raster files should be georeferenced and include clear class labels for different land types.

### Process Workflow
**Data Import:** Read multi-temporal raster data using rasterio.
**Transition Analysis:** Compare raster data to identify LULC transitions between specific years.
**Area Calculation:** Compute the area of each transition type in hectares.
**Output Generation:** Save the results as a CSV file and create a GeoTIFF to visualize the changes.
### Output Interpretation
**GeoTIFF Files:** Visual representations of LULC transitions, where pixel values correspond to specific transitions.
**Excel Summary:** A detailed table showing the year, reference class, new class, pixel count, and area (in hectares).




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

![Workflow](Images/Workflow.png)



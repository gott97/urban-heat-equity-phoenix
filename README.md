![Python](https://img.shields.io/badge/Python-3.13-blue)
![ArcGIS Pro](https://img.shields.io/badge/ArcGIS-Pro-green)
![ArcPy](https://img.shields.io/badge/ArcPy-Spatial%20Analysis-orange)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

## Live Project

🌐 StoryMap:
https://storymaps.arcgis.com/stories/e975b895c9354858ac33ba7044ac577a

🗺 Interactive Web Map:
[<web map URL>](https://arcg.is/0P14nu1)

📄 Hosted Feature Layer:
<[feature layer URL](https://services6.arcgis.com/SDdpEAs6WyhEBmTu/arcgis/rest/services/Phoenix_Urban_Heat_Island_and_Tree_Canopy_Equity_Analysis/FeatureServer)>

# Phoenix Urban Heat Island & Tree Canopy Equity Analysis

## Project Overview

This project demonstrates a fully automated GIS workflow for identifying urban heat equity priorities across the City of Phoenix, Arizona. Using Landsat Collection 2 thermal imagery, National Land Cover Database (NLCD) Tree Canopy Cover, and American Community Survey (ACS) demographic data, the workflow quantifies the relationship between land surface temperature, tree canopy, and socioeconomic characteristics at the census tract level.

The project was developed as a professional portfolio piece to demonstrate geospatial analysis, Python automation, remote sensing, and ArcGIS Online publishing using reproducible workflows.

---

## Objectives

- Quantify land surface temperature using Landsat Collection 2 imagery
- Measure tree canopy cover using NLCD Tree Canopy data
- Integrate ACS demographic indicators through the Census API
- Calculate a Heat Equity Priority Score
- Publish an interactive web map and hosted feature layer to ArcGIS Online
- Demonstrate a reproducible GIS workflow using Python and ArcPy

---

## Workflow

![Workflow Diagram](figures/workflow.png)

The workflow consists of five major stages:

1. Data Acquisition
2. Data Preparation
3. Indicator Calculation
4. Visualization & Analysis
5. ArcGIS Online Publishing

---

## Outputs

### StoryMap

*Insert StoryMap screenshot here*

### Interactive Web Map

*Insert Web Map screenshot here*

### Example Analysis

| Income vs Temperature | Tree Canopy vs Temperature |
|------------------------|----------------------------|
| *(insert image)* | *(insert image)* |

---

## Data Sources

| Dataset | Source |
|---------|--------|
| Landsat Collection 2 Level-2 | Microsoft Planetary Computer |
| Tree Canopy Cover | National Land Cover Database (NLCD) |
| Census Tracts | U.S. Census Bureau TIGER/Line |
| Demographics | U.S. Census Bureau ACS 5-Year Estimates |

---

## Repository Structure

```
Phoenix-Urban-Heat-Equity-Analysis/
│
├── README.md
├── environment.yml
├── .gitignore
├── notebooks/
├── figures/
├── scripts/
└── outputs/
```

---

## Requirements

Create the project environment using Conda:

```bash
conda env create -f environment.yml
```

---

## Running the Workflow

Run the notebooks in the following order:

1. 01_acquire_data.ipynb
2. 02_prepare_data.ipynb
3. 03_calculate_indicators.ipynb
4. 04_analyze_visualize.ipynb
5. 05_publish_arcgis_online.ipynb

---

## Results

The completed workflow produces:

- Hosted Feature Layer
- Interactive Web Map
- StoryMap
- Statistical Tables
- Publication-quality Figures
- Reproducible Python Workflow

---

## Technologies

- ArcGIS Pro
- ArcGIS Online
- ArcPy
- ArcGIS API for Python
- Python
- pandas
- matplotlib
- Remote Sensing
- Landsat Collection 2
- Census API

---

## Related Resources

**StoryMap**

*(Add StoryMap URL after publishing)*

**Interactive Web Map**

*(Add Web Map URL after publishing)*

**Hosted Feature Layer**

*(Add Hosted Feature Layer URL after publishing)*

**LinkedIn**

*(Add LinkedIn Profile URL)*

---

## Author

**Ava Gotthard**

GIS Analyst | Remote Sensing | Spatial Analysis | Python Automation
The Python code, documentation, and original project materials are © Ava Gotthard and licensed under the MIT License. Public datasets remain subject to the terms and licenses of their respective providers, including the U.S. Census Bureau, USGS, and Esri where applicable.
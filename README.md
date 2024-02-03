# Project: Spatial Analysis of Education Levels and Sexual Harassment in the city Athens
## Overview
This project was made for the course of Geospatial Analysis and Representation of Data Science in University of Trento 2023.
The project aims to conduct a comprehensive analysis of the education levels  across regions of Athens and explore potential correlations with instances of sexual harassment  in those areas. Specifically, it seeks to identify any spatial dependencies between education levels and occurrences of sexual harassment, followed by spatial regression analysis to determine the impact of education on the frequency of sexual attacks.
## Project Structure
1. `Geospatial_Project_Athens_Criminality.ipynb`:This Jupyter Notebook file provides insights into how geospatial data, including shapefiles, was extracted from open data sources. Due to the absence of readily available data from national organizations, techniques were employed to extract the desired data from GeoFabrik.
2. `Data Preparation.Rmd` :This R Markdown file outlines the methods used to prepare the data, including computing relevant variables and indexes necessary for further analysis.
3. `Data Exploration.Rmd`: In this R Markdown file, you'll find data visualizations and descriptive statistics that offer valuable insights into the nature of the collected data.
4. `Moran Index Analysis.Rmd`: This R Markdown file contains spatial analysis for assessing the spatial dependence of the two variables under investigation, as well as the final spatial regression analysis.
## Packages Used
### Python :
- pygeoif
- osmium
- pyrosm
- geopandas
- os
- pygeos
- geopy
- osmium
- shapely.geometry
- Nominatim
- osmx
### R Studio
- spdep
- sf
- tmap
- leaflet
- readxl
- ggplot2
- dplyr
- spatialreg



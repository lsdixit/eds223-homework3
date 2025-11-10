# Quantifying the Texas blackout of 2021
## EDS223 - Homework #3 Leela Dixit

Repository containing all code and output for homework 3, in class EDS 223 of the MEDS program - Geospatial Analysis and Remote Sensing.
This project focuses on exploring light intensity before and after the 2021 storm, and trying to quantify the amount of homes affected in Houston.  

# Data
Data about light intensity was accessed through NASA's [Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC)](https://ladsweb.modaps.eosdis.nasa.gov/). We accounted for the light from roads using [OpenStreetMap (OSM)'s](https://planet.openstreetmap.org/) publicly available geographic data, downloaded through [Geofabrik](https://download.geofabrik.de/). Building data were also collected from OpenStreetMap. Socioeconomic data on census tracts and income were obtained from the [U.S Census Bureau's American Community Survey](https://www.census.gov/programs-surveys/acs). 

# Contents
- [README.md](https://github.com/lsdixit/eds223-homework3/blob/main/README.md) : file for the README.
- [texas_blackout.qmd](https://github.com/lsdixit/eds223-homework3/blob/main/texas_blackout.qmd) : file containing all code and outputs for this project.
- [texas_blackout_files](https://github.com/lsdixit/eds223-homework3/tree/main/texas_blackout_files) : Folder for rendering html.
- [texas_blackout.Rproj](https://github.com/lsdixit/eds223-homework3/blob/main/eds223-homework3.Rproj) : Project file.
- [texas_blackout.html](https://github.com/lsdixit/eds223-homework3/blob/main/texas_blackout.html) : Rendered project as html page.
- [texas_blackout.pdf]() : Rendered project as pdf.
- [figs]() : This folder contains all image outputs from the project.
- data are not pushed to GitHub. If recreating this repository, this is the suggested data structure:
  - .gitignore
    - data
      - gis_osm_buildings_a_free_1.gpkg
      - gis_osm_roads_free_1.gpkg
      - ACS_2019_5YR_TRACT_48_TEXAS.gdb
        - census tract gdb files
      - VNP46A1
        - VIIRS data files

# Author
This work was done by Leela Dixit, with assistance from students in EDS223, Annie Adams, and Ale Vidal Meza. 
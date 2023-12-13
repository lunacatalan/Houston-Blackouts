# Analysis of blackouts in the Houston, Texas metropolitan area in February 2021
This project looked at the impact of winter storms in Houston, Texas in Febuary, 2021. For more background information check out my [blog post!](https://lunacatalan.github.io/blog/2023-12-5-houston-blackouts/)

## Goals
- Explore the socioeconomic factors that influenced recovery post blackouts in the Houston, Texas metropolitan area.
- Explore relationship of median income of counties that had houses that experienced blackouts and those that did not.

## Visualizations
This project will have two visualizations in the `.RMD` file. The first will show the median income of the counties in Houston metropolitan area, and identify the counties that experienced a blackout between Feb 7th and Feb 16th, 2021. The second plot shows the distribution of median income comparing the counties that experienced blackouts and those that didn't. 

## Skills Highlights
- vector and raster data  operations
- vector and raster data manipulation
- spatial joins
- plotting with ggplot


Contents/Structure:

    Houston-Blackouts
    │   README.md
    │   Rmd/Proj files    
    │
    └───data
        │   gis_osm_buildings_a_free_1.gpkg
        │   gis_osm_roads_free_1.gpkg
        │
        └───ACS_2019_5YR_TRACT_48_TEXAS.gdb
        |   │   census tract gdb files
        |
        └───VNP46A1
        |   │   VIIRS data files

Data Download Instructions:

**IMPORTANT** The data associated with this assignment is too large to include in the GitHub repo. Data should be stored locally and added to .gitignore file. Download data from [here](https://drive.google.com/file/d/1bTk62xwOzBqWmmT791SbYbHxnCdjmBtw/view?usp=sharing).

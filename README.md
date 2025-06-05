# Biodiversity Intactness in Phoenix
## Changes in the Biodiversity Intactness Index Over Time

<img src="images/Arizona_Biodiversity.jpeg" width="800"/>

Image credit: [azsustainabilityalliance.com](https://www.azsustainabilityalliance.com/biodiversity-loss-in-arizona-what-we-can-do-about-it/)

This repository holds the notebook `biodiversity_intactness_index.ipynb`, which aims to visualize the parts of the Phoenix subdivision of Maricopa County, Arizona with an observed decrease in biodiversity from 2017-2020. In 2021, Maricopa County was identified as the U.S. county with the most significant increase in developed land since 2001 [1]. The rapid expansion of this area has significant impacts on biodiversity and the well-being of nearby natural ecosystems. The investigation uses biodiversity intactness index (BII) data and geospatial data to highlight these changes.

## Data

All data used is housed locally within the repository in the `data` folder and was originally sourced from the locations listed below. 

## Citations

1. Z. Levitt and J. Eng, “Where America’s developed areas are growing: ‘Way off into the horizon’,” The Washington Post, Aug. 2021, Available: https://www.washingtonpost.com/nation/interactive/2021/land-development-urban-growth-maps/. Accessed: December 4, 2024.

2. Microsoft.com, "Microsoft Planetary Computer."  2024,  Biodiversity Intactness STAC collection https://planetarycomputer.microsoft.com/dataset/io-biodiversity. Accessed: December 4, 2024.
    
3. United States Census Bureau. (2024). Arizona County Subdivision 2024 TIGER/Line Shapefiles. [Data File]. U.S. Census Bureau, Geography Division. https://www.census.gov/cgi-bin/geo/shapefiles/index.php?year=2022&layergroup=County+Subdivisions Accessed: December 4, 2024.
    
## Acknowledgments & References

All materials were created by [Carmen Galaz-Garcia](https://github.com/carmengg) for [EDS-220: Working with Environmental Data](https://meds-eds-220.github.io/MEDS-eds-220-course/).


## Repository Organization

```
├── data
│   └── arizona_lines.zip  # Arizona county boundary data
├── images
│   ├── Arizona_Biodiversity.jpeg
│   └── Phainopepla_Arizona.jpg
├── .gitignore
├── README.md
└── biodiversity_intactness_index_phoenix.ipynb # Jupyter notebooks for analysis
```

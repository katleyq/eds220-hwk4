# Using Remote Sensing Data to Identify Areas Affected by Wildfire

![Image of wildfire on coast captured by USGS.](https://images.unsplash.com/photo-1722083854858-79fb7ea85380?q=80&w=2680&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)


**About**: 

This purpose of this repository is to demonstrate how to use remote sensing data to identify burn areas. We'll use the Thomas Fire that occurred in Santa Barbara County, California in 2017 as a case study.

**Repository Structure:**

This repository contains two notebooks: 
`hwk4-task2-fire-perimeter-LE.ipynb` - Used to obtain Thomas Fire Polygon 
`hwk4-task2-false-color-LE.ipynb` - Used to generate true and false color images to compare to vector data

The repository has the following structure:

```
eds220-hwk4
│   README.md
|   hwk4-task2-fire-perimeter-LE.ipynb 
│   hwk4-task2-false-color-LE.ipynb 
|   .gitignore
│
└───data
    │   landsat8-2018-01-26-sb-simplified.nc
    │   California_Fire_Perimeters
```

**Data**

This notebook utilizes the following datasets:

1) Thomas Fire Perimeter Data: This data was retrieved from US governement's data catalogue. Original Source:[California Fire Perimeter Data](https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436)

2) Landsat Data: This data was retrieved from the Microsoft Planetary Computer Data Catalogue, pre-processed by Dr. Carmen Galaz-Garcia, and stored on the MEDS computational server.  Original Source: [Microsoft Planetary Computer Data Catalogue](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2)


**References**

Microsoft Planetary Computer. (Access Date: November 2024). Landsat Collection 2, Level-2 [Dataset]. U.S. Geological Survey (USGS). https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2

Riebeek, H. (2014, March 4). Why is that forest red and that cloud blue? NASA Earth Observatory. https://earthobservatory.nasa.gov/features/FalseColor

U.S. Geological Survey. (2021, November 12). Common Landsat band combinations [Image]. U.S. Department of the Interior. https://www.usgs.gov/media/images/common-landsat-band-combinations

U.S. Geological Survey. (Access Date: November 2024). California fire perimeters (all) [Dataset]. Data.gov. https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436


**Acnknowledgements**

This repository was created as an assignment for [EDS 220: Working with Environmental Datasets](https://meds-eds-220.github.io/MEDS-eds-220-course/) at the [UCSB Bren School of Environmental Science & Management](https://bren.ucsb.edu/). This course is led by Dr. Carmen Galaz-Garcia and Annie Adams. 
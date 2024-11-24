# Using Remote Sensing Data to Identify Areas Affected by Wildfire

**About**: 



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

U.S. Geological Survey. (Access Date: November 2024). California fire perimeters (all) [Dataset]. Data.gov. https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436


**Acnknowledgements**

This repository was created as an assignment for [EDS 220: Working with Environmental Datasets](https://meds-eds-220.github.io/MEDS-eds-220-course/) at the [UCSB Bren School of Environmental Science & Management](https://bren.ucsb.edu/). This course is led by Dr. Carmen Galaz-Garcia and Annie Adams. 
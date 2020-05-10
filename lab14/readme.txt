svi_chi_4326, shapefile of CDC SVI data (2018), procssed and downloaded from https://svi.cdc.gov/data-and-tools-download.html

Processing steps:
1. Tracts whose centroids fall within Chicago (city) boundary are extracted
2. Coordinate Reference System was transformed from NAD 83 (epsg: 4269) to WSG 84 (epsg: 4326) using a transformation method 

# AI4EO-Final-Project
Description: we are finding anomalies by prediction of night lights in London based on financial, building volume and greenery data with 3 model approaches: linear regression, random forest and MLP.

Software Used:
- Python version 3.13
- Python Libraries: ee, geopandas, geemap, sklearn, rasterio, numpy, rasterstats, requests, statsmodells, matplotlib, folium branca, jinja2, re, libpysal, esda
Datasets (all get extracted if the code is run properly):
- VIIRS night lights dataset
- GlobalBuildingAtlas dataset
- Sentinel-2 dataset
- Ward Profiles London dataset
- Statistical GIS Boundary dataset of London

Running the code:
- code is mounted on google drive and is designed to run on a google colab environment, specify own root to correctly save the inputs, intermediate and final results
- gee needs to be authenticated (active GEE account needed)

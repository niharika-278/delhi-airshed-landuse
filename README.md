### Delhi Airshed Landuse Classification

### 

##### **📌 Project Overview**



This project builds a geospatial pipeline to analyze land-use patterns over the Delhi Airshed using Sentinel-2 satellite imagery and ESA WorldCover 2021 data.



The workflow integrates spatial reasoning, raster processing, and dataset preparation for supervised land-use classification.



   Model training (CNN) is planned but not implemented yet.



# 



##### **🗂️ Dataset Used**



Delhi Airshed Sentinel-2 RGB and Landcover \[[Link](https://www.kaggle.com/datasets/rishabhsnip/earth-observation-delhi-airshed)] **(EPSG:4326)**

###### 

Gridding CRS: **EPSG:32644**



# 



##### **🧠 Pipeline Summary**

###### 

\- CRS transformation to EPSG:32644

\- Uniform spatial grid generation

\- Point-in-polygon filtering

\- Raster patch extraction

\- Mode-based label assignment

\- Dataset split for supervised learning



# 



##### **🛠️ Tech Stack**



\- Python

\- GeoPandas

\- Rasterio

\- NumPy

\- Matplotlib

\- scikit-learn



# 



###### **AI Tools Used**



\- ChatGPT (OpenAI) – assistance with basic structuring, debugging, and README documentation.


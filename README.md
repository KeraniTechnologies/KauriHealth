# KauriHealth
VEGETATION CLASSIFICATION USING REMOTE SENSING TECHNIQUES

The purpose of these scripts is to identify kauri die-back and how kauri vegetation health has changed over time in the Waitakere Ranges, New Zealand using remotely sensed image data from Landsat-8, Sentinel-2, RapidEye satellites and LiDAR. 

 LiDAR data is available from here: https://myvuwac-my.sharepoint.com/:u:/g/personal/lesterkerr_myvuw_ac_nz/EXymPkPEe9BCrnH71n80GYkB_CoTdf9m-UwqxUs2aNcYNg?e=VUKBAJ
 
 Satellite data: https://myvuwac-my.sharepoint.com/:f:/g/personal/lesterkerr_myvuw_ac_nz/EkTSzaaohuVHlaYjgjJFy-EB5KT6wbLNZZc5XKlLpk5XRA?e=6XcaDc

Tasks	

·	Mosaicking of lidar raster tiles
.    Create tree canopy height model from open source LiDAR
·	Acquire multispectral satellite data of the region

Ongoing To Do list:
     
.    Identify kauri trees and how vegetation health has changed over time in the Waitakere Ranges

·	Using each identified kauri tree canopy extent/spectral_classification/ and location, associate various vegetation indices

·	Analyze create maps, frequency and density plots highlighting the differences between years, months and vegetation indices

·	Create plots of the spectral profile differences of the Kauri health between health category ranges

·	Explain variations, clustering patterns and the potential to further monitor kauri dieback disease.

.    What statistical analysis are we going to do that show:
          a) how kauri vegetation health has changed over time?
          b) explain the relationships between seasonal changes in vegetation indices values.
          c) add a layer showing roads/walking paths/rivers/streams
     

Resources:
1) Install python deep learning frameworks for ArcGIS https://pro.arcgis.com/en/pro-app/help/analysis/image-analyst/install-deep-learning-frameworks.htm

2) ESRI Github page https://github.com/Esri/raster-deep-learning

3) ArcGIS Pro Python reference https://pro.arcgis.com/en/pro-app/arcpy/main/arcgis-pro-arcpy-reference.htm

4) Discovery Paths https://www.esri.com/en-us/arcgis/products/arcgis-pro/resources

Python Scripts:
Create instructional Notebooks 
Learn machine learning processes of identifying trees/vegetation in python
Build Plugin for ESRI? 

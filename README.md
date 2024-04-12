# CloudComputing_finalproject
Relationship among land surface temperature (LST), normalized difference vegetation index (NDVI) with topographic slope element in Central America.

var dataset = ee.Image('USGS/SRTMGL1_003'); 
var elevation = dataset.select('elevation');
var data = dataset.clip(roi); //Costa Rica, El Salvador y Panamá
var SA_DEM = data.select('elevation')
print(SA_DEM,'elevation');

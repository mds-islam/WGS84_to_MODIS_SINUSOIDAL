# About
When performing spatial operations, it is necessary to bring all the data layers into the same coordinate reference systems (CRS). The MODIS products come with a Sinusoidal projection system. 

Therefore, if we want to extract time series values from a MODIS dataset, we must convert the sample points' CRS into a MODIS Sinusoidal reference system. The same goes for other datasets (i.e., raster or vector layers) when working with MODIS data.

This script provides code to perform this type of task written in Python.

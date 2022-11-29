README for:
* NYC_CounDist_GreenRoof_Bldg_MaxHVI_PctCSO.gpkg
* NYC_CounDist_GreenRoof_Bldg_MaxHVI_PctCSO.csv.
* HeatVulnerabiltiy_Stormwater_Correlation_Analyses.R

The data and R code in these files were data were used for correlation analyses to assess the relationship 
between the number and area of green roofs in City Council Districts of NYC and the maximum Heat Vulnerability 
Index, and percent overlap with a combined sewer system area. The files are associated with a peer reviewed paper, 
"Examining the distribution of green roofs in New York City through a lens of social-ecological-technological 
filters" published in Ecology and Society. The associated green roof dataset is available at 
https://zenodo.org/record/1469674 and a GitHub repository associated with this work is available at: https://github.com/tnc-ny-science/NYC_GreenRoofMapping.

The file 'HeatVulnerabiltiy_Stormwater_Correlation_Analyses.R' is commented for usage

The file 'NYC_CounDist_GreenRoof_Bldg_MaxHVI_PctCSO.gpkg' is a spatial data file with a single layer for NYC City Council District Boundaries, (the .csv version does not have spatial data within it). The colun names for these files are as follows:
* coun_dist - Unique Idnetifier for each City Council District
* Borough -  Name of the borough containing the respective City Council District
* num_greenroofs - Number of Green Roofs Contained in the respective City Council District
* greenroof_area_sqmeters - total area (square meters) of green roofs in each City Council District
* num_bldgs_total - Number of total buildings contained within the respective City Council District
* bldg_area_total_sqmeters - Total area (square meters) of buildings in each City Council District
* prop_greenroofs_of_bldgs - Proportion of the buildings in each City Council District with a green roof
* prop_greenroofarea_of_bldgarea - Proportion of the rooftop area (building footprint area) covered by green roof within each City Council District
* hvi_nta_2018_max - Maximum heat vulnerability index score of overlapping neighborhood tabulation areas, based on overlay with 152.4 m inner buffer of neighborhood tabulation areas
* prop_gipriority - Proportion of overlap for City Council District with combined sewer area.
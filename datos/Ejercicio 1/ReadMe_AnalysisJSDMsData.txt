#####################################################################
#
# README Analysis of JSDMs Data
#
#####################################################################
#
# There are 3 data sets in OwlGlider_SurveyData zipped folder including 
#                  species observations
#                  occupancy covariates, and 
#                  detection covariates.
#
#  All data is in CSV format
#  An outline of the data is presented below.  A further detailed description
# can be found in the excel file DetailedDataExplanation.xlsx.
#
####################################################################
#
# Data type: species observations
# File name: so_species_data.csv
# Source: Dr.Matt White and the Arthur Rylah Institute, and 
#         the Department of Environment, Land, Water and Planning (Victoria):
#         field data from the Victorian Central Highland Owl and Glider Study
#
# Fields
#
#     x:     easting location of the observation site
#     y:     northing location of the observation site
#   PO1:     count of powerful owls for survey replication 1
#   PO2:     count of powerful owls for survey replication 2
#   PO3:     count of powerful owls for survey replication 3
#   SO1:     count of sooty owls for survey replication 1
#   SO2:     count of sooty owls for survey replication 2
#   SO3:     count of sooty owls for survey replication 3
#   GG1:     count of greater gliders for survey replication 1
#   GG2:     count of greater gliders for survey replication 2
#   GG3:     count of greater gliders for survey replication 3
#   YB1:     count of yellow bellied gliders for survey replication 1
#   YB2:     count of yellow bellied gliders for survey replication 2
#   YB3:     count of yellow bellied gliders for survey replication 3
#
# Note: if no count made (i.e. missing), entry is set to NA.  
# A 0 indicates a count of 0 was made.

####################################################################
#
# Data type: occupancy covariates
# File name: so_occupancy_cov.csv
# Fields
#
#  RainfallJan75m:     Mean rainfall for January for 75m resolution
#  RainfallJul75m:     Mean rainfall for July for 75m resolution
#  Dem75mInteger:      Mean site elevation for 75m resolution
#  terrain_ruggedness_index_sept2012:   Terrain Ruggedness Index (TRI) as calculated September 2012.
#                                       TRI measures mean difference in elvation between a cell and its neighbours.
#  wetness_index_saga_sept2012:         SAGA Wetness Index as calculated September 2012 
#  topographic_position_index_sept2012: Topographic Position Index (TPI) as calculated September 2012
#                                       TPI measures difference in elvation between a cell and and 
#                                       the mean elevation of itsneighbours.
#  SouthSummerEVI:     Enhanced vegetation index (EVI) calculated for the southern hemisphere summer.
#                      EVI is calculated from reflected red, blue and infrared reflection and
#                      corrects for atmospheric conditions.  EVI is sensitive to canopy structure.
#  SouthSummerNDVI:    Normalized Difference Vegetation Index (NDVI) calculated for the southern hemisphere summer.
#                      NDVI is calculated from reflected red, and infrared reflection. 
#                      NDVI is sensitive to vegetation density and lushness.

####################################################################
#
# Data type: detection covariates
# File name: so_detection_cov.csv
# Fields
# 
#   wind1:    windspeed as record in 5 point scale (0 to 4, using mean for missing data) for survey replication 1
#   wind2:    windspeed as record in 5 point scale (0 to 4, using mean for missing data) for survey replication 2
#   wind3:    windspeed as record in 5 point scale (0 to 4, using mean for missing data) for survey replication 3
#   yday1:    years day of survey replication 1 relative to June 1
#   yday2:    years day of survey replication 2 relative to June 1
#   yday3:    years day of survey replication 3 relative to June 1
#
# Note: negative ydays indicate days before June 1 (i.e. autumn days) while
#       positive days are days after June 1 (i.e. winter days).
#       ydays is used to calculate the categorical covariate winter which is 1 if winter day, 0 if autumn
#       All days are in winter or Autumn.

####################################################################




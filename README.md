![GEE_xtract](https://user-images.githubusercontent.com/24545206/189917216-d955b4c4-160d-4d9d-ad6e-89357ff64f76.png)

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

#### GEE_xtract is a Google Earth Engine (GEE) code for extracting remotely sensed data from ground-based data, at multiple spatial and temporal scales. Here, scale magnitude and how data is aggregated is defined by the user. Second, while GEE_xtract was primarily conceived to solve ecological scaling issues, on the other hand, it was concomitantly adapted to retain high-quality data, thus avoiding biases and anomalies during data extraction. Third, the code was further prepared for multiple secondary needs, notably to combine data from different sources, to soften computation limits throghout different strategies, and to produce advanced metrics.

The funcionality of the code, for each of the satellites, can be verified directly on GEE, specifically for [MODIS](https://code.earthengine.google.com/?scriptPath=users%2Fvaleriofrank%2FGEE_xtract%3AExtract_Points_MODIS) satellites and associated products for [data-fusion](https://code.earthengine.google.com/?scriptPath=users%2Fvaleriofrank%2FGEE_xtract%3AExtract_Points_MODIS_For_Data_Fusion) approaches, as well for [Landsat](https://code.earthengine.google.com/?scriptPath=users%2Fvaleriofrank%2FGEE_xtract%3AExtract_Points_Landsat) satellites and [Sentinel-2](https://code.earthengine.google.com/?scriptPath=users%2Fvaleriofrank%2FGEE_xtract%3AExtract_Points_Sentinel). The sample datasets are disposable as vectors at [Figshare](https://figshare.com/articles/dataset/Annual_Ground_Observations_and_Study_Area/21641564).

The GEE_xtract code was developed for three public satellites, namely MODIS, Landsat, and Sentinel 2.

Moreover, besides the GEE extraction codes, two secundary directories are available:

1. The first directory contains GEE codes for extracting data from ground data for each satellite. In addition, another directory is present which contains codes for extrapolate variables, hence for writing meaningful habitat metrics for each satellite. The type of metric to be extrapolated can be parameterised and adapted by the user.

2. The second directory contains a working example in R on how combine different dataset with remotely sensed extracted information, to help those users that decided to split data annually.

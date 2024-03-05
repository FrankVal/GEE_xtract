![GEE_xtract](https://user-images.githubusercontent.com/24545206/189917216-d955b4c4-160d-4d9d-ad6e-89357ff64f76.png)

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

#### GEE_xtract is a Google Earth Engine (GEE) code for extracting remotely sensed data from ground-based data, at multiple spatial and temporal scales. Here, scale magnitude and how data is aggregated is defined by the user. Second, while GEE_xtract was primarily conceived to solve ecological scaling issues, on the other hand, it was concomitantly adapted to retain high-quality data, thus avoiding biases and anomalies during data extraction. Third, the code was further prepared for multiple secondary needs, notably to combine data from different sources, to soften computation limits throghout different strategies, and to produce advanced metrics.

The GEE_xtract code was developed for three public satellites, namely MODIS, Landsat, and Sentinel 2.
The funcionality of the code, for each of the satellites, can be verified directly on GEE computing platform, specifically for [MODIS](https://code.earthengine.google.com/?scriptPath=users%2Fvaleriofrank%2FGEE_xtract%3AExtract_Points_MODIS) satellites and associated products for [data-fusion](https://code.earthengine.google.com/?scriptPath=users%2Fvaleriofrank%2FGEE_xtract%3AExtract_Points_MODIS_For_Data_Fusion) approaches, as well for [Landsat](https://code.earthengine.google.com/?scriptPath=users%2Fvaleriofrank%2FGEE_xtract%3AExtract_Points_Landsat) and [Sentinel-2](https://code.earthengine.google.com/?scriptPath=users%2Fvaleriofrank%2FGEE_xtract%3AExtract_Points_Sentinel) satellites. The sample datasets used for running the command-lines are disposable as vectors at [Figshare](https://figshare.com/articles/dataset/Annual_Ground_Observations_and_Study_Area/21641564).

Two secundary directories are available:

1. The first directory contains GEE codes for extracting data from ground data for each satellite. In addition, another directory is present which contains codes for extrapolate variables, hence for writing meaningful habitat metrics from each satellite. The type of metric to be extrapolated should be prepared by the user following the MSAVI2 example.

2. The second directory contains a working example in R on how combine different dataset with remotely sensed extracted information, with the aim to help users that decided to split data annually.


Cite this work:

Valerio F, Godinho S, Marques AT, Crispim-Mendes T, Pita R, Silva JP (2024) GEE_xtract: High-quality remote sensing data preparation and extraction for multiple spatio-temporal ecological scaling. Ecol Inform 80:102502. https://doi.org/10.1016/j.ecoinf.2024.102502

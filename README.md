![GEE_xtract](https://user-images.githubusercontent.com/24545206/189917216-d955b4c4-160d-4d9d-ad6e-89357ff64f76.png)

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

#### GEE_xtract is a Google Earth Engine (GEE) code for extracting remotely sensed data from ground-based data, at multiple spatial and temporal scales. Here, magnitude and how data is aggregated is defined by the user. Second, while GEE_xtract was primarily conceived to solve ecological scaling issues, on the other hand, it was concomitantly adapted to retain high-quality data, thus avoiding biases and anomalies during data extraction. Third, the code was further prepared for multiple secondary needs, notably to combine data from different sources, to soften computation limits throghout different strategies, and to produce advanced metrics.

The funcionality of the code, for each of the satellites, can be verified directly on [GEE](https://code.earthengine.google.com/?accept_repo=users/valeriofrank/GEE_xtract), and through a dataset of samples, which is available on [GEE](https://code.earthengine.google.com/?asset=users/valeriofrank/Methods_Ecol_Evol), or from the sample data directory.

The GEE_xtract code was developed for three public satellites, namely MODIS, Landsat, and Sentinel 2.

Moreover, besides the GEE extraction codes, two secundary directories are available:

1. The first directory contains GEE codes for extracting data from ground data for each satellite. In addition, another directory is present which contains codes for extrapolate variables, hence for writing meaningful habitat metrics for each satellite. The type of metric to be extrapolated can be parameterised and adapted by the user.

2. The second directory is a working example in R on how combine different dataset with remotely sensed extracted information, and how identify significant habitat metrics. 

3. The third directory refers to telemetry observations used as example for data extraction, and represent the ecological case of study in the manuscript.

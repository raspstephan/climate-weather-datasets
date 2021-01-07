---
layout: post
title: Preprocessed Datasets
permalink: /preprocessed_datasets/
---

This is a list of weather and climate datasets preprocessed for AI research. This can include benchmarks, competitions or ML papers with published data. The list is in alphabetical order.


### AMS Solar Energy Prediction Contest
- *Code and data*: [https://www.kaggle.com/c/ams-2014-solar-energy-prediction-contest](https://www.kaggle.com/c/ams-2014-solar-energy-prediction-contest)
- *Source data*: GEFS forecasts and Mesonet solar observations
- *Description*: Predict total daily solar irradiance from GEFS and Oklahoma Mesonet Data

### ClimateNet: an expert-labelled open dataset and Deep Learning architecture for enabling high-precision analyses of extreme weather
- *Paper*: [https://gmd.copernicus.org/preprints/gmd-2020-72/](https://gmd.copernicus.org/preprints/gmd-2020-72/)
- *Code and data*: [https://portal.nersc.gov/project/ClimateNet/](https://portal.nersc.gov/project/ClimateNet/)
- *Source data*: Climate Model simulations and expert labels
- *Description*: Detect atmospheric rivers and tropical cyclones from climate model simulations. Tool for labeling along with dataset of expert labelled data.

### Deepti: Deep-Learning-Based Tropical Cyclone Intensity Estimation System (+ Competition)
- *Paper*: [http://doi.org/10.1109/JSTARS.2020.3011907](http://doi.org/10.1109/JSTARS.2020.3011907)
- *Competition*: [https://www.drivendata.org/competitions/72/predict-wind-speeds/page/274/](https://www.drivendata.org/competitions/72/predict-wind-speeds/page/274/)
- *Code and data*: [http://registry.mlhub.earth/10.34911/rdnt.xs53up/ ](http://registry.mlhub.earth/10.34911/rdnt.xs53up/ )
- *Source data*: GOES
- *Description*: A collection of tropical storms in the Atlantic and East Pacific Oceans from 2000 to 2019 with corresponding maximum sustained surface wind speed. This dataset is split into training and test categories for the purpose of a competition.
The train set consists of 70,257 images and the test set consists of 44,377 image, each one being 366 x 366 pixels

### EarthNet2021: A novel large-scale dataset and challenge for forecasting localized climate impacts
- *Paper*: [https://arxiv.org/abs/2012.06246](https://arxiv.org/abs/2012.06246)
- *Code and data*: [https://www.earthnet.tech/](https://www.earthnet.tech/)
- *Source data*: Sentinel 2
- *Description*: Curated dataset containing target spatio-temporal Sentinel 2 satellite imagery at 20 m resolution, matched with high-resolution topography and mesoscale (1.28 km) weather variables. With over 32000 samples it is suitable for training deep neural networks.

### The ExtremeWeather Dataset
- *Paper*: [https://arxiv.org/abs/1612.02095 ](https://arxiv.org/abs/1612.02095 )
- *Code and data*: [https://github.com/eracah/hur-detect](https://github.com/eracah/hur-detect), [https://extremeweatherdataset.github.io/](https://extremeweatherdataset.github.io/)
- *Source data*: CAM5
- *Description*: Consists of 768 × 1152 images of the global atmospheric state with a spatial resolution of 25 km and separated by 6 hour intervals from 1979 to 2005. There are 16 channels of images that correspond to different variables such as surface pressure, surface temperature and humidity of the reference altitude. In addition, there are boundary boxes and class labels for 4 types of extreme weather events: Tropical Depressions, Tropical Cyclones, Extratropical Cyclones and Atmospheric Rivers.

### FlowDB: A new large scale river flow, flash flood, and precipitation dataset
- *Paper*: [https://arxiv.org/abs/2012.11154](https://arxiv.org/abs/2012.11154)
- *Code and data*: [https://flow-forecast.atlassian.net/wiki/spaces/FF/pages/33456135/FlowDB+Dataset](https://flow-forecast.atlassian.net/wiki/spaces/FF/pages/33456135/FlowDB+Dataset) (Not public)
- *Source data*: USGS, SNOTEL, NOAA, ASOS,EcoNet
- *Description*: An hourly river flow and precipitation dataset and a second subset of flash flood events with damage estimates and injury counts. Created for general stream flow forecasting and flash flood damage estimation.

### How Much Did It Rain I and II
- *Code and data*: <a href="https://www.kaggle.com/c/how-much-did-it-rain">https://www.kaggle.com/c/how-much-did-it-rain</a> and <a href="https://www.kaggle.com/c/how-much-did-it-rain-ii">https://www.kaggle.com/c/how-much-did-it-rain-ii</a>
- *Source data*: US Radar and rain gauges
- *Description*: Estimate rainfall probability distribution from Dual Pol. radar data.


### MeteoNet, an open reference weather dataset by METEO FRANCE
- *Code and data*: <a href="https://github.com/meteofrance/meteonet">https://github.com/meteofrance/meteonet</a>
- *Source data*: AROME/ARPEGE forecasts, radar reflectivity and ground stations over France
- *Description*: Multi source dataset of forecasts and observations over France spanning 3 years


### Neural Networks for Postprocessing Ensemble Weather Forecasts
- *Paper*: [Rasp and Lerch 2018](https://journals.ametsoc.org/view/journals/mwre/146/11/mwr-d-18-0187.1.xml?tab_body=fulltext-display)
- *Code and data*: [https://github.com/slerch/ppnn](https://github.com/slerch/ppnn)
- *Source data*: TIGGE forecasts and station observations over Germany
- *Description*: Ensemble temperature postprocessing of station observations over Germany. 9 years of data at 500 stations. Predictors include temperature as well as a range of other variables.


### RainBench: Towards Global Precipitation Forecasting from Satellite Imagery
- *Paper*: [https://arxiv.org/abs/2012.09670](https://arxiv.org/abs/2012.09670)
- *Code and data*: [https://github.com/frontierdevelopmentlab/pyrain](https://github.com/frontierdevelopmentlab/pyrain)
- *Source data*: IMERG, ERA5 and SimSat
- *Description*: Multi-modal benchmark dataset for data-driven precipitation forecasting at 3 different spatial resolutions: 0.1deg (IMERG and SimSat) and 0.5deg (ERA5).
Presented along an efficient dataloading pipeline: Pyrain


### SEVIR Dataset
- *Paper*: [NeurIPS](https://proceedings.neurips.cc/paper/2020/file/fa78a16157fed00d7a80515818432169-Paper.pdf)
- *Code and data*: [http://sevir.mit.edu/](http://sevir.mit.edu/)
- *Source data*: GOES-16 and NEXRAD over CONUS
- *Description*: Preprocessed satellite and radar data over the continental US, served in patches. For a range of challenges with baselines (check website for updates).

### SVRIMG - SeVere Reflectivity IMaGe Dataset
- *Presentation*: [AMS](https://ams.confex.com/ams/101ANNUAL/meetingapp.cgi/Paper/384398) 
- *Code and data*: [https://svrimg.org/](https://svrimg.org/)
- *Source data*: GridRad (which in turn is sourced from NOAA NEXRAD Level II archives)
- *Description*: over 500,000 data rich, geospatial, radar reflectivity images centered on high-impact weather events. These images have consistent dimensions and intensity values on a grid with relatively low spatial distortion over the Conterminous United States. Also includes crowd-sourced labeling.


### TAASRAD19, a high-resolution weather radar reflectivity dataset for precipitation nowcasting
- *Paper*: [https://doi.org/10.1038/s41597-020-0574-8](https://doi.org/10.1038/s41597-020-0574-8)
- *Code and data*:[https://github.com/MPBA/TAASRAD19](https://github.com/MPBA/TAASRAD19)
- *Source data*: Official public meteorological agency of the civil protection department of the Autonomous Province of Trento (Italy)
- *Description*: Benchmark dataset for radar nowcasting with deep learning. The dataset contains 1,732 radar sequences labeled with precipitation type spanning from 2010 to 2019, for a total of 362,233 radar images. Image size is 480 x 480 at 500m resolution (UTM grid) covering a complex orographic area in the Italian Alps.
- *Papers using this dataset*: <a href="https://doi.org/10.3390/atmos11030267">https://doi.org/10.3390/atmos11030267</a>, <a href="https://doi.org/10.3390/rs11242922">https://doi.org/10.3390/rs11242922</a>


### Understanding Clouds from Satellite Images
- *Paper*: [BAMS](https://journals.ametsoc.org/view/journals/bams/101/11/bamsD190324.xml)
- *Code and data*: [https://www.kaggle.com/c/understanding_cloud_organization](https://www.kaggle.com/c/understanding_cloud_organization)
- *Source data*: TERRA and AQUA MODIS visible images
- *Description*: Cloud classification challenge of 4 human-designed shallow cloud patterns of organization: Sugar, Flower, Fish and Gravel with 30,000 human labels

### VALUE: A framework to validate downscaling approaches for climate change studies
- *Paper*: [https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2014EF000259](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2014EF000259)
- *Code and data*: [http://www.value-cost.eu/](http://www.value-cost.eu/)
- *Source data*: Station observations
- *Description*: Framework for evaluating climate model downscaling methods. Validation observations are provided.
- *Papers using this dataset*: Many

### WeatherBench: A Benchmark Data Set for Data‐Driven Weather Forecasting
- *Paper*: [https://doi.org/10.1029/2020MS002203](https://doi.org/10.1029/2020MS002203)
- *Code and data*: [https://github.com/pangeo-data/WeatherBench](https://github.com/pangeo-data/WeatherBench)
- *Source data*: ERA5 and TIGGE for baselines
- *Description*: Benchmark dataset for medium-range (3 and 5 day) forecasting of global pressure, temperature and precipitation with preprocessed data (40 years), evaluation and baselines
- *Papers using this dataset*: <a href="https://arxiv.org/abs/2003.11927">https://arxiv.org/abs/2003.11927</a>, <a href="https://arxiv.org/abs/2008.08626">https://arxiv.org/abs/2008.08626</a>









### Template
- *Paper*: 
- *Code and data*: 
- *Source data*: 
- *Description*: 
- *Papers using this dataset*:




## General description


This is an example of the use of satellite and model-derived data in SnowPower, yielding a prediction of hydropower energy generation in the Italian river watersheds in the Alps.
This hands-on Case Study closely mimicks the Energy module of SnowPower, leveraging runoff data from SnowPower's Runoff module and other selected climate variables to produce predictions of energy generation in target areas.

### Data origin 

The Energy module of SnowPower ingests information about water runoff in the basin, as well as other features describing meteorological conditions such as temperature, and energy market demand.
The dataset spans over the melting seasons (April-September) of 2017-2020. The variables included in the dataset are:

- *time*
- *t2m_mean* -- mean daily air temperature at 2m from ground surface, averaged over the Italian watersheds, from ERA5 data
- *runoff* -- water runoff in the study area in m/s, output of the Runoff model of SnowPower
- *e_load* -- daily energy load in the Northern Italy bidding zone from ENTSO-E data
- *energy* -- energy generation in GWh/km2, processed from ENTSO-E data

### Getting started

To execute this Case Study, please use the Jupyter Notebook *Asset2_casestudy.ipynb*.
To run the Jupyter Notebook some packages are required. Using a dedicated virtual environment is kindly suggested.

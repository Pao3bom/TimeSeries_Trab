# TimeSeries_Trab

The two notebooks in this repository perform distinct tasks of Time Series Analysis in the [Beijing Multi-Site Air Quality](https://archive.ics.uci.edu/dataset/501/beijing+multi+site+air+quality+data) Dataset, to quote the link:
> This data set includes hourly air pollutants data from 12 nationally-controlled air-quality monitoring sites. The air-quality data are from the Beijing Municipal Environmental Monitoring Center. The meteorological data in each air-quality site are matched with the nearest weather station from the China Meteorological Administration. The time period is from March 1st, 2013 to February 28th, 2017. Missing data are denoted as NA.

The first of them attempts to detect anomalies in the multiple time-series contained in the data, evaluating if any high anomaly score is something affecting the city as a whole or if it's just an isolated case.

The second contains a novel strategy of forecasting. It uses 11 stations to forecast the data of the 12th (what we call the Centerpoint), giving weights to the predictions of each station according to their distance to the Centerpoint. The results are promising.

NOTE: Both notebooks are standalone. As long as you have the required libraries there's no need to manually download the data.

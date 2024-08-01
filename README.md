# Predicting Wildfires in Bejaia

## Introduction
Wildfires are among the most devastating natural disasters, leading to significant material and human losses, particularly in regions where urban areas intersect with dense forests. In recent years, the Bejaia region of Algeria has experienced severe wildfires that have caused widespread damage. Addressing this challenge requires proactive measures that leverage technology and data-driven approaches.

## Purpose of This Study
The primary objective of this study is to employ advanced data mining techniques and classification methodologies to develop predictive models that anticipate and manage wildfires in the Bejaia region. By analyzing historical fire data from the **Fires_in_Bejaia.csv** dataset and studying relevant environmental factors, we aim to create accurate models that can predict wildfire occurrences, thereby aiding in their prevention and management.

## Dataset Overview
This study utilizes data from two regions in Algeria, specifically focusing on the Bejaia region in the northeast. The dataset spans from June 2012 to September 2012 and comprises 244 instances, each with 11 attributes and 1 target variable (class).
- link to the dataset : https://archive.ics.uci.edu/dataset/547/algerian+forest+fires+dataset

### First Dataset Description
- **Date**: Observations of weather data on specific days, recorded in the format DD/MM/YYYY.
- **Temp**: Maximum temperature at noon in Celsius.
- **RH (Relative Humidity)**: Humidity percentage.
- **Ws (Wind Speed)**: Wind speed in km/h.
- **Rain**: Total daily rainfall in mm.
- **Fine Fuel Moisture Code (FFMC)**: Index from the Fire Weather Index (FWI) system indicating the moisture content of surface litter and other fine fuels.
- **Duff Moisture Code (DMC)**: Index representing the moisture content of decomposing organic material.
- **Drought Code (DC)**: Index indicating long-term drying and the effect of extended drought on deeper organic layers.
- **Initial Spread Index (ISI)**: Indicator of the initial spread rate of a fire.
- **Buildup Index (BUI)**: Combines the DMC and DC indices to estimate the amount of fuel available for combustion.
- **Fire Weather Index (FWI)**: Comprehensive index predicting fire danger.
- **Classes**: Binary classification with values 'Fire' and 'Not Fire', representing the occurrence or absence of a fire.

### Second Dataset Description
- **Date**: Recorded in the format yyyy-MM-dd, indicating the observation day.
- **Temperature**: Atmospheric temperature in Celsius.
- **Rain**: Rainfall in millimeters.
- **Wd (Wind Direction)**: Wind direction in degrees (0 to 360).
- **Ws (Wind Speed)**: Wind speed in kilometers per hour.
- **Pres (Air Pressure)**: Atmospheric pressure in hectopascals (hPa).
- **RH (Relative Humidity)**: Humidity percentage.
- **Dew Point Max**: Maximum dew point temperature in Celsius.
- **Dew Point Avg**: Average dew point temperature in Celsius.
- **Dew Point Min**: Minimum dew point temperature in Celsius.
- **Classes**: Binary classification with values '1' (Fire) and '0' (Not Fire), indicating the presence or absence of fire based on environmental parameters.

## Project Structure
This repository contains two separate notebooks, each corresponding to the analysis of the two datasets described above. These notebooks include different interpretations, results, and detailed discussions on the methodologies applied.


- **Notebook 1**: Analysis of the first dataset, including data preprocessing, feature selection, and model building for wildfire prediction.
- **Notebook 2**: Analysis of the second dataset, exploring alternative approaches and additional environmental factors to enhance predictive accuracy.

## Conclusion
This project demonstrates the potential of data mining and machine learning techniques in predicting and preventing wildfires. By developing robust predictive models, we can contribute to more effective wildfire management strategies, reducing the risk of catastrophic events in regions like Bejaia.

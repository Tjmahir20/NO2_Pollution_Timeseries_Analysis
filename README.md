# NO2 Pollution Timeseries Analysis for Different Cities

## Project Overview

This project focuses on analyzing time-series data related to NO2 (nitrogen dioxide) concentrations in the troposphere, collected by the Ozone Monitoring Instrument (OMI) on NASA's Aura satellite. The aim is to study global NO2 trends, including seasonal variations and anomalies, across multiple years.

### Dataset Description

The dataset consists of daily global NO2 observations from 2004 to 2024. The primary variable of interest is the **ColumnAmountNO2Trop** (mean NO2 concentration in the troposphere). The data is provided by the OMI instrument, and more information can be found on the [KNMI project page](https://www.knmiprojects.nl/projects/ozone-monitoring-instrument) or the [NASA Aura website](https://aura.gsfc.nasa.gov/omi.html). Due to the larger size of the dataset, it was not included with this repository. Interested users can download similar datasets from the above mentioned websites.

### Key Tasks

1. **Global NO2 Mapping**
   - Generated a global map showing the long-term mean NO2 concentration.
   
2. **Yearly NO2 Anomalies**
   - Created global maps of mean yearly NO2 anomalies for selected years (2005, 2010, 2015, 2020).

3. **Regional NO2 Time-Series**
   - Plotted time-series data of daily NO2 concentrations for specific cities:
     - Enschede
     - New Delhi
     - Nairobi
     - Houston
     - Beijing

4. **Time-Series Decomposition**
   - Performed seasonal decomposition to understand trends and seasonality in NO2 levels across different regions.
  
This repository contains the results of an academic course assignment developed as part of the **Satellites for Geohealth Course** ([Satellites for Geohealth Course](https://studyguide.itc.nl/m-geo/all-courses/202300143/satellites-for-geohealth-?q=satelli)).

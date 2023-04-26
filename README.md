# DS-4002-Project3

## Contents of the Repository

This repository includes all of the necessary files related to the third DS 4002 project for our group, The Swifties B. This README.md file contains an overview of what is included in each of the three folders: SRC, Data, and Figures. The LICENSE.md file explains to a visitor the terms under which they may use and cite this repository. The SRC folder contains all source code for the project. The Data folder contains all of the data for the project. Lastly, the Figures folder contains all figures generated over the course of the project.

## SRC

### Installing/Building Code

We downloaded the data as a .csv file and cleaned it for use in R. Make sure the data is available and accessible in the same working directory as the file, and make any necessary changes to the file path in order for the dataset to be loaded into RStudio on your device.

### Using Code

This code can be used by opening the .Rmd file within RStudio, version 2022.12.

## Data

#### Data Dictionary

| Column Name | Data Type   | Description |
| ----------- | ----------- | ----------- |
| STATION     | String      | This column contains a string of the name of the station for the weather data. In this data set, all values in this column are “USC00441593”. |
| DATE        | String      | This column contains the date for each data point, ranging from “2008-03-30” to “2023-03-30”. Every value in this column should be unique. |
| PRCP        | Integer     | The precipitation, in inches, for that date. |
| SNOW        | Integer     | The snowfall, in inches, for that date. |
| SNWD        | Integer     | The snow depth, in inches, for that date. |
| TMAX        | Integer     | The observed temperature maximum for the day, recorded in Fahrenheit. |
| TMIN        | Integer     | The observed temperature minimum for the day, recorded in Fahrenheit. |
| TOBS        | Integer     | The temperature at the time of observation, recorded in Fahrenheit. |

#### Link to Data

Our dataset can be found [here](https://drive.google.com/file/d/1W32Mw8LcvxuTWM0gqHaSRfgvCCmPkCu0/view?usp=sharing), and was originally obtained from the NOAA website [1].

#### Relevant Notes About Data

Our data set comes from the National Oceanic and Atmospheric Administration (NOAA), where we were able to request daily weather data from a Charlottesville weather station (zip code 22904) over the last 15 years [1]. This data was sent to us via email in the format of a .CSV, containing 11 total columns. However, three of these columns are blank/full of NAs, so we have opted to drop them and not include them in the above data dictionary.

## Figures 

| Figure      | Description | Takeaways   |
| ----------- | ----------- | ----------- |
| HighTemperature_Decomposed.png| This graph includes the observed high temperature for each day in the training set, as well as the decomposition of the time series into its trend, seasonality, and random components.| This graph helps to explain how our Holt-Winters model works, as it utilizes the trend and seasonal components shown here to forecast the high temperature at future dates. |
| HighTempForecast.png| This graph includes the observed high temperature values in the the training set, as well as the forecasted values with confidence intervals for the test set.| This graph helps to explain how our forecast performed, as it shows the forecasted values for the test set are in line with what would be expected from the training set. |

## References

[1] National Oceanic and Atmospheric Administration, “Daily Summaries Location Details, ZIP 22904,” National Oceanic and Atmospheric Administration. [Online]. Available: https://www.ncei.noaa.gov/cdo-web/datasets/GHCND/locations/ZIP:22904/detail. [Accessed Apr. 5, 2023].

Our submission for M1 can be found [here](https://docs.google.com/document/d/1KtRkGcfcuY3WumVRNYGSjXVEUWk6gJ7HTOci15iLDM8/edit?usp=sharing).

Our submission for M2 is linked [here](https://docs.google.com/document/d/1_bvMRtwMolEkX2z_-Z1ZTqJKe3f7xxGh91NO3DkRolE/edit?usp=sharing).

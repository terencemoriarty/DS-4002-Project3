# DS-4002-Project3

## Contents of the Repository

This repository includes all of the necessary files related to the third DS 4002 project for our group, The Swifties B. This README.md file contains an overview of what is included in each of the three folders: SRC, Data, and Figures. The LICENSE.md file explains to a visitor the terms under which they may use and cite this repository. The SRC folder contains all source code for the project. The Data folder contains all of the data for the project. Lastly, the Figures folder contains all figures generated over the course of the project.

## SRC

We pulled the source data from Kaggle. It includes all of Taylor Swift's songs released during the time frame 2006-2017. It also includes the lyrics, song name, album name, and year of release.

### Installing/Building Code

We downloaded the data as a .csv file and cleaned it for use in R. Make sure the data is available and accessible in the same working directory as the file, and make any neccessary changes to the file path in order for the dataset to be loaded into RStudio on your device.

### Using Code

This code can be used by opening each .R or .Rmd file within RStudio, version 2022.12.

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

There are several significant notes about our dataset. Firstly, it is important to note that it only contains lyrics from Taylor Swift's first six albums, not her entire discography. This led to our group adjusting our hypothesis and research question accordingly. Additionally, it is important to note that the dataset breaks up lyrics by line in each song, so some data aggregation will be necessary in order to use each song as individual data points.

## Figures 

| Figure      | Description | Takeaways   |
| ----------- | ----------- | ----------- |
| Romance:CountryRatioGraph.png| This graph has each Taylor Swift song plotted with the year of release on the x-axis and it's romance-to-country ratio on the y-axis. It also includes a line of best fit.| The line of best fit having a positive slope confirms our hypothesis that the lyrics of Taylor Swift's songs have shifted from being more aligned with the country theme to more aligned with the romance theme. |

## References

[1] National Oceanic and Atmospheric Administration, “Daily Summaries Location Details, ZIP 22904,” National Oceanic and Atmospheric Administration. [Online]. Available: https://www.ncei.noaa.gov/cdo-web/datasets/GHCND/locations/ZIP:22904/detail. [Accessed Apr. 5, 2023].

Our submission for M1 can be found [here](https://docs.google.com/document/d/1KtRkGcfcuY3WumVRNYGSjXVEUWk6gJ7HTOci15iLDM8/edit?usp=sharing).

Our submission for M2 is linked [here](https://docs.google.com/document/d/1_bvMRtwMolEkX2z_-Z1ZTqJKe3f7xxGh91NO3DkRolE/edit?usp=sharing).

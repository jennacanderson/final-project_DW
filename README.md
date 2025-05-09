# final-project_DW

## Overview
An analysis of the relationship between weather and crime in Iowa City from January to March.

## Folder Structure
- data/: contains weather and crime data files
- code/: contains notebooks and scripts used for data processing and analysis
- project/: contains the written proposal and final report
  
## Data Dictionary

| Column Name        | Description                                                                 | Data Type   |
|--------------------|-----------------------------------------------------------------------------|-------------|
| Case Number         | Unique identifier for each crime incident                                  | Text        |
| Classification      | Type of crime reported (e.g., Theft, Assault)                              | Text        |
| Date/Time Occurred  | When the crime occurred                                                     | DateTime    |
| Date/Time Reported  | When the crime was reported                                                 | DateTime    |
| Location            | Location of the incident                                                    | Text        |
| Disposition         | Outcome or resolution of the case                                           | Text        |
| Date                | Date extracted from Date/Time Reported                                      | Date        |
| Time                | Time extracted from Date/Time Reported                                      | Time        |
| Time Bucket         | Time of day category (Morning, Afternoon, Evening, Night)                   | Categorical |
| DateTime            | Combined date and time (used for merging)                                   | DateTime    |
| Nearest Weather Time| Closest available weather observation time                                  | Time        |
| Temperature         | Temperature in degrees Fahrenheit                                           | Numeric     |
| Dew Point           | Dew point temperature in degrees Fahrenheit                                 | Numeric     |
| Humidity            | Relative humidity (%)                                                       | Numeric     |
| Wind                | Cardinal direction of wind (e.g., N, SW)                                    | Text        |
| Wind Speed          | Wind speed in miles per hour                                                | Numeric     |
| Wind Gust           | Wind gust speed in miles per hour                                           | Numeric     |
| Pressure            | Atmospheric pressure in inches of mercury                                   | Numeric     |
| Precipitation       | Precipitation in inches                                                     | Numeric     |
| Condition           | General weather condition (e.g., Clear, Rain, Snow)                         | Text        |
| Violent Crime       | Indicator for violent crime (1 = violent, 0 = non-violent)                  | Binary      |


## Sources
- [University of Iowa Crime Log](https://safety.uiowa.edu/crime-log#accordion-item-2146-3)
- [Weather Underground](https://www.wunderground.com/history/daily/us/ia/iowa-city)

## Author
Jenna Anderson  

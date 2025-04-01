# Data-Analysis-and-Visualization-of-India-Air-Quality

![](Images/Pollution(1).png)
![](Images/Pollution(2).png)
![](Images/Pollution(3).png)
![](Images/Pollution(4).png)

The purpose of this project is to analyze and visualize the data of Air Quality in India.

India has made it to the headlines when it comes to air pollution. The growing air pollution in the country has been one of the serious concerns for both the government and the citizens.


## Overview
This project analyzes air pollution data across different states and locations in India. The primary focus is on the concentration of air pollutants like SO2, NO2, RSPM, SPM, and PM2.5 over the years. The analysis includes data cleaning, transformation, and visualization to gain insights into the pollution levels in various regions.

## Key Features
- *Data Cleaning*: Handling missing data, converting dates, and filtering relevant data for analysis.
- *Statistical Analysis*: Utilized scatter plots to examine correlations between different pollutants (SO2, NO2, RSPM, etc.).
- *Heatmaps*: Visualized the distribution of pollutants across states and years using heatmaps.
- *Bar Plots*: Showed pollutant concentrations by location to identify regions with high pollution levels.

### Example Data

state            | location  | type        | so2  | no2  | rspm | spm | pm2_5 | date       | year
-----------------|-----------|-------------|------|------|------|-----|-------|------------|------
Andhra Pradesh  | Hyderabad | Residential | 4.8  | 17.4 | NaN  | NaN | NaN   | 1990-02-01 | 1990
Andhra Pradesh  | Hyderabad | Industrial  | 3.1  | 7.0  | NaN  | NaN | NaN   | 1990-02-01 | 1990


## Workflow
1. *Data Preprocessing*: The data was first cleaned by converting the date column to datetime format, and a year column was extracted. The data was filtered for valid years and missing values were handled.
   
2. *Visualization*:
   - *Heatmaps* were created to visualize the concentration of pollutants by state and year.
   - *Bar Plots* were generated to show the distribution of various pollutants (e.g., SO2, NO2, RSPM) across locations.
   - *Scatter Plots* were used to analyze correlations between pollutant concentrations.

3. *Insights*:
   - Some states like Delhi, Punjab, Uttar Pradesh, and Haryana were found to have high pollution levels, requiring immediate attention.
   - The analysis suggested a trend where states with high concentrations of RSPM also had high concentrations of SPM.
   - Heatmap analysis revealed that some states with severe pollution in the early years (1980-2000) have shown improvements over time, likely due to government policies and increased public awareness.

## Conclusion
This project provides valuable insights into the air pollution patterns across different regions of India, helping to identify areas that need more targeted interventions to improve air quality. Through the use of advanced visualization techniques like heatmaps and bar plots, it becomes evident where the major pollutants are concentrated and where progress has been made over the years.

## Dataset

The dataset contains the following features :

1. stn_code : Station code. A code given to each station that made the measurements.
2. sampling_date : The date when the data was recorded.
3. state : It represents the states whose air quality data is measured.
4. location : It represents the city whose air quality data is measured.
5. agency : Name of the agency that measured the data.
6. type : The type of area where the measurement was made.
7. so2 : The amount of Sulphur Dioxide measured.
8. no2 : The amount of Nitrogen Dioxide measured.
9. rspm : Respirable Suspended Particulate Matter measured.
10. spm : Suspended Particulate Matter measured.
11. location_monitoring_station : It indicates the location of the monitoring area.
12. pm2_5 : It represents the value of particulate matter measured.
13. date : It represents the date of recording (It is cleaner version of 'sampling_date' feature)

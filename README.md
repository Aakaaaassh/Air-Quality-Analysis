# Documentation: Air Quality Analysis Pipeline

## Introduction:
This documentation outlines the step-by-step process of analyzing air quality data for three cities: Delhi, Chennai, and Mumbai. The analysis includes data preprocessing, calculating Air Quality Index (AQI), visualizations, and generating reports.

## Step 1: Data Acquisition:
- Air quality data for Delhi, Chennai, and Mumbai was obtained from a reliable source.
- The dataset includes various pollutants such as PM2.5, PM10, SO2, NOx, NH3, CO, O3, and meteorological parameters.

## Step 2: Data Preprocessing:
- Timestamps were formatted for consistency.
- Missing values were handled appropriately using methods like interpolation or removal.

## Step 3: AQI Calculation:
- AQI calculation involves seven measures: PM2.5, PM10, SO2, NOx, NH3, CO, and O3.
- PM2.5, PM10, SO2, NOx, and NH3 averages for the last 24 hours were calculated.
- CO and O3 maximum values for the last 8 hours were calculated.
- Sub-Indices for each pollutant were computed based on predefined groups.
- Final AQI was determined as the maximum Sub-Index among the available indices.
- Conditions were applied to ensure the availability of necessary data points.

## Step 4: Data Visualization:
### 4.1 AQI Bucket Distribution:
- Bar plots were created to visualize the distribution of AQI buckets for each city.
- The number of data points falling into each AQI bucket was represented.

### 4.2 Time Series Plot for Pollutants:
- Line plots were generated to depict the time series of pollutant concentrations.
- Pollutants included PM2.5, PM10, SO2, and NOx.
- Trends and patterns in pollutant concentrations over time were observed.

### 4.3 Rolling Averages Plot:
- Line plots were generated to visualize 24-hour rolling averages of pollutants.
- PM2.5, PM10, SO2, and NOx rolling averages were plotted against timestamps.

### 4.4 Box Plot for Pollutants:
- Box plots were created to display the distribution of pollutant concentrations.
- PM2.5, PM10, SO2, and NOx concentrations were compared using box plots.

### 4.5 AQI Trend Plot:
- Line plots were generated to illustrate the trend of AQI over time for each city.
- AQI values were plotted against timestamps to visualize air quality trends.

## Step 5: Data Export:
- Processed data and visualizations were exported to Excel files for further analysis and reporting.
- Separate Excel files were created for each city, containing the processed data and AQI values.

## Conclusion:
This documentation outlines a comprehensive analysis pipeline for assessing air quality in Delhi, Chennai, and Mumbai. By preprocessing data, calculating AQI, visualizing trends, and exporting results, insights into air quality variations over time were gained.

---

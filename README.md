# IJC437 Sheffield Air Quality Analysis

This repository contains the coursework for the IJC437 Data Science module.
The project analyses daily NO₂ concentrations in Sheffield during 2023 and
their relationship with meteorological factors.

## Repository Structure

- `01_get_data.R`  
  Downloads raw air quality data from DEFRA UK-AIR and weather data from Open-Meteo.

- `02_clean_join.R`  
  Cleans, aggregates and joins air quality and weather data into daily summaries.

- `03_analysis_plots.R`  
  Performs exploratory data analysis, visualisation, and correlation analysis.

## How to Run the Code

1. Run `01_get_data.R` to download raw datasets.
2. Run `02_clean_join.R` to clean and merge the datasets.
3. Run `03_analysis_plots.R` to generate figures and analysis outputs.

## Data Sources

- DEFRA UK-AIR (air quality monitoring data)
- Open-Meteo Archive API (meteorological data)

## Author

Yunhan Zhang  
University of Sheffield

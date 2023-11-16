# Economic Data Analysis: Impact of COVID-19 on Labor Force Participation and Unemployment Rates

This project aims to analyze economic data from the United States, with a specific focus on the Labor Force Participation Rate and Unemployment Rate and their impact during the COVID-19 pandemic.

## Introduction

The project utilizes the FRED API (Federal Reserve Economic Data) to source relevant economic data. FRED is an extensive online database that provides access to a wide range of economic data time series.

## Project Phases

The project consists of the following phases:

1. **Creating the Fred Object**: Setting up the necessary tools to interact with the FRED API.
2. **Searching for Economic Data**: Identifying the relevant data series related to the Labor Force Participation Rate and Unemployment Rate.
3. **Pulling Raw Data**: Extracting the raw data from the FRED database using the API.
4. **Pulling and Joining Multiple Data Series**: Gathering and merging various data series to obtain a comprehensive dataset for analysis.
5. **Data Cleaning and Handling Missing Values**: Ensuring the data is in a usable format by addressing any inconsistencies or missing values.
6. **Data Visualization**: Utilizing Python libraries such as Matplotlib and Plotly Express to create visual representations of the data.

## Plots

The project includes the following plots:

- Overall Unemployment Rate Per State
- April 2020 Unemployment Rate Per State (during the COVID-19 pandemic)
- Unemployment Rate vs. Labor Force Participation Rate for each state in 2020 and 2021

## Requirements

To execute the code, you will need an API key from FRED. Obtaining a FRED API key is a simple process. Please follow the steps below:

1. Visit the [FRED API Key page](https://fred.stlouisfed.org/docs/api/api_key.html).
2. Log into your fredaccount.stlouisfed.org user account.
3. Request or view your API key. .

## Dependencies

The project relies on the following libraries:

- Pandas
- NumPy
- Matplotlib
- Plotly Express


## Conclusion

By following the outlined steps and utilizing the FRED API, Pandas, and NumPy libraries, this project provides insights into the economic data and visualizes the impact of the COVID-19 pandemic on the Labor Force Participation Rate and Unemployment Rate in the United States.

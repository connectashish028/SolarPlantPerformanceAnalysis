# Solar Power Plant Data Analysis

This repository contains a Jupyter Notebook exploring solar power generation data and its relationship with weather conditions. The analysis leverages key data science and visualization skills to gain insights into power output and yield.

## Project Overview

The notebook performs exploratory data analysis (EDA) and time series analysis on datasets from two solar power plants. 

## Key Skills and Implementation

* **Data Wrangling:**
    - Pandas is used extensively for data cleaning, manipulation, and aggregation. Examples include converting date/time formats, grouping data, and handling missing values.
* **Data Visualization:**
    - Matplotlib, Seaborn, and Plotly are employed to create informative visualizations such as histograms, line plots, box plots, and calendar plots. These visualizations help understand data distributions, patterns, and correlations.
* **Time Series Analysis:**
    - Statsmodels is utilized for time series decomposition, enabling the identification of trends and seasonality in ambient temperature data.

## Files

* **Solar_Data_Analysis.ipynb:** Jupyter Notebook containing the code and analysis.
* **Plant_1_Generation_Data.csv:** Dataset with power generation data for Plant 1.
* **Plant_1_Weather_Sensor_Data.csv:** Dataset with weather sensor data for Plant 1.

## Getting Started

1. **Clone the repository:** `git clone https://github.com/your-username/solar-power-analysis.git`
2. **Open the Jupyter Notebook:** Navigate to the repository and open `Solar_Data_Analysis.ipynb`.
3. **Install required libraries:** Ensure you have the necessary libraries installed (pandas, numpy, matplotlib, seaborn, plotly, statsmodels, scipy, holoviews, cufflinks).

## Analysis Highlights

* **Daily Yield:** Exhibits a strong correlation with time, peaking during daylight hours.
* **Ambient Temperature:** Shows a seven-day seasonality pattern.
* **Module Temperature:** Outliers identified on specific dates, warranting further investigation.

## Future Work

* Analyze data from Plant 2.
* Develop predictive models for yield based on weather conditions.
* Explore optimization strategies for power generation.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests.

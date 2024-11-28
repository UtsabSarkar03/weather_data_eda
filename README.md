Weather Data Exploratory Data Analysis (EDA) Project
Overview
This project focuses on performing exploratory data analysis (EDA) on weather data using Python and pandas. Through a series of calculations and queries, we extract meaningful insights about the weather patterns, analyze specific conditions, and compute statistical summaries for the dataset.

Objectives
Extract unique "Wind Speed" values in the dataset.
Determine the frequency of specific weather conditions (e.g., "Clear").
Analyze specific wind speed occurrences (e.g., "4 km/h").
Identify and handle null values in the dataset.
Rename columns to improve readability (e.g., renaming "Weather" to "Weather Condition").
Perform statistical analysis:
Calculate the mean visibility.
Compute the standard deviation of pressure.
Determine the variance of relative humidity.
Identify instances of specific weather conditions (e.g., "Snow").
Analyze specific weather scenarios:
Instances when "Wind Speed" > 24 and "Visibility" = 25.
Mean values of each column against different "Weather Conditions."
Minimum and maximum values of each column against "Weather Conditions."
Query specific conditions:
Instances when "Weather Condition" is Fog.
Instances when "Weather is Clear" or "Visibility" > 40.
Tools and Libraries Used
NumPy:
For numerical operations.
Pandas:
For data loading, manipulation, and analysis.
Jupyter Notebook:
To perform and document the analysis interactively.
Dataset
The dataset contains weather-related data, including various meteorological parameters such as temperature, pressure, visibility, wind speed, humidity, and weather conditions.

Features in the Dataset:
Wind Speed
Visibility
Pressure
Relative Humidity
Weather (renamed to "Weather Condition")
Dataset Source:
This dataset is publicly available and suitable for performing EDA.

Key Findings and Analysis
Unique "Wind Speed" Values:

Extracted all unique wind speed values to understand variability in the dataset.
Frequency of Clear Weather:

Identified the number of times the weather was reported as "Clear."
Occurrences of Specific Wind Speed (4 km/h):

Counted the occurrences when the wind speed was exactly 4 km/h.
Handling Null Values:

Checked and reported any null values in the dataset to ensure data quality.
Renamed Columns:

Renamed "Weather" to "Weather Condition" for better clarity.
Statistical Insights:

Mean Visibility: Computed the average visibility across all records.
Standard Deviation of Pressure: Measured variability in pressure readings.
Variance of Relative Humidity: Analyzed the spread in relative humidity values.
Instances of Specific Weather Conditions:

Identified all occurrences of "Snow."
Weather Scenarios:

Queried instances where wind speed > 24 and visibility = 25.
Aggregate Statistics:

Computed the mean, minimum, and maximum values of each column for every weather condition.
Fog Instances:

Extracted all records where the weather condition was "Fog."
Query on Clear Weather and High Visibility:

Found all instances where the weather was "Clear" or visibility was greater than 40.

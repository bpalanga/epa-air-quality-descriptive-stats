# EPA Air Quality: Descriptive Statistics

Descriptive statistics on EPA air quality data for carbon monoxide, done in Python as part of a Coursera data course. The notebook summarizes the center, spread and structure of the Air Quality Index (AQI) values across more than 200 monitoring sites.

## Notebook

* `epa_air_quality_descriptive_stats.ipynb`: loading the data, summary statistics with `describe()`, and calculating the mean, median, minimum, maximum and standard deviation of `aqi` with pandas and numpy

## What it covers

* Summary statistics for the `aqi` column
* Percentiles and what they show about where most readings fall
* State coverage in the data
* Calculating each statistic individually with numpy

## Key findings

* The `aqi` column has 260 values and none are missing
* The mean AQI is about 6.76 and the median is 5, so the distribution is right-skewed
* The 25th percentile is 2 and the 75th percentile is 9, so the middle half of readings sit between 2 and 9
* The minimum is 0 and the maximum is 50, so even the worst reading falls in the "Good" range (0 to 50)
* The standard deviation is about 7.06, larger than the mean, which reflects a few high readings against mostly low ones
* The data covers 52 unique state names, and California appears most often with 66 rows, about 25% of the data

## Tools

Python, pandas, numpy, Jupyter Notebook

## Data

c4_epa_air_quality.csv

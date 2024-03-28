# Importance and Scope

Operational Insights
- The analysis aims to offer operational insights into the workload and distribution of calls for service across different divisions, neighborhoods, and incident types.

Resource Allocation
- Understanding the frequency and nature of calls helps in efficient resource allocation, ensuring that the police department can respond effectively to different types of incidents.

Trend Identification
- By analyzing trends over time, the report helps in identifying recurring patterns, seasonal variations, and any emerging trends in calls for service.

Policy Decision Support
- Data-driven insights from the analysis can support policy decisions related to police deployment, response protocols, and community engagement strategies.



# Overview

This project involves analyzing police data to gain insights into various aspects of police events, including event counts, division details, neighborhood information, etc. The analysis encompasses descriptive statistics, exploratory data analysis (EDA), time series analysis, and visualization of trends and patterns.



# Analysis Goals Covered
## Descriptive Analysis: 
Descriptive statistics were computed for the 'EVENT_COUNT' variable to understand its central tendencies and variability.
## Temporal Analysis: 
Time series analysis was performed to analyze temporal trends and patterns in calls for service attended over time.
## Exploratory Data Analysis: 
Visualize numerical variable distributions with histograms and box plots. Explore categorical variables using bar charts.
## Time Series Analysis: 
Plot time series of event count. Resample data to daily frequency and analyze trends. Decompose time series into trend, seasonal, and residual components.

# Data Description

The data used for this analysis includes variables such as _id (unique identifier), EVENT_YEAR (year of the event), DIVISION_ORIGINAL (original division), DIVISION_FINAL (final division), HOOD_158 (hood information), NEIGHBOURHOOD_158 (neighborhood information), and EVENT_COUNT (count of events).

# Overall Analysis Steps

1. Data Loading and Preprocessing
   - Loaded the police data into a pandas DataFrame and performed data cleaning and formatting.

2. Descriptive Statistics
   - Computed basic statistics such as mean, median, mode, range, and standard deviation for numerical variables.

3. Exploratory Data Analysis (EDA)
   - Visualized distributions of numerical variables using histograms and box plots.
   - Plotted bar charts to explore categorical variables.

4. Time Series Analysis
   - Plotted time series of event count over time.
   - Resampled the data to daily frequency and analyzed trends.
   - Decomposed the time series into trend, seasonal, and residual components.

5. Visualization
   - Created various plots and visualizations using matplotlib and seaborn libraries.

# Code Usage

- "Calls for Service Attended.csv": Contains the raw data used for analysis.
- "Project.ipynb": Python script containing the code for data analysis.
- Dependencies: pandas, matplotlib, seaborn, numpy, scipy, statsmodels (for time series analysis).

# Result and Visualizations
![image](https://github.com/feven2965/Police-Annual-Statistical-Repport/assets/163018035/c58ac111-8eb5-4b54-9f29-76ff1a6d2656)

# Conclusion

The analysis provided valuable insights into the police data, including trends, distributions, and relationships between variables. Further analysis or modeling can be performed based on the findings to derive actionable insights.

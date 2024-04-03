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
![image](https://github.com/feven2965/Police-Annual-Statistical-Report/assets/163018035/863d5bc1-e379-4c0b-868d-fb7d32bec530)

![image](https://github.com/feven2965/Police-Annual-Statistical-Repport/assets/163018035/c58ac111-8eb5-4b54-9f29-76ff1a6d2656)


## Analysis Summary

Data Cleaning and Preprocessing
The initial steps involved cleaning the dataset by removing duplicates and handling missing values. This ensures that the analysis is based on accurate and complete information, thereby enhancing the reliability of the findings.

Outlier Detection
By calculating the Z-score for the 'EVENT_COUNT' column, outliers were identified and analyzed. This step is crucial for understanding extreme cases or anomalies in the data, which could have a significant impact on the overall analysis and interpretations.

Distribution Analysis
The analysis included exploring the distribution of various features, such as 'EVENT_YEAR', 'DIVISION_ORIGINAL', 'DIVISION_FINAL', 'HOOD_158', and 'NEIGHBOURHOOD_158'. The bar charts and histograms provided insights into the frequency and distribution patterns of these variables, helping to identify trends and areas of interest.

Neighborhood Analysis
The data was analyzed based on neighborhoods, with calculations for the mean, median, and standard deviation of 'EVENT_COUNT' for each neighborhood. This analysis highlights differences in event occurrences across neighborhoods, allowing for targeted approaches in addressing specific community needs.

Time Series Analysis
Utilizing time series analysis, including seasonal decomposition and forecasting with ARIMA models, revealed patterns and trends over time in the 'EVENT_COUNT'. This aspect of the analysis is vital for predicting future events and planning resource allocation effectively.

Correlation Analysis
The correlation matrix provided insights into the relationships between numerical variables. Understanding these correlations is essential for identifying factors that may influence event counts, contributing to a deeper understanding of the underlying dynamics.

## Conclusion
The comprehensive analysis of the dataset reveals significant insights into event occurrences, distributions across divisions and neighborhoods, and temporal trends. The preprocessing steps ensured a clean and reliable dataset, enabling accurate analysis. The outlier detection highlighted anomalies for further investigation. Distribution and neighborhood analyses shed light on spatial variations in event counts, offering a basis for targeted interventions. Time series analysis, including forecasting, offers a predictive perspective, essential for planning and resource allocation. Finally, the correlation analysis elucidates the interrelations among variables, suggesting areas for further exploration. Together, these findings provide a solid foundation for data-driven decision-making and strategic planning in addressing the needs highlighted by the event count data.



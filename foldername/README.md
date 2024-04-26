**Global Warming Power BI Project**

**Overview**

This Power BI project aims to visualize and analyze data related to global warming trends.
It includes interactive dashboards that explore various aspects of climate change, such as temperature anomalies, greenhouse gas emissions, sea level rise, and more.

**Stakeholders :**



**Source of Data :**

The data was taken from NASA. There are two dataset used in this project namely land and ocean temperature and CO2 measurement.

1.The first dataset consists of 3 columns namely Year, Smoothing and Lowess. **Year** : It consists year from 1958 to 2023. **Smoothing** refers to a technique used to reduce the noise or fluctuations in the temperature data. Imagine if the temperature readings have some random ups and downs due to various factors like weather patterns or measurement errors. Smoothing helps to average out these fluctuations, making the data easier to understand and analyze. **Lowess** stands for Locally Weighted Scatterplot Smoothing. It's a specific method used for smoothing data, particularly useful when dealing with scatterplots (which show individual data points). Lowess fits a smooth curve through the data points by giving more weight to nearby points and less weight to distant points. This helps in capturing the overall trend of the data while reducing the impact of outliers or noisy points.

The temperature are in degree celsius.

2.The second dataset consists of 7 columns namely  Year,	Month,	Monthly_Average,	De-Seasonlized,	Days,	std.dev of days and	unc. of mon mean. **Year** This column represents the year in which the CO2 data was recorded. It spans from 1958 to 2023, indicating the historical timeline of CO2 measurements. **Months** This column indicates the month within each year when the CO2 measurements were taken. It helps organize the data temporally, showing the variation in CO2 levels across different months.**Monthly_Average** This column represents the average concentration of CO2 recorded for each month throughout the years. It gives an indication of the typical CO2 levels observed during specific months across different years. **De-Seasonalized** This column likely contains the CO2 data after removing or adjusting for seasonal variations. Seasonal variations refer to the regular fluctuations in CO2 levels that occur due to natural factors such as changes in plant activity, temperature, and sunlight. De-seasonalizing the data helps reveal underlying trends or anomalies beyond seasonal patterns. **Days** This column might represent the number of days in each month for which CO2 measurements were taken. It provides information on data collection frequency and completeness for each month. **Std. Dev of Days** This column likely represents the standard deviation (a measure of data dispersion or variability) of the CO2 measurements taken within each month. It indicates the degree of variability or spread in the CO2 data for each month. **Unc. of Mon Mean** This column probably represents the uncertainty or error associated with the monthly average CO2 concentration. It provides a measure of the confidence or reliability of the reported monthly average values, accounting for factors such as measurement accuracy and variability.

The units of CO2 data is parts per million(ppm).

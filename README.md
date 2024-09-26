# Time Series Analysis of CPI, GDP, and Unemployment Rate (UNRATE)

This project involves time series analysis of three key economic indicators: the Consumer Price Index (CPIAUCSL), Gross Domestic Product (GDP), and the Unemployment Rate (UNRATE). These datasets provide valuable insights into the U.S. economy, and this analysis aims to explore trends, seasonality, and relationships between these variables over time.

## Datasets

- **CPIAUCSL**: Consumer Price Index for All Urban Consumers (CPI) from 1950 to the present.
- **GDP**: U.S. Gross Domestic Product (GDP) on a quarterly basis.
- **UNRATE**: U.S. Unemployment Rate (UNRATE) from 1950 to the present.

## Project Overview

This analysis focuses on the following aspects of the data:

1. **Data Cleaning and Preparation**:
   - Converting date columns to datetime format.
   - Merging the datasets on the `DATE` column.
   - Handling missing data in the GDP dataset.

2. **Time Series Visualizations**:
   - **Line Plot**: Visualizing the trend over time for CPIAUCSL, GDP, and UNRATE.
   - **Subplots**: Individual trends of CPIAUCSL, GDP, and UNRATE shown separately.
   - **Rolling Statistics**: Rolling mean and standard deviation to smooth the data and observe long-term trends.
   - **Correlation Heatmap**: Visualizing the correlation between CPIAUCSL, GDP, and UNRATE to check for relationships between variables.
   - **Monthly Averages**: Exploring seasonality in CPIAUCSL and UNRATE by calculating monthly averages.
   - **Pair Plot**: Pairwise relationships between CPIAUCSL, GDP, and UNRATE.
   - **Distribution Plots**: Histograms and KDE plots for visualizing the distribution of each variable.

3. **Descriptive Statistics**:
   - Summary statistics like mean, median, and variance for each of the indicators.
   - Correlation between the variables to understand their relationships.

## Key Insights

- **Trends**: Long-term trends in the CPIAUCSL, GDP, and UNRATE were visualized, revealing fluctuations in economic activity.
- **Volatility**: The rolling standard deviation was computed to understand periods of volatility in the CPIAUCSL data.
- **Correlations**: The correlation matrix shows the strength of the relationships between the economic indicators.
- **Seasonality**: Monthly average plots were created to observe any seasonality in CPIAUCSL and UNRATE.



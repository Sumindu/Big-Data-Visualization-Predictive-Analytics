# Big Data Visualization & Predictive Analytics

## Overview

This project focuses on visualizing large datasets and performing predictive analytics to understand traffic patterns. The primary objective is to analyze how different factors such as weather conditions and holidays impact traffic volume.

## Project Highlights

### Data Cleaning and Transformation

1. **Data Loading**: Loaded the dataset `Metro_Interstate_Traffic_Volume.csv` using Spark for efficient processing.
2. **Dataset url** - https://archive.ics.uci.edu/dataset/492/metro+interstate+traffic+volume
3. **Missing Values Handling**: Identified and handled missing values to ensure data quality.
4. **Categorical Transformation**: Transformed categorical variables (`weather_main`, `holiday`, `weather_description`) into numerical indices for better analysis.
5. **Duplicate Removal**: Identified and removed duplicate records to maintain data integrity.
6. **Data Sorting**: Sorted data by date and time to prepare for analysis and visualization.

### Data Visualization

1. **Historical Traffic Volume**: Plotted the historical traffic volume to visualize trends over time using Matplotlib.
2. **Scatter Plot**: Created scatter plots to show traffic volume over time, highlighting potential patterns or anomalies.
3. **Time Series Decomposition**: Decomposed the time series data to analyze trends and seasonality, providing insights into weekly patterns.
4. **Forecasting**: Utilized ARIMA models to forecast traffic volume for future dates, visualizing both historical and predicted traffic volumes.

### Predictive Analytics

1. **Summary Statistics**: Computed summary statistics for numerical columns such as temperature, rain, snow, cloud coverage, and traffic volume.
2. **Correlation Analysis**: Analyzed the correlation between different variables to understand their impact on traffic volume.
3. **Modeling**: Implemented machine learning models to predict traffic volume based on historical data and external factors like weather conditions.

### Kafka Integration

1. **Kafka Producer**: Implemented a Kafka producer to send real-time data to a Kafka topic.
2. **Kafka Consumer**: Developed a Kafka consumer to listen for messages from the Kafka topic and process the data.
3. **Extended Kafka Consumer**: Enhanced the Kafka consumer to include data processing and statistical analysis using Spark.

### Key Findings

- **Weather Impact**: Identified significant impacts of various weather conditions on traffic volume.
- **Holiday Effect**: Determined how holidays influence traffic patterns.
- **Trends and Seasonality**: Uncovered weekly patterns and trends in traffic volume through time series decomposition.
- **Forecast Accuracy**: Achieved reasonable accuracy in predicting traffic volume using ARIMA models.

This project demonstrates the application of big data technologies and predictive analytics to derive meaningful insights from large datasets.

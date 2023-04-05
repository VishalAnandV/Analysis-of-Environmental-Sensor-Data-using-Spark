## Analysis of Environmental Sensor Data using Spark

The goal of the project is to analyse air quality data captured from a network of small environmental sensors, using either the Apache Hadoop or Apache Spark data processing framework. The data can be accessed in JSON format from:
- Averaged data from last 24 hours for each sensor: https://data.sensor.community/static/v2/data.24h.json
- Averaged data from last 5 minutes for each sensor (for testing): https://data.sensor.community/static/v2/data.json

### Questions: 
- Identify the top 10 countries in terms of average air quality improvement over the previous 24 hours as well as the current averaged air quality indices of each. As far as possible use the country field in the sensor data to identify the country.

- Using the geo-coordinates from the sensor data, group the data into smaller regions using an appropriate clustering algorithm. Then determine the top 50 regions in terms of air quality improvement over the previous 24 hours.

- Calculate the longest streaks of good air quality (ie low index values) and display as a histogram. The histogram should have 20 buckets ranging from zero to the longest streak of good air quality. State the period over which the data was collected for the histogram.

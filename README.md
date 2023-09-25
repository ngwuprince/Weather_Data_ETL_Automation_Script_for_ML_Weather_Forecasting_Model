# Weather ETL Proof-of-Concept

*About Project* :
- As part of a predictive modeling project, I have developed a proof-of-concept (POC) for an Extract, Transform, Load (ETL) process to automate the extraction of daily weather forecast and observed weather data. The ETL process focuses on a single station and one data source, gathering actual and forecasted temperatures for Casablanca, Morocco, at noon local time.

Project Objectives:
- Download raw weather data using the wttr.in API.
- Extract relevant data for Casablanca's noon temperature and the following day's noon forecast.
- Transform and structure the data.
- Load the data into a tabular log file for analysis.
- Schedule the ETL process to run daily at a specified time.
In the future, we plan to expand this project to include multiple locations, forecasting sources, update frequencies, and additional weather metrics.

# Data Source
- I utilized the weather data package provided by the open-source project [wttr.in](https://github.com/chubin/wttr.in), a web service that offers weather forecast information in a text-based format.

This POC serves as a foundation for future enhancements, including additional locations, forecasting sources, update frequencies, and various weather metrics such as wind speed, precipitation, and visibility.

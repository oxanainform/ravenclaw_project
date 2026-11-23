# ravenclaw_project
This repository is for IronHack project for Ravenclaw Team 2026. 

The dataset includes two lookup tables: `bike_sharing_dataset/season.csv`
and `bike_sharing_dataset/weathersit.csv`. Join their `digit` columns to
the `season` and `weathersit` columns, respectively, in `day.csv` or
`hour.csv`. Their descriptions follow the dataset's original `Readme.txt`.

The Fact agency will investigate bike-sharing usage patterns in order to understanding and predicting bike-sharing demand

# Working title:
Urban Mobility Intelligence: Understanding and Predicting Bike-Sharing Demand

# Project Overview

Urban Mobility Intelligence & Demand Prediction is a data analytics project focused on understanding, analysing, and predicting urban bike-sharing demand.
The project uses historical bike-sharing data from Washington, D.C. (2011–2012), enriched with external datasets such as weather conditions, public holidays, and significant city events.
By combining relational database management, data engineering, exploratory data analysis, statistical methods, and machine learning, the project aims to identify the factors influencing bicycle rental behaviour and develop analytical tools that could support operational and strategic decision-making.
The ultimate goal is to transform historical mobility data into actionable insights for bike-sharing operators and urban mobility planners.

# Business problem:

Bike-sharing operators face several operational challenges:
* Demand fluctuates depending on weather, seasonality, time of day, and human behaviour.
* Unexpected events can significantly affect normal mobility patterns.
* Insufficient demand forecasting can lead to inefficient resource allocation.
* Understanding customer behaviour is essential for improving service availability and planning future operations.

The project addresses these challenges by analysing historical mobility patterns, identifying demand drivers, predicting future rental volumes, and detecting unusual changes in demand.nticipate demand, optimise bicycle availability, identify unusual changes in mobility patterns, and improve operational efficiency.

# Questions:
- Are there identifiable morning and evening commuting peaks?
- Do people use bikes differently on weekdays and weekends?
- Does the behaviour change between seasons?
- Are there specific hours when demand suddenly increases?
- Does bad weather affect commuting and recreational cycling differently?

# Expected Deliverables

The project is expected to produce:
* A structured MySQL database.
* Data ingestion and transformation scripts.
* Documented SQL queries and analytical procedures.
* Exploratory data analysis notebooks.
* Statistical analysis of mobility and environmental factors.
* Predictive demand forecasting models.
* Anomaly detection implementation.
* Interactive analytical dashboard.
* Final report with findings and business recommendations.

# Business Value
The proposed analytical solution aims to demonstrate how historical mobility data can support:
* Better understanding of urban transportation behaviour.
* Improved demand forecasting.
* More informed operational planning.
* Identification of unusual mobility patterns.
* Better understanding of environmental influences on transportation.
* Evidence-based urban mobility planning.

The project is intended as an analytical prototype rather than a production-ready bike-sharing management system.

# Project Limitations

Several limitations will be considered when interpreting the results:
* The primary dataset covers only 2011–2012.
* Rental records are aggregated hourly or daily.
* Station-level availability information is not included in the primary dataset.
* Historical external datasets may have different levels of temporal and geographic granularity.
* Correlations between external factors and rental demand do not necessarily establish causation.
* Predictive models trained on historical data may not generalise to present-day mobility patterns.

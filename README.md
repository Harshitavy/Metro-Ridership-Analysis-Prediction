#Project Overview

This project focuses on forecasting metro ridership using historical data from
the Delhi Metro dataset spanning the years 2022 to 2024. The dataset includes
time-stamped passenger information, enabling detailed analysis at both hourly
and daily levels. The initial phase of the project involves comprehensive
Exploratory Data Analysis (EDA), where key patterns such as peak travel hours,
weekday versus weekend variations, and seasonal trends are identified. Data
preprocessing steps such as handling missing values, formatting timestamps,
and feature extraction are performed to ensure the dataset is clean and suitable
for time-series modeling.

About the Dataset: 
The Delhi Metro is a rapid transit system serving the National Capital Region (NCR) of India. It plays a crucial role in reducing traffic congestion and providing sustainable public transportation to millions of passengers every day.
This dataset captures multiple performance indicators of the Delhi Metro network over time, including:
Total metro trips operated
Daily total passengers
Ticket revenue
Average passenger distance traveled per trip
Top stations based on passenger demand
Total stations operational

These data points help in analyzing metro usage patterns, operational efficiency, and transit demand in the region.

Visualization dashboards (e.g., Plotly/Dash, Power BI)

Data has been collected, cleaned, and aggregated using publicly available metro operational insights, news reports, and transit performance summaries released by the Delhi Metro Rail Corporation (DMRC).
File Details
Field	Description
Date	Date of operation
Total_Trips	Number of train trips operated on that day
Total_Passengers	Total ridership for that day
Total_Revenue	Ticketing revenue (₹ INR)
Avg_Fare	Revenue divided by passengers
Avg_Distance	Estimated average travel distance per passenger
Passengers_per_Trip	Ridership divided by number of trips
Revenue_Ticket	Ticket revenue per trip
Ticket_Type (optional)	Type of ticket or trip category
Top_Stations	Highest-demand stations on that day

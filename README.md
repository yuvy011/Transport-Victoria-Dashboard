# Public-Transport-Victoria-Dashboard
An interactive Power BI data analytics project exploring passenger movement and scheduled public transport services across Victoria.

The project combines passenger movement data with GTFS scheduled transport data to analyse demand patterns, service frequency, routes, stations, operating periods, and transport network activity.

## Dashboard Overview

The dashboard is divided into two pages:

### Page 01 — Passenger Demand Overview

The first page focuses on passenger movement and demand patterns.

It explores:

- Passenger movements over time
- Passenger movements by day type
- Passenger movements by hour
- Top destination stations
- Peak passenger movement hour
- Differences between weekdays, Saturdays, Sundays, and public holidays

Interactive filters allow users to explore the data by:

- Date range
- Day type

### Page 02 — Service & Network Operations

The second page focuses on the scheduled structure of Victoria's metropolitan train network.

It explores:

- Scheduled service activity by hour
- Scheduled services by route
- Scheduled services by day type
- Top stations by scheduled services

Interactive filters allow users to explore:

- Date range
- Day type
- Route

---

## Objective

To analyse Victoria's public transport network by combining passenger movement data with scheduled train service data, providing an interactive view of passenger demand and network operations.

The dashboard is designed to help users understand how passenger activity and scheduled services vary across time, day types, routes, and stations.

---

## Goal

The main goals of this project were to:

- Understand passenger movement patterns across Victoria's public transport network.
- Identify periods of higher and lower passenger activity.
- Analyse scheduled train service frequency throughout the day.
- Compare scheduled services across different routes.
- Identify stations with high scheduled service activity.
- Explore differences between weekday and weekend operations.
- Build an interactive Power BI dashboard that allows users to investigate these patterns.
- Develop practical experience working with large and relational datasets.

---

## Data

The project uses publicly available Victorian public transport and GTFS data.

https://opendata.transport.vic.gov.au/dataset/monthly-average-patronage-by-day-type-and-by-mode
https://opendata.transport.vic.gov.au/dataset/gtfs-realtime

https://opendata.transport.vic.gov.au/dataset/annual-regional-train-station-patronage-station-entries

The datasets contain information relating to:

- Passenger movements
- Passenger counts
- Stations
- Routes
- Trips
- Stop times
- Scheduled departure times
- Service calendars
- Calendar dates

The GTFS data is structured across multiple related tables rather than being provided as one single dataset.

Key tables used in the Power BI model include:

Fact_PassengerCounts
Fact_StopTimes

Dim_Routes
Dim_Trips
Dim_Stops
Dim_Calendar
Dim_CalendarDates
Dim_Date

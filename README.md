# Fly-Emirates-Airline-Performance
✈ U.S. Airline Performance Analysis

Tools: MySQL Workbench, Power BI, Excel

Duration: 2-Month Internship (Fly Emirates Theme)


---

📌 Project Overview

This project analyzes U.S. airline flight data to study:

Flight delays

Cancellations

On-time performance

Busiest airports

Delay reasons

Airline efficiency


The project was executed as part of a 2-month data analysis internship.


---

🛠 Tech Used

MySQL → Data cleaning, transformation, SQL joins, delay calculations

Power BI → KPI dashboard, charts, maps

Excel → Initial inspection

GitHub → Documentation



---

📂 Dataset

Contains:

airlines.csv – Airline codes and names

airports.csv – Airport information

flights.csv – 5M+ flight records including delays, cancellations, schedule, distance



---

🧹 Data Cleaning (SQL)

Performed:

Missing value handling

Time format conversion

Cancellation reason mapping

Created integrated view using JOINs

Added computed features

Created analytical view v_flight_analysis



---

📊 KPIs & Insights

Average arrival & departure delay

On-time performance % for each airline

Most delayed routes

Delay by day, month, airport

Top cancellation reasons

Busiest airports by traffic



---

📈 Dashboard Overview (Power BI)

Includes:
✔ Airline-wise delay trend
✔ Airport map visualization
✔ Monthly analysis
✔ Route-level performance
✔ Cancellation patterns
✔ KPI cards (Avg Delay, Total Flights, Cancellation Rate)


---

🧪 Sample SQL Queries

SELECT airline_name, AVG(ARRIVAL_DELAY) AS avg_delay 
FROM v_flight_analysis 
GROUP BY airline_name;

SELECT MONTH, AVG(ARRIVAL_DELAY) 
FROM v_flight_analysis 
GROUP BY MONTH;


---

🎯 Outcome

✓ Identified the most reliable airlines
✓ Found major delay factors
✓ Built a complete BI dashboard
✓ Improved understanding of real-world airline operations

#                                   Report on Data Analysis in a SQLite Database






## Introduction____

In this report, we present an analysis of a SQLite database related to travel. The database contains multiple tables, and we have conducted various data exploration and basic analyses to gain insights into the travel data.
Database Connection
We started by connecting to the SQLite database named 'travel.sqlite' and listing the tables present in the database. The tables available in the database are as follows:
'aircrafts_data'
'airports_data'
'boarding_passes'
'bookings'
'flights'
'seats'
'ticket_flights'
'tickets'







## Data Exploration____

We performed data exploration by examining the structure and content of each table:
**aircrafts_data:** This table contains information about aircraft.

**airports_data:** It provides details about airports.

**boarding_passes:** Information related to boarding passes.

**bookings:** This table includes data about flight bookings.

**flights:** Flight-related data.

**seats:** Information on seat availability in aircraft.

**ticket_flights:** Details of tickets associated with flights.

**tickets:** Information about tickets booked.

For each table, we also displayed the columns and their data types.







## Basic Analysis____

**Planes with More Than 100 Seats**:

We analyzed the number of planes with more than 100 seats in the **'seats'** table.


**Ticket Booking Trends:** 

We examined how the number of tickets booked and the total amount earned changed over time. This analysis was conducted by joining the 'tickets' and 'bookings' tables and visualizing the trends.


**Average Charges for Aircraft with Different Fare Conditions:** 

We calculated the average charges for each aircraft with different fare conditions, visualizing the results using a bar plot.


**Occupancy Rate Analysis:**

We analyzed the occupancy rate for each aircraft, including total revenue per year and the average revenue per ticket. Additionally, we calculated the average occupancy rate for each aircraft.


**Increase in Annual Turnover:** 

We estimated how the total annual turnover could increase by giving all aircraft a 10% higher occupancy rate. This was done by increasing the occupancy rate and calculating the resulting increase in total annual turnover.







## Conclusion____

This report provides a comprehensive overview of the data in the SQLite database related to travel. The analyses conducted reveal insights into seat availability, booking trends, fare conditions, and occupancy rates, which are essential for making informed decisions related to travel operations and revenue generation. Further, the report offers valuable information for optimizing the occupancy rates of aircraft to potentially increase total annual turnover.



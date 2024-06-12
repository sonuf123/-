

# Revenue Insights in Hospitality Domain Dashboard Project 

[Dashboard Link](https://app.powerbi.com/view?r=eyJrIjoiZmQ4MDM4NTAtODk2Yi00YjBkLWIxY2YtNzQ0NWY2YjY0NDM5IiwidCI6IjZhMTgyNzllLTgzMzktNGFhYS1hZDliLTViYjdjMmU4ZDE2YiJ9 "Dashboard Link")


## Purpose and Description

The purpose of this project is to analyze revenue-related metrics and booking trends in the hospitality domain using data from multiple tables including `fact_bookings`, `fact_aggregated_bookings`, `dim_date`, and `dim_rooms`. The project aims to derive actionable insights for stakeholders to optimize revenue, occupancy, and booking strategies.

### Data Extraction and Preparation

The project involves extracting data from the following tables:

- `fact_bookings`
- `fact_aggregated_bookings`
- `dim_date`
- `dim_rooms`

The data extraction process includes:

- Utilizing SQL queries to extract relevant data from the database.
- Cleaning and transforming data to prepare it for analysis.

### Key Metrics and Calculations

The project focuses on analyzing the following key metrics and performing calculations:

- **Revenue Metrics:**
  - Total Revenue Realized
  - Average Daily Rate (ADR)
  - Revenue Per Available Room (RevPAR)
  - Realization Percentage

- **Booking Metrics:**
  - Total Number of Bookings
  - Successful Bookings
  - Canceled Bookings
  - Checked Out Bookings
  - No Show Bookings

- **Occupancy Metrics:**
  - Occupancy Percentage
  - Daily Booked Room Nights (DBRN)
  - Daily Sellable Room Nights (DSRN)
  - Daily Utilized Room Nights (DURN)

- **Percentage Contribution Metrics:**
  - Contribution of Each Booking Platform to Total Bookings
  - Contribution of Each Room Class to Total Rooms Booked

- **Week Over Week (WoW) Change Metrics:**
  - Revenue Change Percentage
  - Occupancy Change Percentage
  - ADR Change Percentage
  - RevPAR Change Percentage
  - Realization Change Percentage
  - DSRN Change Percentage

### SQL Code and Steps

SQL queries are used extensively to perform data analysis and derive insights. Key SQL tasks include:

- Extracting data from multiple tables (`fact_bookings`, `dim_date`, `dim_rooms`).
- Calculating week numbers and identifying weekdays vs. weekends based on specific criteria.
- Aggregating data to calculate total revenue, bookings, occupancy, and other metrics.

### Power BI Dashboard Creation

The extracted and processed data is visualized using Power BI to create an interactive and dynamic dashboard. The dashboard includes:

- Visualizations for revenue trends, occupancy rates, booking distributions by platform and room class.
- Drill-down capabilities to analyze metrics at granular levels (e.g., daily, weekly).
- Performance indicators and KPIs to monitor key metrics over time.

## How to Use

1. **Data Extraction and Preparation:**
   - Ensure access to the database containing relevant tables (`fact_bookings`, `dim_date`, `dim_rooms`).
   - Use SQL queries to extract and transform data as described in the project requirements.

2. **Power BI Dashboard Creation:**
   - Import the cleaned and transformed dataset into Power BI.
   - Design interactive visualizations and implement calculated measures using DAX.
   - Create dynamic filters, slicers, and drill-throughs for exploring data insights.

3. **Analysis and Insights:**
   - Explore the dashboard to gain insights into revenue trends, booking patterns, and occupancy rates.
   - Use interactive features to analyze metrics based on specific time periods, booking platforms, or room classes.

4. **Actionable Recommendations:**
   - Leverage the derived insights to make data-driven decisions and recommendations for revenue optimization strategies in the hospitality domain.

<<Link from excel>>
<Link from power bi dashboard>

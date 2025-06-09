# Service Performance Optimization
# Customer Support Ticket Analysis 
This project presents a comprehensive analysis of a Customer Support Ticket Dataset, focused on deriving actionable insights related to service performance, customer satisfaction, and process optimization. It includes data cleaning, feature engineering in Python, and an interactive dashboard built in Tableau.

Objective:

Measuring ticket response and resolution times

Evaluating customer satisfaction patterns

Identifying delay contributors and operational inefficiencies

Enabling decision-makers to optimize customer service processes


# Technologies Used
Python (Pandas, NumPy) – for data cleaning and feature engineering

Tableau – for creating an interactive dashboard

Jupyter Notebook – for exploratory analysis and transformations

# Step 1: Data Cleaning
Removed leading/trailing whitespace from column names

Parsed datetime columns and added extra columns (Date of Purchase, First Response Time, Time to Resolution, Compalint Date)

Converted text-based timestamps to duration metrics (in hours)

# Step 2: Feature Engineering
Created several useful features including:

Response Delay (hrs): Time between ticket creation and first response

Resolution Delay (hrs): Time between ticket creation and resolution

SLA Breached: Boolean column indicating whether response exceeded SLA threshold (e.g., 24 hours)

Customer Segment: Combined age and gender for detailed segmentation

Extracted Purchase Day, Purchase Month, and Weekend Purchase flags

# Step 3: KPI Calculation

1. Total Tickets

2. Resolution Rate (%)

3. Avg. First Response Time

4. Avg. Time to Resolution

5. Avg. Customer Satisfaction Rating

# Step 4: Tableau Dashboard
[View the Tableau Dashboard](https://public.tableau.com/app/profile/isha.more/vizzes)



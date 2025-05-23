# Ola Data Analytics End to End Project 

## About
The Ola Project analyzes ride-hailing data using SQL for querying large datasets, Excel for data manipulation and cleanup, and Power BI for creating interactive reports and dashboards.

This project is divided into the following sections:
- **Data Extraction**: SQL queries are used to extract relevant data from databases (such as ride details, user information, etc.).
- **Data Cleaning**: Excel is used to clean and format the data before analysis.
- **Data Visualization**: Power BI is used to create insightful reports and dashboards for better business decision-making.

The goal is to understand trends, customer behavior, and operational patterns, such as peak hours, ride distribution, and customer demographics.
## Dataset Used
The dataset for this project 
- <a href = https://github.com/atifhassan630/OLA-Project/blob/main/Ola-data-file.xlsx> Dataset</a>
## Business Questions To Answer
## For SOL 
 1. Retrieve all successful bookings:
 2. Find the average ride distance for each vehicle type:
 3. Get the total number of cancelled rides by customers:
 4. List the top 5 customers who booked the highest number of rides:
 5. Get the number of rides cancelled by drivers due to personal and car-related issues:
 6. Find the maximum and minimum driver ratings for Prime Sedan bookings:
 7. Retrieve all rides where payment was made using UPI:
 8. Find the average customer rating per vehicle type:
 9. Calculate the total booking value of rides completed successfully:
  10. List all incomplete rides along with the reason:

- Solution of these problem <a href =https://github.com/atifhassan630/OLA-Project/blob/main/SQL_queries.SQL>SQl_Queries</a>
-  Create Database Ola_Use Ola(Through Views Database) <a href = https://github.com/atifhassan630/OLA-Project/blob/main/Create_Database_Ola_Use_Ola.sql >SQl_Queries </a>
 
 ## For Power BI 
 1. Ride Volume Over Time
 2. Booking Status Breakdown
 3. Top 5 Vehicle Types by Ride Distance
 4. Average Customer Ratings by Vehicle Type
 5. cancelled Rides Reasons
 6. Revenue by Payment Method
 7. Top 5 Customers by Total Booking Value
 8. Ride Distance Distribution Per Day
 9. Driver Ratings Distribution
  10. Customer vs. Driver Ratings

# Dashboard
<img src = "https://github.com/atifhassan630/Ola-Data-Analyst-Project/blob/main/Ola_Report-Overall.png" alt = "Overall-Report-view">
 <a href = https://github.com/atifhassan630/OLA-Project/blob/main/Ola_Report-Overall.pdf> Overall-Report</a> ||
 <a href = https://github.com/atifhassan630/OLA-Project/blob/main/Ola__Report-Vehicle_Type.pdf"> Vehicle_type-Report</a> ||
 <a href = https://github.com/atifhassan630/OLA-Project/blob/main/Ola_Report-Revenue.pdf> Revenue-Report</a> ||
 <a href = https://github.com/atifhassan630/OLA-Project/blob/main/Ola_Report-Cancellation.pdf> Cancellation-Report</a> ||
 <a href =https://github.com/atifhassan630/OLA-Project/blob/main/Ola_Report-Rating.pdf> Rating-Report</a> 


 
## Segregation of the views:
 1. Overall
 >1. Ride Volume Over Time
 >2. Booking Status Breakdown
 
 2. Vehicle Type
 >1. Top 5 Vehicle Types by Ride Distance

 3. Revenue
 >1. Revenue by Payment Method
 >2. Top 5 Customers by Total Booking Value
 >3. Ride Distance Distribution Per Day
 
 4. Cancellation
 >1. Cancelled Rides Reasons (Customer)
 >2. Cancelled Rides Reasons(Drivers)

 6. Ratings
 >1.Driver Ratings
 >2.Customer Ratings

 ##  Qestion to Answers:
 1. Ride Volume Over Time:
 > A time-series chart showing the number of rides per day/week.

 2. Booking Status Breakdown:
 > A pie or doughnut chart displaying the proportion of different
    booking statuses (success, cancelled by the customer, cancelled by the driver, etc.).
 
 3. Top 5 Vehicle Types by Ride Distance:
 > A bar chart ranking vehicle types based on the total distance covered.

 4. Average Customer Ratings by Vehicle Type:
 > A column chart showing the average customer ratings for different vehicle types.
 
 5. cancelled Rides Reasons:
 > A bar chart that highlights the common reasons for ride cancellations by customers and drivers.
 
 6. Revenue by Payment Method:
 > A stacked bar chart displaying total revenue based on payment methods (Cash, UPI, Credit Card, etc.).
 
 7 . Top 5 Customers by Total Booking Value:
 > A leaderboard visual listing customers who have spent the most on bookings.
 
 8 . Ride Distance Distribution Per Day:
 > A histogram or scatter plot showing the distribution of ride distances for different Dates.

 9 . Driver Rating Distribution:
 > A box plot visualizing the spread of driver ratings for different vehicle types.

 10. Customer vs. Driver Ratings:
 > A scatter plot comparing customer and driver ratings for each completed ride, analyzing correlations.
     
 ## Data Columns
 1. Date
 2. Time
 3. Booking_ID
 4. Booking_Status
 5. Customer_ID
 6. Vehicle_Type
 7. Pickup_Location
 8. Drop_Location
 9. V_TAT
 10. C_TAT
 11. cancelled_Rides_by_Customer
 12. cancelled_Rides_by_Driver
 13. Incomplete_Rides
 14. Incomplete_Rides_Reason
 15. Booking_Value
 16. Payment_Method
 17. Ride_Distance
 18. Driver_Ratings
 19. Customer_Rating

# Conclusion

## Problem Statement:
- Analyzed a 1-month dataset (40,000 rows) for Bengaluru to optimize ride bookings, reduce cancellations, and improve overall service performance.
-  Focused on improving customer satisfaction, operational efficiency, and revenue through data insights.

## Key SQL Queries & Insights:

- Achieved 62% successful bookings by identifying key factors affecting booking status and reducing cancellations by <7% (customer) and <18% (driver).
- Identified top 5 customers with the highest booking frequency and calculated the average ride distance for each vehicle type (Auto, Mini, Prime Plus, etc.).
- Analyzed cancellation reasons: Found that AC not working and driver moving away from pickup location were the top issues for 4-wheeler cancellations.
- Calculated the total booking value for successful rides and identified revenue trends with 70% of orders under 500 INR and 28% above 500 INR.
- Calculated the average customer and driver ratings for each vehicle type, enabling better quality control and improvement strategies.
- Tracked incomplete rides (less than 6%), identifying key issues like vehicle breakdowns and other reasons.

## Power BI Dashboards & Insights:
- Visualized ride volume over time and booking status breakdown, enabling targeted strategies for peak times like weekends and match days.
- Analyzed top 5 vehicle types by ride distance and average customer ratings per vehicle type, identifying high-performing segments.
- Tracked cancellation reasons and revenue by payment method, helping reduce cancellations and increase revenue from high-value bookings.
- Visualized customer vs. driver ratings to improve customer service and driver performance.

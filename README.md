# Data-Analytics-Uber-Trip-Analysis-And-Riding-Patterns-Dashboard-Using-Power-Bi
## 1. Objective
To analyze Uber trip data using Power BI and uncover riding behavior, booking trends, time patterns, location-based usage, and vehicle performance—helping stakeholders optimize operations, improve services, and enhance customer satisfaction.

## 2. Dataset Used
Data Source: Uber trip dataset in CSV format

Fields Included:

Trip ID, Date, Pickup Time

Vehicle Type (UberX, UberXL, etc.)

Payment Type (Uber Pay, Cash, etc.)

Passenger Count

Pickup/Drop-off Locations

Total Trip Distance

Total Booking Value

Total Booking Count

## 3. Business Questions Solved for Each Dashboard
### Overview Analysis
What is the total trip distance and booking value across all rides?

Which vehicle types contribute most to bookings and revenue?

What is the distribution of payment types?

Are trips more frequent during the day or night?

### Location Analysis
Which locations have the highest trip distances?

What are the most frequent pickup and drop-off locations?

Which cities contribute the most to total trip distance?

What is the farthest recorded trip route?

### Time Analysis
What is the distribution of trips by hour and day?

What time slots have the highest booking volumes?

How does trip distance and value vary across weekdays?

### Detail Grid
Can we view and filter individual trip records by date, location, or type?

What is the breakdown of fare, vehicle, and time for each trip?

## 4. Process (Step-by-Step)
Data Collection: Gathered raw Uber trip data in CSV.

Data Cleaning: Removed nulls, standardized date-time, validated fields.

Power BI Integration: Loaded dataset using Power Query and created data model.

Data Transformation: Calculated measures like total distance, avg value, etc.

Dashboard Design: Created 4 dashboards – Overview, Time, Location, Detail Grid.

Visualizations Used:

Cards, Pie charts, Donuts, Line/Area charts

Heatmaps, Bar graphs, DAX measures

Interactivity: Implemented slicers, filters, and page navigation.

## 5. Key Insights for Each Dashboard
### Overview Dashboard
UberX accounts for the highest total bookings and distance.

Uber Pay is the most preferred payment method (~66%).

Trips are more frequent during the day (60%) than night.

### Location Dashboard
Penn Station is the most common pickup location.

JFK and LaGuardia are major distance hubs.

Manhattan has the highest city-wise trip distance.

### Time Dashboard
Peak bookings occur between 4 PM to 7 PM.

Friday and Saturday are the busiest booking days.

Least activity is seen on early weekday mornings.

### Detail Grid
Total trip value: $1.6M+ with over 103K bookings.

Enables deep-level filtering and comparison by ID, vehicle, and time.

## 6. Recommendations for Each Dashboard
### Overview Dashboard
Focus promotions on UberX as it brings in the most value.

Encourage digital payments further to reduce cash handling.

Target night-time riders with safety-focused offers.

### Location Dashboard
Allocate more drivers near airports and Penn Station during peak hours.

Optimize routing in Manhattan and Brooklyn for high-efficiency zones.

### Time Dashboard
Increase driver availability on weekends and during evening hours.

Run off-peak discounts to balance traffic during low-demand hours.

### Detail Grid
Use trip-level data to track anomalies or unusually long/short trips.

Monitor high-value trips for loyalty program eligibility.

## 7. Conclusion
The Uber Trip Analysis Dashboard in Power BI delivers comprehensive insights into trip behavior, location trends, and time-based patterns. It helps decision-makers:

Improve fleet allocation and customer targeting

Optimize trip pricing and driver distribution

Enhance user experience by understanding peak demand and location trends

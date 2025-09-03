# Uber-Trip-analysis (Interactive Dashboard creation Using Power bi)
Built an interactive Power BI dashboard on Uber trips, analyzing bookings, revenue, trip efficiency, time, and location insights. Showcased KPIs like total/average bookings, value, distance &amp; time. Designed trends, demand patterns, top locations, vehicle preferences with slicers, heatmaps, drill-through, and export options.

## Dataset Used
<a href="https://github.com/Seelamavinash/Uber-Trip-analysis-Dashboard-/blob/main/Uber%20Trip%20Details.xlsx">Dataset</a>

## Dashboard Interaction
<a href="https://github.com/Seelamavinash/Uber-Trip-analysis-Dashboard-/blob/main/Uber%20Trip%20Analysis%20Dashboard.pbix">Dashboard</a>

## Data Modeling & Preparation
Cleaned & transformed raw Uber trip data in Power Query.
Built star schema model with relationships (including inactive Pickup–Dropoff link).
Created dynamic measures using a disconnected table (Total Bookings, Booking Value, Trip Distance).
## Dashboard 1: Overview & KPIs
Analyse Uber trip data using Power BI to gain insights into booking trends, revenue, and trip efficiency, helping stakeholders make data-driven decisions.
1.	Total Bookings – How many trips were booked over a given period?
2.	Total Booking Value – What is the total revenue generated from all bookings?
3.	Average Booking Value – What is the average revenue per booking?
4.	Total Trip Distance – What is the total distance covered by all trips?
5.	Average Trip Distance – How far are customers traveling on average per trip?
6.	Average Trip Time – What is the average duration of trips?
Expected Outcomes:
✔ Identify trends in ride bookings and revenue generation.
✔ Analyse trip efficiency in terms of distance and duration.
✔ Compare booking values and trip patterns across different time periods.
✔ Provide insights to optimize pricing models and improve customer satisfaction.
**CHART’s**
Create a Measure Selector using a Disconnected Table with the following values:
•	Total Bookings
•	Total Booking Value
•	Total Trip Distance
Then, use a measure to dynamically update the visualizations based on user selection.
By Payment Type (Card, Cash, Wallet, etc.)
By Trip Type (Day/Night)

**Additional Enhancements:**
	Dynamic Title – Update the chart title based on the selected measure.
	Slicers – Add filters for Date, City, and other interactive filters for deeper analysis.
	Tooltips – Show additional details like Average Booking Value or Trip Distance.
Vehicle Type Analysis - Grid View in Power BI
Create a grid table (matrix or table visual) to analyse key performance indicators like Total Bookings, Total Booking Value, Avg Booking Value, Total Trip Distance across different Vehicle Types in Uber trips.
Power BI Implementation:
	Use a Table or Matrix Visual to display Vehicle Type with the KPIs.
	Apply Conditional Formatting to highlight high and low values.
	Enable Sorting & Filtering for user interaction.
Total Bookings by Day
	Detecting trends and fluctuations in daily trip volumes.
	Identifying peak and off-peak booking days.
	Understanding the impact of external factors (holidays, events, weather) on ride demand.
	Supporting strategic planning for resource allocation and pricing adjustments.

**Location Analysis**
Understanding trip locations is crucial for optimizing ride distribution, demand forecasting, and operational efficiency. This analysis focuses on:
	Most Frequent Pickup Point
•	Identify the most common starting locations for trips.
•	Helps in optimizing driver availability and dynamic pricing strategies.
	Most Frequent Drop-off Point
•	Find the most common drop-off locations.
•	Requires activating an inactive relationship in Power BI between Pickup Location and Drop-off Location in the data model.
	Farthest Trip
•	Determine the longest trip based on distance travelled.
•	Useful for analysing outlier trips, long-distance demand, and fare optimization.
Total Bookings by Location (Top 5)
•	Identify the top 5 locations with the highest trip bookings.
•	Helps in demand forecasting and optimizing driver availability in high-traffic areas.
Most Preferred Vehicle for Location Pickup
•	Determine the most frequently booked vehicle type at each pickup location.
•	Supports strategic vehicle distribution based on customer preferences and location demand.

Other Implementation Enhancements for Uber Trip Analysis Dashboard
**Bookmark for Data Details**
•	Add a "Data Details" bookmark to display a pop-up or side panel explaining:
o	Meaning of key metrics (Total Bookings, Total Trip Distance, etc.).
o	Description of tables used in the analysis.
o	Data source and refresh frequency.
**Clear Slicer Button**
•	Add a "Clear Filters" button using a blank button with a Reset Slicers action to reset all selections in one click.
•	Improves user experience for quick dashboard resets.
**Download Raw Data Button** 
•	Add a button to export raw data in CSV or Excel format.
•	Use Power Automate or built-in Power BI Export functionality.
•	Enables users to analyse raw data outside Power BI if needed.

## Dashboard 2: Time Analysis
To understand trip patterns based on time, Uber needs to analyse ride demand and trends across different time intervals. This dashboard will help in optimizing operations, pricing, and driver availability.
Global Dynamic Measure (Filters All Charts)
A measure selector will be created for:
✔ Total Bookings
✔ Total Booking Value
✔ Total Trip Distance
This dynamic measure will update all visuals based on user selection.
Visualizations:
By Pickup Time (10-Minute Intervals) - Area Chart
•	Groups trip bookings into 10-minute intervals throughout the day.
•	Helps in identifying peak and off-peak demand periods.
By Day Name - Line Chart
•	Shows booking trends across Monday to Sunday.
•	Useful for analysing weekday vs. weekend demand.
By Hour and Time - Heatmap (Matrix Grid)
•	Rows: Hours of the Day (0–23)
•	Columns: Days of the Week (Mon-Sun)
•	Values: Selected Dynamic Measure (e.g., Total Bookings)
•	Highlights peak booking hours across different days.
## Dashboard 3:Trip Details
To provide in-depth insights and allow users to explore granular data, a Grid Tab will be created. This tab will enable drill-through functionality, allowing users to access detailed records based on selections made in other dashboards.
Features of the Grid Tab:
	Grid Table with Key Fields:
•	Displays essential trip details
	Drill-Through Functionality:
•	Users can right-click on a data point from other visuals (e.g., charts, heatmaps) and drill through to this Grid Tab.
•	Displays detailed records related to the selected data point.
	Bookmark for Full Data View:
•	A "View Full Data" bookmark to toggle between filtered drill-through data and the complete dataset.
•	Allows users to reset filters and see all records easily.

## 3. Enhancements
Dynamic titles based on selected measure.
Tooltips for Avg Booking Value & Trip Distance.
Clear slicer/reset button for better UX.
Raw data export (CSV/Excel via Power Automate).
## Expected Outcomes
Identify booking & revenue trends.
Analyze trip efficiency (distance & time).
Optimize pricing, driver allocation & resource planning.
Improve customer satisfaction with actionable insights.
 






# Uber-Trip-analysis (Interactive Dashboard creation Using Power bi)
Built an interactive Power BI dashboard on Uber trips, analyzing bookings, revenue, trip efficiency, time, and location insights. Showcased KPIs like total/average bookings, value, distance &amp; time. Designed trends, demand patterns, top locations, vehicle preferences with slicers, heatmaps, drill-through, and export options.
## Dataset Used
<a href="https://github.com/Seelamavinash/Uber-Trip-analysis-Dashboard-/blob/main/Uber%20Trip%20Details.xlsx">Dataset</a>

**DAHBOARD 1**: **OVERVIEW ANALYSIS**
## KPI’s
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
CHART’s
Create a Measure Selector using a Disconnected Table with the following values:
•	Total Bookings
•	Total Booking Value
•	Total Trip Distance
Then, use a measure to dynamically update the visualizations based on user selection.
By Payment Type (Card, Cash, Wallet, etc.)
By Trip Type (Day/Night)

Additional Enhancements:
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

Location Analysis
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
	Bookmark for Data Details 
•	Add a "Data Details" bookmark to display a pop-up or side panel explaining:
o	Meaning of key metrics (Total Bookings, Total Trip Distance, etc.).
o	Description of tables used in the analysis.
o	Data source and refresh frequency.
	Clear Slicer Button 
•	Add a "Clear Filters" button using a blank button with a Reset Slicers action to reset all selections in one click.
•	Improves user experience for quick dashboard resets.
	Download Raw Data Button 
•	Add a button to export raw data in CSV or Excel format.
•	Use Power Automate or built-in Power BI Export functionality.
•	Enables users to analyse raw data outside Power BI if needed.












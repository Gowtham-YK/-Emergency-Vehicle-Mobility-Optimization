# -Emergency-Vehicle-Mobility-Optimization
Analyze movement patterns of emergency vehicles (ambulance, fire, police) to identify delays, high-response-time zones, and optimal routing paths.
Key Visualizations  
Response time vs. zone  
Delay hotspots  
Suggested optimized response routes  
Time-of-day movement comparison

# 1.Purpose
This project works to help emergency vehicles reach the scene faster. It really reduces how long folks end up waiting for assistance in tough spots. The effort centers mostly on police cars along with fire trucks and ambulances. It examines their daily movements in detail. That approach lets them refine the usual routes these vehicles take. When the team studies the places and times of travel, they identify areas where responses drag on too slowly. They also pinpoint spots jammed up by constant traffic delays. Beyond that, the project offers improved routes to guide the vehicles better. Emergency crews get these sharper ways to decide on paths. As a result, the overall trips turn out much shorter. Public safety benefits from these kinds of steady gains in the long run.

# 2.Technologies Used
  i. Tableau
 ii. CSV / Excel
iii. Openstreet Map

# 3.Setup Instructions

1. Install Tableau

Make sure you have one of the following installed:

Tableau Desktop (recommended)

or Tableau Public (free)

2. Prepare Your Dataset

Ensure your emergency vehicle dataset (CSV/Excel) includes fields like:

Latitude and Longitude

Vehicle Type (Ambulance, Police, Fire)

Timestamps

Response Time

Station or Zone

Route or Trip ID (if available)

You can place it anywhere on your system. Tableau will connect to it directly.

3. Open the Tableau Workbook

Go to the project folder.

Open the file Emergency-Vehicle-Analysis.twbx (or your workbook name).

When Tableau loads, it may ask you to select the dataset again. Browse and connect to your CSV or Excel file.

4. Verify Geographic Fields

To make sure the map displays correctly:

Go to the Data Pane.

Right-click on Latitude, then choose Set Geographic Role and select Latitude.

Right-click on Longitude, then choose Set Geographic Role and select Longitude.

For Zone or Station Name, set it to:

Geographic Role: Area Name or District (or leave it as string if not mapping).

5. View the Dashboards

Open the dashboards included in the project, such as:

Response Time vs Zones

Delay Hotspots Map

Optimized Route Suggestions

Time-of-Day Movement Comparison

Each dashboard will automatically update based on your dataset.

6. (Optional) Connect to OpenStreetMap

Tableau uses OpenStreetMap by default for background maps. If it doesn't appear:

Go to Map, then Background Maps, and select Tableau.

Then select Map Layers and turn on Streets, Terrain, and Labels.

7. Interact With Visuals

# 4. Usage

Follow these steps to use the Emergency Vehicle Mobility Optimization dashboard effectively:

1. Load the Dataset

Open the Tableau workbook (.twbx file).

If prompted, reconnect your dataset (CSV/Excel) from Data Source.

Tableau will refresh all sheets and dashboards automatically.

2. Explore the Dashboards

The project includes several dashboards for different types of analysis:

Response Time vs Zone

Select a zone or station to view average response times.

Compare emergency types like Ambulance, Police, and Fire.

Delay Hotspots Map

View locations with significant delays on the map.

Hover over hotspots to see delay values and affected routes.

Use filters to switch between vehicle types.

Optimized Route Suggestions

Shows the recommended shortest and fastest routes.

Filter by vehicle type, time range, or zone.

Helps identify areas that consistently cause slowdowns.

Time-of-Day Movement Comparison

Compare movements during the morning, afternoon, evening, and night.

Identify time periods with the most congestion or delays.

This helps with shift planning and improving deployment.

3. Apply Filters and Interactions

You can interact with the dashboards using:

- Vehicle Type filter
- Time range slider
- Map zoom and pan
- Click to highlight routes or stations
- Tooltip insights for each point or hotspot

These interactions help you focus on specific data segments.

4. Export Reports

Tableau allows you to export:

- PDFs
- Images
- Crosstab data
- Packaged workbooks

Go to File and then Export to save reports for presentations or analysis.

5. Update With New Data

To analyze new emergency movement data:

Replace the old dataset file with the new one, keeping the same structure.

Open Tableau and refresh the data source.

All dashboards will update automatically.

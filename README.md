# Emergency Vehicle Mobility Optimization
Identify the movement patterns of emergency vehicles-ambulance, fire, and police-to highlight bottlenecks, high-response-time zones, and the routing paths that would be most efficient.
Key Visualizations
Response time vs. zone
Hotspot delays
Suggested optimized response routes
Time-of-day movement comparison

# I.Purpose


It aims to hasten the timely arrival of emergency vehicles at scenes. This really cuts down on the length of time one waits for aid during life's hard moments. The project focuses much on police cars, other emphases being fire trucks and ambulances. It studied their regular motions in great detail. That type of approach allows them to fine-tune the regular paths these vehicles take. When the team surveyed the times and places of travel, they realized where the responses dragged along a bit too slow. They also realized locations clogged up by constant delays in traffic. Other than this, the project provides better routing to the vehicles to further guide them. To this end, emergency crews get keen ways to decide on the paths. In this way, the general trips turn out to be much shorter. This kind of incremental gain benefits public safety in the long term.

# II.Technologies Used


i. Tableau

ii. CSV/Excel

iii. Openstreet Map

# III.Setup Instructions

# 1. Install Tableau

Make sure you have one of the following installed:

Tableau Desktop (recommended)

or Tableau Public (free)

# 2. Preparing Your Dataset

Your dataset of emergency vehicles in CSV/Excel format should at least have the following data columns:

Latitude and Longitude

Vehicle Type: Ambulance, Police, Fire

Timestamps

Response Time

Station or Zone

Route or Trip ID: If applicable

You can place it anywhere in your system and directly connect Tableau to it.

# 3. Open the Tableau Workbook

Go to the project folder:

Open the file Emergency-Vehicle-Analysis.twbx or your workbook name.

When Tableau opens, it may prompt you to select the dataset again. You can browse for your CSV or Excel file and connect to it.

4. Check geographic fields

For the map to work properly,

Go to the Data Pane:

Right click Latitude; select Set Geographic Role and choose Latitude.

Right-click the Longitude variable, choose Set Geographic Role and select Longitude.

For Zone or Station Name, input

Geographic Role: Area Name or District (or leave as string if not mapping).

# 5. View the Dashboards

Open the following dashboards included in the project:

Response Time vs. Zones

Delay Hotspots Map

Optimized Route Suggestions

Time-of-Day Movement Comparison

Each of these dashboards will refresh automatically when your dataset refreshes.

# 6. (Optional) Connect to OpenStreetMap


Tableau uses OpenStreetMap for background maps by default. If you don't see it:

Click on Map, then Background Maps, and select Tableau.

Then, under Map Layers check the boxes for Streets, Terrain, and Labels.

7. Chart and Graph Interactions

# IV. Usage

To use the Emergency Vehicle Mobility Optimization dashboard, follow these steps:

# 1. Load the Dataset

Open Tableau workbook (.twbx file)

If you have been prompted, reconnect your dataset CSV/Excel from Data Source.

Tableau will refresh all sheets and dashboards automatically.

# 2. Explore the Dashboards

Various types of analysis have been visualized in diverse dashboards within this project.

Response Time vs Zone

Please choose a zone or station to see average response times.

Now, let's compare the types of emergencies: Ambulance, Police, and Fire.

Hotspots Delay Map

See areas of significant delay on the map.

Mouse over hotspots to see delay values and affected routes.

Switch between vehicle types using filters.

Optimized Route Suggestions

Displays the suggested shortest and fastest routes.

Filter by vehicle type, time range or zone.

Allows identification of those places that always delay processes.

Time-of-Day Movement Comparison
Describe the movement in the morning, afternoon, evening, and night.

Identify time periods which are most congested or delayed.

This helps in shift planning to improve deployment.

# 3. Apply Filters and Interactions

You can interact with the dashboards using:

Vehicle Type filter

- Time range slider

Zoom and pan within the map

- Click to highlight routes or stations

- Tooltip details for every point or hotspot

These interactions help you focus on particular segments of data. # 4. Export Reports Tableau allows you to export: - PDFs - Images Output- Crosstab data - Packaged workbooks Click on 'File', then 'Export' to save the reports for presentations or analysis. 5. Refresh with new data To analyze new emergency movement data: Replace the old dataset file with the new one, maintaining the same structure. Open Tableau and refresh the data source. All the dashboards will refresh automatically.

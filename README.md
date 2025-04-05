**Project Goal:**

The aim of this project is to analyze and understand a dataset related to street lighting. The project helps identify patterns and trends such as:

Types of street lamps being used

How many are functional or non-functional

Installation timelines

Power consumption

Geographic distribution (if coordinates are provided)

**Dataset Used:**

Name: Street_Lighting.csv

Contains Information Like:

Lamp type (e.g., LED, Sodium, etc.)

Wattage or power usage

Status (working or not)

Installation date

Location (latitude and longitude if available)
Technologies and Tools Used:
**Programming Language:**
Python – Chosen for its powerful data analysis and visualization capabilities.

**Libraries:**

Pandas: For reading and processing tabular data (like CSV files).

Matplotlib & Seaborn: For creating visual charts and graphs.

Folium (Optional): For showing street lights on an interactive map.

Jupyter Notebook / VSCode: Used as the development environment for coding and viewing results.

**Modules of the Project:**

**1. Data Loading & Cleaning Module**

This part handles reading the CSV file and preparing the data.

Fixes column names, handles missing or incorrect values, and formats dates.

**2. Data Analysis Module**

Examines the dataset to find out:

How many of each type of lamp are present.

How many lamps are working or faulty.

Average power consumption by lamp type.

Which years saw the most installations.

**3. Visualization Module**

Converts the analysis into easy-to-understand visuals like:

Bar charts (lamp types, yearly installations)

Pie charts (lamp status: working vs. not working)

Line charts (power trends over time)

Interactive map (to show where lamps are located)

**Functional Highlights:**

Lamp Type Analysis: Identifies which types of lights are most used in the city.

Status Breakdown: Shows the percentage of working and non-working lights.

Power Usage: Compares the wattage used by different lamp types.

Installation Trends: Reveals which years had the most installations.

Geographic Mapping (optional): Plots street lights on a map using location data.

**Expected Outcomes:**

A clear understanding of street lighting infrastructure.

Graphical representations of trends and issues.

Insights that could help city planners make better lighting decisions.

(Optional) An interactive map showing lamp distribution.

**Applications and Use Cases:**

City infrastructure planning

Identifying areas needing maintenance

Replacing inefficient lamp types with energy-saving ones

Creating a dashboard for real-time monitoring

**Conclusion:**

This project gives a complete overview of how Python and its libraries can be used to process and analyze real-world datasets. It shows how meaningful insights can be extracted from raw data, especially for public utility planning like street lighting.

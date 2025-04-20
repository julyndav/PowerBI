# Tracking Tornadoes
A comprehensive, interactive Power BI dashboard exploring tornado activity across the continental U.S. over a 22-year period. Designed to provide both high-level overviews and detailed state-specific insights into tornado frequency, damage, injuries, and fatalities.
<br></br>

## Table of Contents:
[Interactive PowerBI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNjUwNzFiYjktYWMyNy00OGViLTllNzQtZWEzN2M4ZjY0YzdkIiwidCI6ImI4OTBlNWMxLTg4YzQtNDQ4MC1hM2E1LTA2MGVlOTI2MjZmMCJ9&embedImagePlaceholder=true&pageName=00b11b586c5acfc879bc)<br>
[Data Source](https://www.spc.noaa.gov/wcm/#data)


### Skills Used
<ul>
<li>Data extraction and loading (Python)</li>
<li>Data cleaning (Power Query)</li>
<li>Calculated Columns (DAX)</li>
<li>Dashboard design (Canva)</li>
<li>Data Visualisation(PowerBI)</li>
</ul>

## About this project:
Submission for Microsoft PowerBI DataViz World Championship (2025)

#### Objective:
Create an Infographic style PowerBI dashboard to inform the viewer of the dangers and toll that tornadoes cause: 
<ul>
<li>Identify the main destructive trends</li>
<li>Create a heatmap to show tornado intensity by state</li>
<li>State specific analysis</li>
<li>Time interval trends by year and time of day</li>
</ul>
<br></br>

# Analysis Process:

### Reviewing and Processing the Data:
<ul>
<li>Data was downloaded from the National Oceanic and Atmospheric Administration website.</li>
<li>Loaded data into Python to exlpore, clean and transform as needed.</li> 
<li>Dataset was filtered for the years of 2000-2022.</li>
<li>Data was then extracted from Python into a CSV file for analysis</li>
<li>Loaded the cleaned dataset into Power BI.</li>
</ul>  
<br></br>

# Dashboard
### Dashboard Concept:
<ul>
<li>Aimed for a simple, 2 page design.</li>
<li>Designed the overall aesthetic and layout to ensure a user-friendly interface. The background and icons were designed and exported from Canva.</li>
</ul>
<p></p>


## Main Page

#### First Section:
<ul>
<li>Displays overal tornado statistics.</li>
<li>Other than the map graphic, clicking a graphic detail will not filter the data. That functionality was removed.</li>
<li>The map graphic incorporates 'Drill through' options. Hovering over a state, will all the viewer to filter the data to that state.</li>
</ul>
<p></p>

![MainDB](https://github.com/julyndav/PowerBI/blob/main/Tracking_Tornadoes/Images/Dashboard.png)
<br></br>

#### Second Section:
<ul>
<li>Displays general ticket information: quantity, purchase methods, monthly ticket totals, and average price.</li>
<li>Highlights the number of stations covered, with a focus on the top 3 departure and arrival stations, their on-time performance, and revenue.</li>
<li>KPIs and visuals to provide a summary of other key metrics.</li>
</ul>
<p></p>

![MainDB_2ndPg](https://github.com/julyndav/PowerBI/blob/main/Tracking_Tornadoes/Images/Main_Dashboard_2.png)




### Overview Insights: 
<b>EF Scale Magnitude:</b>
Less than 0.1% of all recorded tornadoes reach EF5, the highest and most destructive rating on the Enhanced Fujita Scale. Out of the <b>28K</b> reported tornadoes, only <b>9</b> were EF5 level. Tornadoes of this magnitude are extremely rare but incredibly devastating, capable of leveling entire towns and stripping the landscape bare. The sheer force of an EF5 tornado includes estimated wind speeds exceeding 200 miles per hour, strong enough to tear asphalt from roads and hurl vehicles like projectiles. Such intense storms require an exceptionally rare combination of atmospheric conditions—strong wind shear, extreme instability, and ample moisture—making them far less common than lower-rated tornadoes 

<b>Property Damage:</b>
Regions or states that are not typically exposed to severe weather events—such as tornadoes—often experience high levels of property damage when such events do occur. This could be due to a combination of factors, including infrastructure that is not built to withstand extreme weather, a general lack of preparedness among residents and local authorities, and limited early warning systems. From the below graphic, we can see how destructive the various intensities can be regardless of how often they occur.<p>
![Damage](https://github.com/julyndav/PowerBI/blob/main/Tracking_Tornadoes/Images/PropertyDamage.png)
</p>
<br></br>

## State Specific Dashboard

#### First Section:
<ul>
<li>From the Main Page, hovering over a state will allow the user to 'Drill through' and select 'Expanded_State_information'.</li>
<li>All information on the page pertains to the selected state.</li>
<li>Viewer can return to the Main pg by selecting the back arrow at the top of the dashboard.</li>  
</ul>
<p></p>

![MainDB](https://github.com/julyndav/PowerBI/blob/main/Tracking_Tornadoes/Images/StatePg1.png)
<br></br>

#### Second Section:
<ul>
<li>The chart illustrates the frequency of tornadoes throughout the day, revealing that most occur during the late afternoon and early evening hours.</li>
<li>Note that not all of the states will experience every level of tornado intensity.</li>
<li>Feel free to return to the main page and explore other states.</li>
</ul>
<p></p>

![MainDB](https://github.com/julyndav/PowerBI/blob/main/Tracking_Tornadoes/Images/StatePg2.png)
<ul>
<li>DAX was used to extract 'hour' from tornado start times into a new column and used for the time analysis graphic.</li>
</ul>
<br></br>

#### Third Section:
<ul>
<li>The final section of the state specific analysis deals with distance and effects of tornadoes.</li>
<li>DAX was used to calculate the miles a particular tornado has traveled using the starting and ending longitudes and latitudes.</li>
<li>Depending on the duration of the tornado, it can rise and fall multiple times depending on it's strength. Each instance of it </li>
</ul>
<p></p>

![MainDB](https://github.com/julyndav/PowerBI/blob/main/Tracking_Tornadoes/Images/StatePg3.png)
<li>Tornadoes can vary in strength and duration as they move, sometimes touching down, lifting, and then touching down again. Because of this behavior, a single tornado event can cover significant distances, even if it isn’t continuous. Additionally, multiple tornadoes may occur on the same day, often as part of a larger outbreak. The distances shown represent the total ground path covered across the state on that day, based on recorded start and end coordinates of each event.</li>
<br></br>








### Revenue Recommendations:
<b> ...</b>
this analysis could be usefull for local or state officals to advocate more preventive and safety measures such as public storm shelters, warning sirens

1) 
<br></br>
<br></br>



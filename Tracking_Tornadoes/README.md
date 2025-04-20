# Tracking Tornadoes
A comprehensive, interactive Power BI dashboard exploring tornado activity across the continental U.S. over a 22-year period. Designed to provide both high-level overviews and detailed state-specific insights into tornado frequency, damage, injuries, and fatalities.
<br></br>

## Table of Contents:
[Interactive PowerBI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNmY5NTliYzYtNWZjMS00OGVkLTk2NDctZWFhNmNlYTMyZjQ2IiwidCI6ImI4OTBlNWMxLTg4YzQtNDQ4MC1hM2E1LTA2MGVlOTI2MjZmMCJ9&embedImagePlaceholder=true&pageName=921abace809859bddd06)<br>
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
<li>Displays general ticket information: quantity, purchase methods, monthly ticket totals, and average price.</li>
<li>Highlights the number of stations covered, with a focus on the top 3 departure and arrival stations, their on-time performance, and revenue.</li>
<li>KPIs and visuals to provide a summary of other key metrics.</li>
</ul>
<p></p>

![MainDB](https://github.com/julyndav/PowerBI/blob/main/Tracking_Tornadoes/Images/StatePg1.png)
<br></br>

#### Second Section:
<ul>
<li>Displays general ticket information: quantity, purchase methods, monthly ticket totals, and average price.</li>
<li>Highlights the number of stations covered, with a focus on the top 3 departure and arrival stations, their on-time performance, and revenue.</li>
<li>KPIs and visuals to provide a summary of other key metrics.</li>
</ul>
<p></p>

![MainDB](https://github.com/julyndav/PowerBI/blob/main/Tracking_Tornadoes/Images/StatePg2.png)
<br></br>

#### Third Section:
<ul>
<li>Displays general ticket information: quantity, purchase methods, monthly ticket totals, and average price.</li>
<li>Highlights the number of stations covered, with a focus on the top 3 departure and arrival stations, their on-time performance, and revenue.</li>
<li>KPIs and visuals to provide a summary of other key metrics.</li>
</ul>
<p></p>

![MainDB](https://github.com/julyndav/PowerBI/blob/main/Tracking_Tornadoes/Images/StatePg3.png)
<br></br>








### Revenue Recommendations:
<b> Improve Technical and Staffing Reliability:</b>
Implement a rigorous maintenance schedule to minimize technical issues. Conduct regular training sessions and improve the staffing process to ensure that adequate staff is available, especially during peak times. Invest in better monitoring and early detection systems to quickly address technical problems before they impact service.

<b> Refund/Delays:</b>
Enhance the communication system to inform passengers promptly about weather-related delays and offer alternative options to reduce the impact.
Consider offering flexible rescheduling options rather than refunds to retain revenue.

<b> Ticket Recommendations:</b>
1) Improve the user experience on the online ticketing platform to make it more intuitive and faster.
2) Provide a seamless mobile experience to cater to on-the-go customers.
3) Offer exclusive online discounts or loyalty points to encourage more online purchases.
4) Offer early bird discounts for passengers who book tickets well in advance.
5) Provide additional benefits for advance purchasers, such as seat selection or free Wi-Fi.
6) Railcard: Reevaluate the discount railcard program to understand why it is underutilized. Simplify the process of acquiring and using the discount railcard.
   Promote the benefits of the discount railcard through targeted marketing campaigns.
<br></br>
<br></br>



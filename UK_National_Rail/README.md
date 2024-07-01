# UK National Rail Analysis
<br>

## Table of Contents:
[Interactive PowerBI Dashboard](https://mavenanalytics.io/project/15152)<br>
[Data Set](https://github.com/julyndav/Business_Analytics/tree/main/cohort_images)
<br></br>
## About this project:

### Project Rundown
#### Objective:
Create an exploratory dashboard that helps analyze traveler behavior and operating performance.
<ul>
<li>Identify the most popular train routes</li>
<li>Determine peak travel times</li>
<li>Analyze revenue from different ticket types & ticket classes</li>
<li>Diagnose on-time performance and contributing factors</li>
</ul>
<br>


## Analysis Process:
### Reviewing the Data:
<ul>
<li>Reviewed the provided data consisting of two CSV tables: one with working data and another with variable information.</li>
<li>Imported the working data into Power BI for initial data cleaning, formatting, and manipulation.</li>
</ul>  
<p>
  
### Processing Data:
<ul>
<li>Formatted currency and date columns.</li>
<li>Reviewed each column’s variables, consolidating the 'Reason for Delay' column to unify various delay reasons.</li>
<li>Ensured data consistency and accuracy through cleaning and validation processes.</li>
</ul>
<p></p>
  
### Dashboard Concept:
<ul>
<li>Outlined key metrics and potential visuals, dividing the dashboard into four main sections based on the initial requirements.</li>
<li>Designed the overall aesthetic and layout to ensure a user-friendly interface. The background and icons were designed in PowerPoint.</li>
</ul>
<p></p>

### Data Analysis and Exploration:
<ul>
<li>Created a ‘Measures’ table to store DAX calculations for data analysis.</li>
<li>Utilized various sorting/grouping DAX expressions for more detailed graphics.</li>
</ul>
<br>

## Dashboard
### Overview Page:
<ul>
<li>Displays general ticket information: quantity, purchase methods, monthly ticket totals, and average price.</li>
<li>Highlights the number of stations covered, with a focus on the top 3 departure and arrival stations, their on-time performance, and revenue.</li>
<li>KPIs and visuals to provide a summary of other key metrics.</li>
</ul>
<p></p>

![MainDB](https://github.com/julyndav/PowerBI/blob/main/UK_National_Rail/Images/UKRail%20Img1.png)
<br></br>

### Route Overview:
<ul>
<li>Showcases ticket classes, highlight the main reasons for delays and refunds totals per ticket class.</li>
<li>Features an interactive route map and a general timeline to visualize passenger patterns over a 24-hour period.</li>
</ul>
<p></p>

![RouteOv](https://github.com/julyndav/PowerBI/blob/main/UK_National_Rail/Images/Route_Overview.png)
<br></br>


### Departures:

Visualizations exclude canceled trips to provide a clearer picture of actual departures.
Identifies peak travel times: 6-8am and 4-6pm, influenced by commuters and possible students.
Breaks down ticketing by station.
Uses tooltips to display additional information for a more detailed coverage without cluttering the visuals.


### Arrivals:

Similar layout to Departures but focuses on average delay times and performance issues.
Examines trip delays, on-time percentages, and cancellations.
Analyzes station-specific delays to highlight where performance improvements can be made.



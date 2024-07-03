# UK National Rail Analysis
Led comprehensive data analysis using Power Query and Power BI to uncover key rail passenger trends and station metrics. Extracted and processed
30k+ passenger records from Maven Analytics, focusing on improving data quality and transforming insights into actionable recommendations. 
Developed an interactive Power BI dashboard to visualize critical metrics including train routes, peak travel times, ticket revenue, 
station performance, and passenger behavior. Delivered insights and feasibility study recommendations to support potential rail expansion initiatives.
<br></br>

## Table of Contents:
[Interactive PowerBI Dashboard](https://mavenanalytics.io/project/15152)<br>
<br></br>
## About this project:

### Challenge Project Rundown
#### Objective:
As a BI Developer for National Rail, a company that provides business services to passenger trains operatored in England, Scotland, and Wales, 
create an exploratory dashboard that will: 
<ul>
<li>Identify the most popular train routes</li>
<li>Determine peak travel times</li>
<li>Analyze revenue from different ticket types & ticket classes</li>
<li>Diagnose on-time performance and contributing factors</li>
</ul>
<br>


# My Analysis Process:


### Reviewing the Data:
<ul>
<li>Reviewed the provided data consisting of two CSV tables: one with working data and another with variable information.</li>
<li>Loaded the working data into Power BI for initial data cleaning, formatting, and manipulation which was minimal.</li>
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
<li>Designed the overall aesthetic and layout to ensure a user-friendly interface. The background and icons were designed and exported from PowerPoint.</li>
</ul>
<p></p>

### Data Analysis and Exploration:
<ul>
<li>Created a ‘Measures’ table to store DAX calculations for data analysis.</li>
<li>Utilized various sorting/grouping DAX expressions for more detailed graphics.</li>
</ul>
<br>


# Dashboard
### Overview Page:
<ul>
<li>Displays general ticket information: quantity, purchase methods, monthly ticket totals, and average price.</li>
<li>Highlights the number of stations covered, with a focus on the top 3 departure and arrival stations, their on-time performance, and revenue.</li>
<li>KPIs and visuals to provide a summary of other key metrics.</li>
</ul>
<p></p>

![MainDB](https://github.com/julyndav/PowerBI/blob/main/UK_National_Rail/Images/UKRail%20Img1.png)

### General Insights: 
<b>Enhancing Online Sales Channel:</b>

With 59% of purchases done online, there is a clear trend towards digital transactions. Investing in improving the online purchasing experience, such as optimizing the website or mobile app for easier navigation and quicker transactions, could lead to increased sales and revenue.

<b>Utilization of Discount Railcard:</b>

Despite the discount railcard availability, 66% of passengers do not use it. Identifying reasons for low adoption (e.g., awareness, perceived value, eligibility) and implementing targeted marketing or adjustments could boost usage, increasing ticket sales and revenue.

<b>Operational Efficiency Based on Punctuality:</b>

Focusing on maintaining or improving punctuality at top arrival stations (85% on-time) and departure stations (75-80% on-time) can boost customer satisfaction, repeat business, and operational efficiency. Addressing factors causing delays at underperforming stations can optimize operations and reduce associated costs.

<br></br>

### Route Overview:
<ul>
<li>Showcases ticket classes, highlights the main reasons for delays and refunds totals per ticket class.</li>
<li>Features an interactive route map and a general timeline to visualize passenger patterns over a 24-hour period.</li>
<li>There are separate dashboards for Arrival and Departure information. These are access via the buttons on the main route page.</li>
<li>If one chooses, there is a Passenger Dashboard which displays passenger information anonomously.</li>  
</ul>
<p></p>

![RouteOv](https://github.com/julyndav/PowerBI/blob/main/UK_National_Rail/Images/Route_Overview.png)
<br></br>


### Departures:
<ul>
<li>Visualizations exclude canceled trips to provide a clearer picture of actual departures.</li>
<li>Identifies peak travel times: 6-8am and 4-6pm, influenced by commuters and possible students.</li>
<li>Breaks down ticketing by station.</li>
<li>Customized tooltip to display additional information.</li>
</ul>
<p></p>

![RouteOv](https://github.com/julyndav/PowerBI/blob/main/UK_National_Rail/Images/Departures.png)
### General Insights: 
<b>Departure Stations:</b>
The distance between Edinburgh and the nearest departure station in Leeds represents a substantial area. Considering budget and geographical coverage, 
strategically increasing the number of stations along this route has significant profit potential. By enhancing accessibility and service coverage in 
this corridor, it can effectively capture untapped market demand and optimize revenue generation.
<br></br>

<figure>
  <img src="https://github.com/julyndav/PowerBI/blob/main/UK_National_Rail/Images/Dept_TT.png" alt="Departure Timetable">
  <figcaption>Departure Tooltip showing top metrics per selected station.  Values shown are default.</figcaption>
</figure>
<br></br>

### Arrivals:
<ul>
<li>Similar layout to Departures but focuses on average delay times and performance issues.</li>
<li>Examines trip delays, on-time percentages, and cancellations.</li>
<li>Analyzes station-specific delays to highlight where performance improvements can be made.</li>
<li>Only arrivals had data on delays.</li>
</ul>
<p></p>

![RouteOv](https://github.com/julyndav/PowerBI/blob/main/UK_National_Rail/Images/Arrivals.png)
### General Insights:

<b>Arrival Stations:</b>
Same with Departures, there are substantial areas that are vacant. This significantly increases commuter time by bus or other means to get to/from a station. 
Costs involved in laying new rail is substantial so thorough research would need to be conducted in the areas to see if rail expansion is even viable.
Resident surveys, need, land surveys and more are all things to take into account during research.

<b>Delay Factors:</b>
Delays in railway operations can be categorized into two primary factors: weather-related delays, which are unpredictable despite forecasts, and operational delays typically caused by technical malfunctions or staffing issues. Understanding these delays requires a deeper analysis to ascertain their root causes, severity levels, and the condition of equipment. This data-driven approach will enable us to implement targeted improvements, optimize operational efficiency, and enhance customer satisfaction by minimizing avoidable disruptions.
<br></br>
### Route Recommendations:
<b>Conduct Feasibility Studies:</b>
Perform thorough research including resident surveys, land surveys, and market demand analysis to determine the viability of adding new departure and arrival stations along the route between Edinburgh and Leeds.

<b>Strategic Expansion:</b>
Focus on areas with substantial population density and inadequate access to current stations. Prioritize locations where improved accessibility could capture untapped market demand. Assess the costs involved in new station development versus the potential revenue increase from capturing new commuters. Ensure the expansion aligns with the budget and long-term strategic goals.
<br></br>

### Peak Travel Times:
<ul>
<li>Uses DAX calculations to identify peak travel hours and group them into categories.</li>
<li>Includes a heatmap to visualize passenger patterns and trends over different hours of the day.</li>
<li>Addressed issues with sorting by creating a separate table for 'DayOfWeek' and DAX to ensure correct hour of the day order.</li>
</ul>
<p></p>

![RouteOv](https://github.com/julyndav/PowerBI/blob/main/UK_National_Rail/Images/Time_Perf.png)
<br></br>


### Revenue:

Summarizes monthly revenue amounts. Incorporated custom tooltip that breaks down the months into days of the week for that month.
Highlights the difference between gross and net revenue amounts.
Provides a detailed revenue breakdown by ticket type and class to identify key revenue drivers.

![RouteOv](https://github.com/julyndav/PowerBI/blob/main/UK_National_Rail/Images/Revenue_DB.png)
<br></br>


![Passengers](https://github.com/julyndav/PowerBI/blob/main/UK_National_Rail/Images/Passenger_DB.png)

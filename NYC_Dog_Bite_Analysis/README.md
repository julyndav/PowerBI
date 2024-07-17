# Data-Driven Insights: NYC Dog Bites (2015-2022)  
A comprehensive interactive dashboard analyzing dog bite incidents in NYC from 2015 to 2022, utilizing a dataset of approximately 22,000 records sourced from Kaggle. The data cleaning process was performed via Jupyter Notebook and using Python. The focus was on duplicate removal, data type adjustments, and dog breed consolidation. Using Python and Pandas libraries, I performed in-depth exploratory data analysis (EDA) and created insightful visualizations.

The refined dataset was extracted from the Jupyter Notebook into a CSV file and seamlessly integrated into PowerBI. This allowed me to create dynamic visualizations that effectively convey key insights from the exploratory analysis. This project demonstrates my proficiency in data cleaning, transformation, and visualization, showcasing my ability to extract actionable insights from complex datasets.
<br></br>

## Table of Contents:
[Kaggle Analysis w/dataset](https://www.kaggle.com/code/julyndav/ny-dog-bite-analysis-visualizations)

[New York Open Data](https://data.cityofnewyork.us/Health/DOHMH-Dog-Bite-Data/rsgh-akpg/about_data)
<br></br>
## Dog Bite Data Variables:
| Variable |Purpose |
| --- | --- |
| UniqueID| Unique dog bite case identifier |
| DateofBite| Date bite took place |
| Species | Type of animal |
| Breed | Breed of dog |
| Age | Age of dog at time of bite |
| Gender | Gender of dog |
| SpayNeuter | Whether reproductive organs have been removed |
| Borough | New York City neighborhood/borough that bite took place in |
| ZipCode |Zip code bite took place in |

<br></br>
### Skills Demostrated
<ul>
<li>Python (for data cleaning, data manipulation and exploratory analysis)</li>
<li>Panda/Matplotlib (for data visualizations)</li>
<li>Dashboard Design (PowerBI and Powerpoint)</li>
<li>Extract and Loading Data</li>
</ul>

<br></br>
# Project Overview:
## Data Notes: 
* Ages with value of 0 were kept for the analysis. Zero age is valid in cases where the dog was a stray, or ran off after the bite incident.
* Bite Month and Bite Year columns were added to the data set to aid in analysis.
* There is an 'Other' option for the boroughs which included data outside of NYC. By filtering out the 'Other' boroughs, approximately 320 records were excluded from the dashboards as this PowerBi analysis was strictly for the NYC boroughs only. 
<br></br>

## Dashboard Notes:
There is a main landing page/home page where an individual borough can be selected. The overview option shows various KPI's and other bite trends. 

![Dashboard Homescreen](https://github.com/julyndav/PowerBI/blob/main/NYC_Dog_Bite_Analysis/Images/HomeScreen.png)
<br></br>

## Borough Dashboards
Each borough has their own separate dashboard page. Borough pages consists of donut charts and bar charts. Clicking a variable on either bar chart will filter the other visuals within the page.

1.	Spayed/Neutered Percentage: The distribution of whether the dog was spayed/neutered. Again this can only be known if the dog involved in the biting incident was detained or the dog was known by the person bit.
2.	Gender Percentage: Shows the distribution genders.
3.	Bites per Year: Total bite incidents for each year. It helps in understanding/determining bite trends.
4.	Top 8 Dog Breeds: Top dog breeds prone to biting for the boroughs. 8 Breeds were chosen so the chart would display fully.
   
![Dashboard borough1](https://github.com/julyndav/POwerBI/blob/main/NYC_Dog_Bite_Analysis/Images/BoroughScreen.png)

<br></br>
By clicking on any of the years in either bar chart, it will filtered the rest of the data accordingly. 
| Data Filtered by 'Year' Value     | Data Filtered by 'Top 8' Value     | 
| ----------------------------------- | ----------------------------------- | 
| Selected 2015 Bite year    |   Selected Pit Bull Breed         |
![Breed](https://github.com/julyndav/POwerBI/blob/main/NYC_Dog_Bite_Analysis/Images/Manhat_filrd.png) | ![Year](https://github.com/julyndav/POwerBI/blob/main/NYC_Dog_Bite_Analysis/Images/Manhat_filrd2.png) | 

<br></br>
## Overview Dashboard   

1.	Key Performance Indicators (KPIs): Highlight the crucial metrics such as total bite incidents, number of male vs females, spaye/neuter breakdown.
2.	Bites per Month Overall: This visualization breaks down the total number of bites for each month throughout the study period. The data reveals a noticeable increase in incidents during the summer months, likely due to higher outdoor activity.
3. Overall Bite Count by Age: This chart displays the number of bites across different age groups of dogs, ranging from 0 to 17 years old. Notably, a single outlier was observed, a dog allegedly 20 years old.
   
![Overview](https://github.com/julyndav/POwerBI/blob/main/NYC_Dog_Bite_Analysis/Images/OverviewData2.png)
<br></br>

## Data Analysis Insights:
1. Over 70% of the dogs were not spayed or neutered.
2. The majority of dogs involved in bite attacks where Male at 46%. Females were reportedly involved in only 19% of bite incidences.
3. Unknown Gender: These dogs accounts for 36% of bite incidences. The unknown factor could come from the dog running off after the incident occured.
4. <b>Data Discrepancy Insight:</b> Dogs listed with an age of 0 likely represent cases where the dogs ran away after the bite incident. This ties in with the "unknown gender" variable, as these dogs are often not captured and their details remain unverified. We would expect the counts of "age 0" and "unknown gender" to be similar, as it's unlikely that a dog's age would be known without knowing its gender. This discrepancy suggests that there may be inconsistencies in how data was recorded for runaway dogs.

   

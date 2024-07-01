# NYC_Dog_Bite_Analysis
I am happy to share my first Power BI project: a dynamic and interactive Dashboard for Dog bite data from various New York city boroughs. The time frame for the data covers 2015 through 2021.  

The initial dataset for this analysis was cleaned using the Kaggle platform then imported into PowerBI. There is a link to the Kaggle analysis below. There is also a link to the original dataset from the New York Open Data website (the dataset is continually being updated).

This dashboard provides a comprehensive view of the data broken down by Borough with an overall view, key metrics and visualizations that offer valuable insights.  <br></br>
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
# Project Overview:
## Data Notes: 
* Ages with value of 0 were kept for the analysis. Zero age would be valid to keep in cases where the dog was a stray, or ran off after the bite incident.
* Bite Month and Bite Year columns were added to the data set to aid in analysis.
* There is an 'Other' option for the boroughs which included data outside of NYC. By filtering out the 'Other' boroughs, approximately 320 records were excluded from the dashboards as this PowerBi analysis was strictly for the NYC boroughs only. 
<br></br>

## Dashboard Notes:
<i>Along with learning to import data from an external source and create various visualizations. This project was also to practice customizing those visualizations.</i>

There is a main landing page/home page where an individual borough can be selected. The overview option shows various KPI's and other bite trends. 

![Dashboard Homescreen](https://github.com/julyndav/PowerBI/blob/main/NYC_Dog_Bite_Analysis/Images/HomeScreen.png)
<br></br>
## Borough Dashboards
Each borough as their own separate dashboard. Borough dashboards consists of donut charts and bar charts. Clicking a variable on either bar chart will filter the other visuals within the page.

1.	Spayed/Neutered Percentage: This donut chart shows the distribution of whether the dog was spayed/neutered. Again this can only be known if the dog involved in the biting incident was detained or the dog was known by the person bit.
2.	Gender Percentage: This donut chart shows the distribution genders.
3.	Bites per Year: This clustered column chart shows the total bite incidents for each year. It helps in understanding/determining bite trends.
4.	Top 8 Dog Breeds: This clustered column chart shows the top dog breeds prone to biting for the boroughs. 8 Breeds were chosen so the chart would display fully.
   
![Dashboard borough1](https://github.com/julyndav/POwerBI/blob/main/NYC_Dog_Bite_Analysis/Images/BoroughScreen.png)

<br></br>
By clicking on any of the variables in either bar chart, it will filtered the rest of the data accordingly. 
| Data Filtered by Top 8 Variable     | Data Filtered by Year Variable      | 
| ----------------------------------- | ----------------------------------- | 
| Selected the first dog breed       |   Selected 2018 Bite year         |
![Breed](https://github.com/julyndav/POwerBI/blob/main/NYC_Dog_Bite_Analysis/Images/Manhat_filrd.png) | ![Year](https://github.com/julyndav/POwerBI/blob/main/NYC_Dog_Bite_Analysis/Images/Manhat_filrd2.png) | 

<br></br>
## Overview Dashboard   

1.	KPIs: These are just a random sample of various KPIs that could have been created. 
2.	Bites per Months Overall: This clustered column chart breaks down the bite totals for each month of the entire study. We can see that the summer months are higher due to folks being out and about more.
3. Overall Bite Count by Age: Range of ages vs number of bites. The Ages went from 0 to 17.  Allegedly, one of the dogs in the study was 20 years old so they were singled out.  

![Overview](https://github.com/julyndav/POwerBI/blob/main/NYC_Dog_Bite_Analysis/Images/OverviewData2.png)






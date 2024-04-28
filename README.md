# Team 4 MIST 4610 Group Project 2

## Team Name:
47114 Group 4

## Team Members: 
1. Morgan Busbee [@morgan-busbee](https://github.com/Morgan-Busbee)
2. Corbin Gay [@corbinGay](https://github.com/CorbinGay)
3. Carson Harris [@clh15315](https://github.com/clh15315)
4. Ashley Seelochan [@as88578](https://github.com/as88578)
5. Hank Stocke [@hstocke1](https://github.com/hstocke1)
6. Katie White [@katiewhite29](https://github.com/katiewhite29)

## Problem Description:
For this project, we are utilizing a data set from the US Data Government website that lists New York City Police Department Shooting Incidents from 2006-2022. Within this data, the primary key is listed as INCIDENT_KEY and this gives an individual number for each of the incidents. The next column within the data set is OCCUR_DATE and the following one is OCCUR_TIME, both of these give the date and time when the incident occurred. There is a column titled BORO and it shows the New York Borough where the shooting occurred. The shooting could occur in one of the following: Bronx, Brooklyn, Manhattan, Queens, and Staten Island. There is a column titled PRECINCT which lists location information about the shooting for police purposes. There is a LOCATION_DESC column (location description) to add details to some of the shootings such as "Grocery store" or "Jewelry Store". Within the data, there is a column that is titled STATISTICAL_MURDER_FLAG, the data for this column is either true or false and this is used to determine if the shooting resulted in the victim's death which would be counted as a murder. After this column, 3 columns describe the perpetrator with their age group, their sex, and their race. Followed by another 3 columns describing the victim's age group, sex, and race as well. The last columns describe the coordinates of where the shooting incident took place. 

## Data Model Questions: 
### Question 1: 
Create a line graph to show the distinct count of incidents that occur at different times throughout the day for the years 2019, 2020, and 2021. Create a bar graph to measure the number of victims by their sex for these years as well. Also, create a heat map for 2019, 2020, and 2021 to count the number of victims by their race and age group. Use a dashboard to show these visualizations. 

<img width="1005" alt="Screenshot 2024-04-27 at 1 17 33 PM" src="https://github.com/katiewhite29/4610-Project-2/assets/150160152/611aac3c-b330-4aba-b600-9d041a6963b0">

From these visualizations, we observed that shootings occur more frequently in NYC during the late night and early morning hours. We also observed that victims were predominantly male. In addition, there is a notable concentration of victims aged 25-44 among the Black community.  


### Question 2: 
Create a map showing the locations of each distinct shooting incident colored by borough that occurred in New York City during the years 2019, 2020, and 2021. Also, create a line graph for each of these years showing the number of shooting incidents over the year colored by borough. Use a dashboard to show both of these visualizations. 

<img width="1002" alt="Screenshot 2024-04-23 at 6 51 13 PM" src="https://github.com/katiewhite29/4610-Project-2/assets/163003533/04ad038b-a2f2-49df-811e-3422cc1ea914">

From these visualizations, we observed that during the summer months, the amount of shootings increased throughout almost all of the boroughs. However, during 2020 the amount of overall shooting incidents increased significantly during the summer months of June and July. This increase was most drastic in Brooklyn and the Bronx. 

## Manipulations to Data:
We utilized a calculated field to change the Victim Sex from "F" and "M" to "Female" and "Male" for easier differentiation in visualizations. 

We utilized count and distinct count on Incident Key to differentiate between the number of incidents and the number of victims. 

We utilized filters to select the appropriate years and exclude others.

We utilized filters to exclude outliers, mistakes, and irrelevant data in the data set such as unknown sex, unknown race, and wrong age values. 

## Analysis and Results: 
Our visualizations provide valuable insights for both the public and the New York City Police Department regarding the patterns of shootings across the city during the years of 2019, 2020, and 2021. 

Our first dashboard is comprised of three visualizations that highlight the disproportionate impact of gun violence on specific communities. It reveals a significant number of black victims across NYC with the largest number of black victims being in the age group of 25-44. In addition, it reveals that victims are predominantly male and that shooting incidents tend to occur more often during the late night and early morning. 

Our second dashboard is comprised of two visualizations that display shooting incidents from 2019 to 2021 across the five boroughs of NYC; Manhattan, Brooklyn, Queens, Bronx, and Staten Island. Each point on the map represents a single shooting incident and they are color-coordinated by the borough. The graph illustrates the variation in shooting incidents throughout the years also color-coordinated by the borough. Notably, Brooklyn and the Bronx have experienced a high concentration of gun violence, with a large spike in 2020 as numerous incidents were recorded in those areas. When examining shooting incidents over each year, we observe a positive line across the summer months with July consistently having the highest number of incidents. 

Our dashboards have examined the New York City Police Department data. Through our visualizations, citizens of NYC can better understand the potential risk factors associated with different demographics and times of day. Similarly, law enforcement agencies can utilize this information to better allocate resources more effectively, focusing on specific times and areas that exhibit higher rates of incidents. 


## Data Source

Police Department (NYPD). (2024). NYPD Shooting Incident Data (Historic). NYC OpenData. https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8/about_data


# Project2_Airport Statistics and Delay Causes

![github-small](https://user-images.githubusercontent.com/68081615/190210649-af611361-7a30-44c6-95ea-244a3cae5b5f.jpg)



Welcome to the proj2 wiki!

**Team Members**

•	Project Manager - Fellipe Lopez, Tyler Pohl

•	Lead Developer - Fellipe Lopez, Tyler Pohl

•	Frontend Developer - Priyanka Garg 

•	Backend Developer - Maria Alzaga, Tyler Pohl, Fellipe Lopez and Kasmira Madina

•	Data Engineer/Data Modeler - Fellipe Lopez, Maria Alzaga



***

## # Airline statistics and delay causes
 
**Project Description:**
The overall goal of this project is to investigate the general basis of flight delays and identify airlines, airports and routes with the highest delay rates. Data Flight delay statistics for this project are originally sourced from the Bureau of Transportation Statistics(BTS). The project demonstrates visualizations with multiple views on flight delay dataset across major airports, airlines, routes and months of the year. The airlines report the causes of delays in five broad categories: Air Carrier, Extreme Weather, National Aviation System (NAS), Late-arriving aircraft, Security. It provides users the ability to easily access and interpret timeseries flight delay statistics for various airports spread across the USA and the reason of likelihood a flight will be delayed at a particular airport and the trending performance of a particular airport in terms of its likelihood of flight delay. 

**Hypothesis**:
Weather delays are rather rare and are not primary reasons for flights to be delayed.

**Datasource**:
The dataset pertaining to flight delays is downloaded from the Bureau of Transportation Statistics (BTS), Airline Service Quality Performance 234 which stores, analyzes and maintains the transportation data.https://www.transtats.bts.gov/OT_Delay/ot_delaycause1.asp?display=download&pn=0&month=&year=
The dataset consists of information about 23 carriers and 373 airports from year 2014-2019. For the exact geo locations for each airport, we used the dataset airport_codes locations: More info on dataset can be found on this repo in db folder https://github.com/Pg-git27/proj2.

**Questions (Measures of Airline statistics and delay causes):**
•	What are the most busiest and least busiest airport and which carrier performs the better over time?
•	Which carrier has maximum difference between scheduled and actual arrival time.
•	What is the possible cause of cancellation or delays within the airline's control and what is the most extreme factor that causes the delay of 
        flights?
•	How does the flight delay percentage change over time?

**Technologies Used**
•	Flask
•	HTML/CSS/Bootstrap
•	Database Postgress, sqlite
•	Plotly/D3 or any other technologies.
•	Deployment using Heroku

**Actions and Tasks**
•	Analyze the BTS database. Find and clean the data. Create schema.
•	Explore and visualize the data.
•	Determine the visualizations.
•	Create the web app using HTML, CSS, Bootstrap, JS.
•	Plotting the routes and querying the code in flask python



UT Data Analysis & Visualization Bootcamp | December 2020

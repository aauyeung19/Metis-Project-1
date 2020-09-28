# Metis-Project-1
**Metis Fall 2020 Cohort**
Collaborators: Andrew Auyeung, Ganesh Bala, Navish Agarwal, Zachary Brandt

## Problem Statement  
We are consulted to provide information for WomenTechWomenYes (WTWY) on where to place street teams at subway stations. 
Their goal is to collect email address to share tickets for the gala. 
Our goal is to perform exploratory data analysis to provide insight based on the MTA Turnstile data sourced from MTA's website linked [here](http://web.mta.info/developers/turnstile.html)  

In the course of working towards the solution, a primary assumption has been made that WTWY would like to maximize the number of people it wants to reach out to.  

---

## Data Sources

[MTA Turnstile Data](http://web.mta.info/developers/turnstile.html)  

[MTA Subway Stations Location Data](web.mta.info/developers/data/nyct/subway/Stations.csv)  

## Overall Recommendation  

1. A set of 7 stations located in Manhattan, all below Central Park, were finalized as the recommended outreach locations. These were chosen due to the high commuter traffic they experience as well their geographic proximity to each other; making it easier for the street teams to coordinate logistically.  
    * 34th St - Penn
    * 34th St - Herald Square
    * Grand Central - 42nd St
    * 14th St - Union Square
    * 42nd St - Port Authority
    * 23rd St
    * Fulton St   
    
2. It is recommended to focus on outreach only on weekdays and ignore the weekends. Two shifts, from 5 AM to 1 PM and 1 PM to 9 PM can be deployed.  

3. Based on street team capacity/expense constraints, the reach out targets can be optimized further:  
    * If a single shift has to be picked, focus just on evening shift. The traffic is 30% higher in these 7 stations during the evenings.
    * If a single day has to be picked, Thursday experiences 15% higher traffic than the average daily amount.
    * If a single station has to be picked, 34th - Penn Station has the highest traffic throughput amongst all the 7 stations.

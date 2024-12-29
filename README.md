______

## [Google Data Analytics Project Capstone](https://github.com/SUPREME-CODER/Google-Analytics-Capstone-Project/blob/master/Google%20Analytics%20Capstone%20Project%201.ipynb)

### Certification
[Google Data Analytics Course](https://coursera.org/share/59978c03d5571cc3c5efc1bded3731d0)

### Problem Statement
Cyclistic, a leading bike-sharing program in Chicago, operates 5,824 GPS-enabled bicycles across 692 docking stations, offering flexible access for users. This project aims to boost Cyclistic's profitability by increasing annual memberships through the analysis of two sets of members casual and member rider usage patterns.

Casual riders, who purchase single-ride or full-day passes, are less profitable than annual members, making their conversion a key focus. Cyclistic offers three pricing plans: Single Ride Pass, Full Day Pass, and Annual Membership.

To guide this effort, the marketing strategy will address three key questions:

1. How do annual members and casual riders use bikes differently?
2. What motivates casual riders to purchase annual memberships?
3. How can digital media influence casual riders to become members?

Insights from this analysis will inform data-driven campaigns to achieve Cyclistic's growth and profitability goals.

[Data Source](https://divvy-tripdata.s3.amazonaws.com/index.html)

The Data included a total of 17 features including :-
* ride_id
* rideable_type
* Start and End times
* Start and End Station Names and IDs
* Start and End Coordinates
* Type of member - Annual or Casual
* Time of the Ride
* Year - Month of the Ride
* Weekday of the Ride
* Start Hour of the Ride

The data was obtained as a part of Google Analytics course on Coursera: _[Coursera Link: to be hyperlinked]_


These features give the summary of the bike rides which we can utilize to find solutions to the questions posed by the company and provide insights to take some actions to increase the conversion rate of casual to annual members.

### Dependencies
Tech Stack used - Python, Pandas, Matplotlib, Seaborn, Plotly.

### Project Workflow - We follow the Ask, Prepare, Process, Analyze, Share, Act Framework.
* **ASK**
    * In this phase we discuss how the project impacts the company's profits and what the burning questions that need to be solved for the firm to further its growth and achieve it's goals.
    * **What is the problem you are trying to solve?**
      * The goal is to analyze rider patterns to convert casual riders into annual members.
    * **How can your insights drive business decisions?**
      * The insights will help the finance and marketing team to increase annual members.

<br>

* **PREPARE**
    * This phase involved accessing the data from the source provided in the link above.
    * Clubbing the data together in the ascending order of the date time stamps.

<br>

* **ANALYSIS**
    * **Data Quality Check** - Performed some data quality checks which included finding out the shape of the data, formatting the date columns, removal of duplicate values, checking the values range of the numerical columns.
    * **Data Distribution Analysis** - This involved analysing the distribution of the rides w.r.t the client types, months of rides, temperature analysis of Chicago, weekdays of the ride, start hour of the ride, start hour for each weekday, weekday / weekend, start hours for weekday / weekends, types of bikes.
    * **Handling Outliers** - Removed the data below the 5th %tile and above the 99th %tile, thus finally having only 94% of the data.
    * **Further Distribution Analysis** - Distribution of rides data w.r.t. the ride time, ride time for each weekday, member types for each ride types. 
    * **Visualizations** - All the above mentioned distributions analysis are described very well with the help of a visualization each.
    * **Some insigths from the analysis** :-
        * Number of members are higher than casuals in the dataset.
        * More rides occur in the last semester of year.
        * There is more of a difference in the ridetime of members/casual from midweek to weekends.
        * Members use bikes for routine activities that differs from casual.
        * Casuals have higher riding time.
        * Both Members and Casuals tend to prefer Electric bikes.

<br>

* **SHARE** - Following insights were generated from the entire analysis of the data.
    * Annual Members make up 14% more of the dataset than casual riders.
    * More data points are recorded in the latter half of 2020 and 2021.
    * Ride volume is significantly influenced by temperature.
    * July 2021 holds the highest data count, ~8% of the dataset.
    * Members outnumber casual rides in all months except June, July, and August 2021.
    * The member-casual difference narrows mid-year and widens toward year-end.
    * Weekends see the highest ride counts.
    * Ride volume peaks in the afternoon, with members favoring early mornings.
    * Ride distribution is cyclical and influenced by temperature.
    * Members likely use bikes out of necessity, as seen in higher usage during colder months and routine patterns.
    * Weekend rides increase due to significant rises in both member and casual usage, suggesting recreational purposes.
    * Afternoon and evening see the highest biking activity.

    * **Differences Between Members and Casuals:**
        * **Ride Volume:** Members have more rides overall, except on Saturdays when casuals dominate.
        * **Weekend Trends:** Casuals see higher ride volumes on weekends, especially from 10 AM to 6 PM.
        * **Time Preferences:**
            * Members prefer early mornings (5 AM–12 PM).
            * Casuals ride more late at night (10 PM–4 AM).
            * Members see ride spikes midweek (6 AM–9 AM and 3 PM–6 PM).
        * **Bike Preference:**
            * Members favor classic bikes.
        * **Ride Duration:**
            * Casuals have longer ride times than members.
            * Members’ ride times are consistent midweek but increase on weekends.
            * Casuals’ ride times peak on weekends and are lowest midweek.
        * **Usage Patterns:**
            * Members use bikes for routine purposes like commuting or exercise, shown by consistent midweek usage and morning/afternoon peaks.
            * Casuals primarily use bikes for recreation, especially on weekends when ride times increase.

<br>

* **ACT** - This is where the marketting teams comes into action for working on the insights provided.

### Usage
Install the Jupyter Notebook and access the data mentioned in the link in Data Source and execute the cells one by one.

### Results
Provide the Final Insights section
* The results have been shared in the final phases of **SHARE** and **ACT** of the project.
* The next steps on how we can improve our analysis to gain better understanding and design accurate strategies for customers are also provided.


### Final Notes
This is a great project to learn:-
* A framework to follow for the entire project's life cycle.
* Analysis of Multivariate Data Distribution.
* Focus on the analysis that answers the questions of the business.



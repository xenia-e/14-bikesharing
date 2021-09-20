# 14-bikesharing

# Overview of the project
Provide a bike trip analysis to convince investors that a bike-sharing program in Des Moines is a solid business proposal. This presentation consists of two technical analysis deliverables and a written report to present results.

## Methods 
- **Tableau Public** 
- **Python** and **Pandas**
 

### Resources
Data source: 
- Downloadable files of Citi Bike trip data from [Citi Bike Trip Histories](https://www.citibikenyc.com/system-data) 


## Deliverables

__**Deliverable 1:**__ Change Trip Duration to a Datetime Format
__**Deliverable 2:**__ Visualizations for the Trip Analysis
__**Deliverable 3:**__ [Written Report for the Final Presentation](https://github.com/xenia-e/14-bikesharing/blob/main/README.md)

# Results and Summary
The Story is created using visualizations that will support the key findings of this analysis: [link to dashboard](https://public.tableau.com/app/profile/xenia.evdokimova/viz/Bikesharing_challenge_16320728889740/Bikesharing)

According to the analysis of provided data, we can make the following conclusions

1. Average trip duration is less than an hour for both user groups and all gender groups.

![Checkout times](https://github.com/xenia-e/14-bikesharing/blob/main/Analysis/Checkout_times.png)

> Figure 1 - Checkout time by Usertipe and Gender

2. If we look at trips by the hour of the day (Figure 2), it is safe to assume that weekday riders use Bikes to commute to and from work, with peak hours from 7–9 AM and 5–7 PM. Most weekend rides occurring in the mid-afternoon hours. In general, bikes are used on weekdays more than on weekends.

Different gender groups follow the same usage pattern with more male users than other genders.

![Trips by Weekday by Hour](https://github.com/xenia-e/14-bikesharing/blob/main/Analysis/Trips_by_weekday_hr.png)

>Figure 2 - Trips by Weekday by Hour

3. Age analysis shows that the average user is born between 1980 and 2000 for male and female genders. There is an outlier in an unknown gender group for the 1960-1970 years that require further analysis. 

![Trips Count by User Age](https://github.com/xenia-e/14-bikesharing/blob/main/Analysis/trips_by_age.png)

>Figure 3 - Trips Count by User Age

4. Cross analysis between user type and gender leads us to the conclusion that the average user of the bike-sharing program is a Male annual subscriber. We can portray the average user as a Male user with an annual subscription born between 1980-2000 that uses the bike-sharing program to commute to and from work

![Usertipes](https://github.com/xenia-e/14-bikesharing/blob/main/Analysis/usertype.png)

>Figure 4 Usertipes


# Chicago-Crime-Analysis
Data analysis project to discover insights and trends of crime in Chicago - (2018)


### About
This was a project I did while in the Business Data Analysis (BUS443) course. The purpose of this data analysis project was to take the skills I had learned during lecture and apply them to a real world problem - crime in Chicago and how to best address the issue. The data used in this project was downloaded from the [City of Chicago Crime Catalog](https://www.chicago.gov/city/en/dataset/crime.html), and contained over 800,000 distinct incidents over 17 years, from 2000 to 2017.

### Process
This project was broken down into 4 discrete steps:\
1. Cleaning, reorganizing, and fixing errors in the data using MS Excel, MS Access, and SQL
2. Importing the data (only 2015-2017 due to lack of processing power) into Tableau
3. Creating and interpretting visualizations to understand trends in crime such as: seasonality, overall changes, and patterns
4. Recommending a course of action based on insights gained from the visualization to the Chicago PD (This didn't actually happen, it was a mock presentation to the class)

### Visualizations
#### Chicago Crime Overview 2015-2017
![Tableau img crime overview](Tableau_Overview.png)

**Total Crime** → We can see that the overall crime trend is increasing during the time period of 2015-2017\
**Crimes Exceeding the Monthly Average** → The average crime count over the 3 year period was calculated, and any crime with a monthly average higher than the overall is considered a *common crime*. Homicide is one of the crimes that exceeds this monthly average. Yay Chicago! /s\
**Districts Exceeding the Monthly Average** → Likewise, this same analysis was conducted with the districts of Chicago to discover which districts should be considered more dangerous\
**Where Crimes Exceeding the Monthly Average are Most Likely to Occur** → I took the crimes that exceeded the monthly average and overlaid their average GPS coordinates on a map of Chicago, also overlaid with colors representing mean household income. Right off the bat, we can see that these common crimes usually occur in areas that are well below the income of the wealthiest areas of the city, but also surprisingly don't occur in the poorest areas of the city. With this visualization, you can see that these crimes *usually* occur in different areas than others, begging the question: Why? What is different about one district of Chicago that leads to (for example) more narcotics arrests than others? Is there some different type of policing (or just more of it) in this specific area to address this type of crime. 


Fixed errors and discrepancies in over 798,000 rows of Chicago crime data from 2000 to 2017 using Microsoft Excel and Access
Analyzed data 3 years of data with Tableau by reorganizing, graphing, and visualizing to develop insights
Discovered trends in crime data such as: seasonality, overall decreases and increases, and weekly and hourly patterns
Created visuals to show easily communicate trends, counts, and maps of crime data
Recommended a course of action based on the insights developed from analyzing the crime data

# Communicate data findings
## Introduction 
This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process.

1. In Part I, Exploratory data visualization, I use Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables.

2. In Part II, Explanatory data visualization, I produce a short presentation that illustrates interesting properties, trends, and relationships that was discovered in your selected dataset. The primary method of conveying my findings will be through transforming the exploratory visualizations from the first part into polished, explanatory visualizations.

## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. Bay Area Bike Share is a company that provides on-demand bike rentals for customers in San Francisco, Redwood City, Palo Alto, Mountain View, and San Jose. Users can unlock bikes from a variety of stations throughout each city, and return them to any station within the same city. Users pay for the service either through a yearly subscription or by purchasing 3-day or 24-hour passes. Users can make an unlimited number of trips, with trips under thirty minutes in length having no additional charge; longer trips will incur overtime fees.
The source data (Ford GoBike System Data) is available at : [here](https://www.fordgobike.com/system-data).  


## Summary of Findings

In the exploration of the Ford GoBike dateset, I observed that there was a very weak relationship between bike users age and the ride duration. Categorizing age into on Six generational cohort according to [here](https://www.pewresearch.org/fact-tank/2019/01/17/where-millennials-end-and-generation-z-begins/) shows that users within the ages of 46-64years had higher ride duration relatively to younger age riders. 
Based on ride frequency, riders preferred starting their ride as early as 8am or in the evenning time by 5pm. On the average, Female customers mostly emabark on a longer trip than the Male customers. 

Also, it was observed that trips that occurred in mid-weeks have higer duration compared to weekends. The longer trip duration per minutes usually occurs in the early hours of mid-week days. 

## Key Insights for Presentation

For the presentation, I focus on just the influence of some selected numerical and categorical variables on ride duration. 
I started by introducing the distribution of the bike duration per seconds, followed by log transformtion of the duration variable per minutes. 

Afterwards, I introduce each of the categorical variables one by one. To start,
I used the box plots of users type, gender and proceeded to examining the distribution of other categorical variable, through the use of count plot I obtained the distribution of days of the week and hours of bike trip. I used a bivariate plot to examine the ride frequency based on the hour of days. Lastly, I examined the top route based on starting and ending stations with respective to the trip duration.
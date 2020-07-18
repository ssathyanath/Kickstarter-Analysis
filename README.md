# Kickstarting with Excel

## Overview
This project uses kickstarter crowdfunding data for analysis. Earlier we had analyzed the kickstarter data and provided recommendations on how goals and launch dates impact successful campaigns. Now we will be analyzing the crowdfunding data to see how Louise faired against other campaigns. 

### Purpose
The purpose of the project is to analyze the kickstarter campaign data to find trends and relation between attributes that contribute to a successful crowdfunding campaign. For this analysis, our focus will be on how the goal amount and campaign launch date impacts a successful campaign.

## Analysis and Challenges
As stated in the purpose of the project, the analysis of the kickstarter data was mainly focused on the goal amount and the launch date. Below are the details for the analysis by launch date and goals.

### Analysis of Outcomes Based on Launch Date
For analysis by launch date, we created a pivot table and chart that shows the number of campaigns by outcome and launch date filtered for theater subcategory, as seen in the chart below.

### Analysis of Outcomes Based on Goals
For analysis by goal amount, we first group the goal amount in 12 different rows. We then created a new table that shows us the number of campaigns by outcomes for each of the goal group. The data was also filtered for "plays" subcategory. Below is the link to the chart.

### Challenges 
As with any analysis, there were a few challenges that we encountered. 
- The data type in the columns were not formatted correctly. 
- Launch date and end date columns have unix timestamp. We had to calculate the Gregorian date and format it accordingly which must be for our analysis.
- The parent category and Subcategory field were combined in a single column. They had to be split for easier analysis

## Results
### Conclusions based on Launch Date
- Most campaigns were launched in the May - June time frame. Most of the campaigns that are launched in the May - June time frame succeeded (approximately 66%)
- December is the month with the least amount of campaigns. A campaign launched in December had ~49% chance of succeeding. 

### Conclusions based on Goals
- Based on the goals, we can clearly see that most plays were launched with goal amount of less than 10000 (85%). 
- Campaigns with less goal amount succeed more compared to the campaigns with higher goals. Campaigns with goal amount less than 5000 has a 73% - 75% of succeeding.

### Limitations of this dataset
- The dataset has campaign data only up to 2017. 
- There also seems to be only ~4000 campaigns listed for 9 years, all over the world. This seems like we don’t have the complete data for our analysis.

### Other possible tables and/or graphs that we could create.
Based on the data available, we could do more analysis that can help launch successful campaign. Some of the analysis are listed below. 
- We can calculate the duration a campaign was open and do analysis on how long it took for campaigns to reach its goal.
- Number of campaigns based on outcomes and categories helps us identify, which category has the most success in kickstarter campaigns.
- We can look at year over year trends for campaign outcomes to see if the demand for a category campaign is still up.

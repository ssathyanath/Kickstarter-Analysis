# Kickstarter Data Analysis with Excel

## Overview
This project uses kickstarter crowdfunding data for analysis. Recommendations were initially made on how goals and launch dates impact successful campaigns after analyzing the kickstarter data. For this project, the crowdfunding data will be analyzed to see how Louise's campaign faired against other campaigns. 

### Purpose
The purpose of this project is to analyze the kickstarter campaign data to find trends and relation between attributes that contribute to a successful crowdfunding campaign. For this analysis, the focus will mainly be on how the goal amount and campaign launch date impacts a successful campaign. 

## Analysis and Challenges
As stated in the purpose of the project, the analysis of the kickstarter data was mainly focused on the goal amount and the launch date. Below are the details for the analysis by launch date and goals. Detailed analysis can be found in the spreadsheet link. [Kickstarter Analysis.xlsx](https://github.com/ssathyanath/Kickstarter-analysis/blob/master/Kickstarter_Challenge.xlsx)

### Analysis of Outcomes Based on Launch Date
For analysis by launch date, the launch date had to be convereted from unix timestamp to short date format. A pivot table and chart that shows the number of campaigns by outcome and launch date, filtered for theater subcategory, was created as seen in the chart below. The launch date column was also grouped to months for easier analysis.

![alt text](https://github.com/ssathyanath/Kickstarter-analysis/blob/master/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals
For analysis by goal amount, the goal amount was grouped into 12 different rows. A new table(/sheet) that shows us the number of campaigns by outcomes for each of the goal group was then created. The data was also filtered for "plays" subcategory and a chart as shown below was created.

![alt text](https://github.com/ssathyanath/Kickstarter-analysis/blob/master/Outcomes_vs_Goals.png)


### Challenges 
As with any analysis, there were a few challenges that were encountered. 
- The data type in the columns were not formatted correctly. 
- Launch date and end date columns had unix timestamps. The Gregorian date had to be calculated and formatted for our analysis.
- The parent category and subcategory fields were combined in a single column. They had to be split for easier analysis.

## Results
### Conclusions based on Launch Date
- Most campaigns were launched in the May - June time frame. Most of the campaigns that were launched in the May - June time frame succeeded (approximately 66%).
- December is the month with the least amount of campaigns. A campaign launched in December had ~49% chance of succeeding. 

### Conclusions based on Goals
- Based on the goals, we can clearly see that most plays were launched with goal amount of less than 10000 (85%). 
- Campaigns with less goal amount succeeded more compared to the campaigns with higher goals. Campaigns with goal amount less than 5000 has a 73% - 75% chance of succeeding.

### Limitations of this dataset
- The dataset has campaign data only up to 2017. 
- There also seems to be only ~4000 campaigns listed for 9 years, all over the world. This seems like we don’t have the complete data for our analysis.

### Other possible tables and/or graphs that we could create.
Based on the data available, additional analysis can be done to help launch successful campaigns. Some of the analysis are listed below. 
- The duration of a campaign was open can be calculated based on launch date and end date. The duration of the campaign can then be analyzed to see if it has an impact on reaching the campaign goal.
- Number of campaigns based on outcomes and categories helps us identify, which category has the most success in kickstarter campaigns.
- Charts showing year over year trends for campaign outcomes can be analyzed to see if the demand for a specific category campaign is still up.

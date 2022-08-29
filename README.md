# kickstarter analysis using Excel
click this link to view the file which is used for analysis: []
## Overview of Project
### Purpose
The purpose of this analysis is to compare the results based on different criteria using different categories like successful,failed,cancelled campaigns in different countries which is based on launch dates and investment goals.
## Analysis and Challenges
Before jumping into analysis,first I had to understand the whole kickstarter dataset which is used for analysis.We can see that dataset give us variety of information about goal and pledged amount for campaigns,start and launch dates,category and subcategory. Most challenging part in the analysis was to understand the format of dates because they are not in understandable form to human eye.so I used epoch converter method to convert numbers into dates.
### Analysis Of Outcomes Based On Launch Date
In this phase of analysis,I created a pivot table that filtered the results based on category and launch dates.The columns give us the information about the status of the campaign, while the row represent the months in which campaign took place. This gives us the total number of successful, failed, and canceled theater campaigns.An image of the pivot table with a filter for the theater category is shown below.
### Analysis of Outcomes Based on Goals
In this phase of analysis,I created a pivot table showing outcome of project based on goal amount.The columns gives us the information about the status of the campaign against the goal range set for that particular campaign. This gives us the success and failed rates of campaigns depending on goal amount set for it.An image of the pivot table based on goals is shown below.
## Results

(1) What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Using this pivot table we can see that the theater category has highest successful outcome in the month of May.
2. Also amount of cancelled campaigns are quite lower than both successful and failed campaign. In addition of this, there are zero cancelled campaign between months of September to November.

(2) What can you conclude about the Outcomes based on Goals?
- Using this analysis, we can conclude that the number of successful campaigns are higher if the goal range is low.Also we can deduce number of failed projects increases drastically when goal amount is 50000 or more.

(3) What are some limitations of this dataset?
- Some column data like dates were not in understandable form to human eye.

(4) What are some other possible tables and/or graphs that we could create?
- We can create tables and/or graphs based on category and subcategory of the campaign.

# kickstarter analysis using Excel
click this link to view the file which is used for analysis: [Kickstarter Analysis](https://github.com/miralchangela/kickstarter-analysis/blob/main/Kickstarter_Challenge.xlsx)

## Overview of Project
### Purpose
The purpose of this analysis is to compare the results based on different criteria using different categories like successful,failed,cancelled campaigns in different countries which is based on launch dates and investment goals.
## Analysis and Challenges
Before jumping into analysis,first I had to understand the whole kickstarter dataset which is used for analysis.We can see that dataset give us variety of information about goal and pledged amount for campaigns,start and launch dates,category and subcategory. Most challenging part in the analysis was to understand the format of dates because they are not in understandable form to human eye.so I used epoch converter method to convert numbers into dates.
### Analysis Of Outcomes Based On Launch Date
In this phase of analysis,I created a pivot table that filtered the results based on category and launch dates.The columns give us the information about the status of the campaign, while the row represent the months in which campaign took place. This gives us the total number of successful, failed, and canceled theater campaigns.An image of the pivot table with a filter for the theater category is shown below.

![Theater Outcomes Pivot Table](https://github.com/miralchangela/kickstarter-analysis/blob/main/Resources/Theater%20outcomes%20pivot%20table.png)

### Analysis of Outcomes Based on Goals
In this phase of analysis,I created a pivot table showing outcome of project based on goal amount.The columns gives us the information about the status of the campaign against the goal range set for that particular campaign. This gives us the success and failed rates of campaigns depending on goal amount set for it.An image of the pivot table based on goals is shown below.

![Play Outcomes Table](https://github.com/miralchangela/kickstarter-analysis/blob/main/Resources/Outcomes%20pivot%20table%20based%20on%20Goals.png)

## Results

(1) What are two conclusions you can draw about the Outcomes based on Launch Date?
1. Using this pivot table we can see that the theater category has highest successful outcome in the month of May.
2. Also amount of cancelled campaigns are quite lower than both successful and failed campaign. In addition of this, the number of successful campaigns is almost equivalent to the number of failed campaigns during the month of December.

![Outcomes Based on Launch Date](https://github.com/miralchangela/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.jpg)


(2) What can you conclude about the Outcomes based on Goals?
- Using this analysis, we can conclude that the number of successful campaigns are higher if the goal range is low.Also we can deduce number of failed projects increases drastically when goal amount is 50000 or more.

![Outcomes Based on Goals](https://github.com/miralchangela/kickstarter-analysis/blob/main/Resources/Outcomes_vs_goals.jpg)


(3) What are some limitations of this dataset?
- Some column data like dates were not in understandable form to human eye.

(4) What are some other possible tables and/or graphs that we could create?
- We can create tables and/or graphs based on category and subcategory of the campaign.
- A box and whisker plot would be useful to compare the Outliners by category and months which represent that outliners are influenced by other factors. A graph that compares the category would also be helpful in determining what types of campaigns are more successful in various countries.

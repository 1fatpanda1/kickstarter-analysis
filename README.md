# kickstarter-analysis
Performance analysis on Kickstarter data to uncover trends
## Overview of Project
I am helping Louise analyze and understand the successes and failures of past theatrical crowdfunding campaigns. This will give her a better understanding on how to set up her own successful campaign. 
## Analysis and Challenges
I first looked at the data for past theatrical campaigns and created a pivot table and accompanying graph that shows the number of successful, failed, and canceled theatrical campaigns by month which can be filtered by year. 
![Theater_Outcomes_vs_Launch.png](https://github.com/1fatpanda1/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)
---
I then aggregated the number of successful, failed, and canceled plays based on their goal and charted those in the following chart.
![Outcomes_vs_Goals.png](https://github.com/1fatpanda1/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)
The main challenge was configuring the countif formulas for the Outcomes Based on Goals. I found the best way to organize the function was by searching for plays, then breaking down the limits by searching for the bottom limit first (greater than) and then the upper limit (less than) for the ranges in between two values. It was also easier to create the first column (number successful) and then copy and pasting those formulas and editing the successful/failed/canceled parameter.
## Results, Limitations, and Recommendations
Based on the graph created for Theater Outcomes by Launch date, the number of successful campaigns range from 37 to 111 per month with May showing the greatest number of successful campaigns. While the number of failed campaigns range between 33 and 52 per month, the number of failures is relatively even from May through September. This would imply the best month to launch a crowdfunding campaign would be May or June. When looking at the Outcomes Based on Goal graph, the most successful play campaigns have a goal of less than $1,000. 
The data set for Theater outcomes by Launch date is very limited for 2009-2013 and 2017, contributing only 57 out of 1,369 data points. Also, the data includes musicals and theater spaces which account for 327 of the data points (roughly 24%). It may be helpful to show the relative percentage of successful campaigns each month via a pie chart. For the Outcomes Based on Goal, a box and whisker plot filtered on successful campaigns with the same category and country as Louise would be beneficial in showing the mean successful campaign goal as outliers and interquartile ranges.  

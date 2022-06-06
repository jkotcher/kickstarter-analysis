# An Analysis of Kickstarter campaigns

## Overview
The purpose of this project was to help Louise determine the best approach to having a successful kickstarter campaign.  In order to do that we looked at past kickstarter campaigns and looked at several statistics to determine what made a successful campaign and what did not.  Some variables that we looked at as preliminary analysis was how the kickstarter campaigns faired based on the sub-category.  For this analysis we will focus on the goal amount that projects had set out and Launch date to see if a particular time of year had any impact on kickstarter campaigns.

## Analysis and Challenges

### Summary Statistics of campaigns based on the outcome
In the US for both the theater category and the plays subcategory there is a large number of successful kickstarter campaigns.  There are 412 successful campaigns for plays in the US.  Within the theater category more broadly there are 839 successful outcomes.  Taking a deeper dive into the data we found that the mean goal amount for successful campaigns was $5,049.  Whereas the mean for failed campaigns was $10,554.  The mean pledged for successful and failed respectively was $5,602 and $559.  The median goal for successful and failed was $3,000 and $5,000, respectively.  In addition, the median pledged amount was $3,168 for successful and $103 for failed campaigns.  According to the box and whisker plot in the UK the number of campaigns to receive funding was very small.  The median value according to this is below $2,000.

### Outcome based on Launch Date
As part of this analysis a pivot table was created to display outcomes based on the Launch date.  To do this the pivot table was created in excel and then a pivot chart was created.  According to the chart there was a large number of successful campaigns around the month of June and both starts lower and after the peak goes lower as well.

![Theater_Outcomes_vs_ Launch](https://user-images.githubusercontent.com/29406929/172162260-08d31f18-0b53-498b-a181-2128d98878a8.png)
Figure 1. Outcomes based on their launch date


### Outcome based on Goal
Looking at the outcomes now based on goal we created a table that could then be created into a chart to show percentage of each outcome.  The three outcomes that were looked at were successful, failed, and canceled.  This data was filtered based on plays specifically since Louise was planning to do campaigns for a play.  In Excel, the COUNTIFS function was used to populate the number of each outcome within a specific range.  Then for the total and percentage columns SUM was used, and then dividing the number of successful projects by the total to get the percent.  To start ranges were created so as to make it easier to group the projects into smaller bins as oppose to dealing with large groupings.  As is seen on the chart there is a grey line on the x-axis, which is representing the percentage of canceled projects.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/29406929/172164823-c37e3391-0cc0-4fc0-8afa-8f90b101bbfc.png)

### Challenges
Some challenges encountered while working on the project were related to chart creation and small technical errors within excel.  While trying to create the second deliverable there was an issue of trying to only use the specific columns needed.  Getting past that issue creating a chart with all the data and removing the data not needed worked to create the chart.  One technical issue discovered was that formula's in some cells had taken on other values from other cells when the same cell was to be used.  To correct this the formulas were manually changed in one cell and then applied to the whole column.

## Results

1. One conclusion that can be drawn from the outcomes based on launch date is that many of the successful projects occurred in the month of May.  This suggests that May is a good time for Kickstarter campaigns.  Another conclusion is that in the month of October there is no canceled campaigns and so projects that were plays were only either successful or failed in the month of October.
2. One takeaway from the outcomes based on goals is as the goal becomes higher the percent of successful and percent failed are opposite of where they started on the graph.  Percent successful is very high at the lowest goal range and is low at the highest goal range.  Something similar is true of percentage failed too.  At the low goal amounts the percent failed is low but as the goal range gets higher the percent failed is higher.
3. One limitation to the data is that for this analysis only plays were looked for one graph.  Also, there were four outcomes but only three were looked at in this analysis.  Something that would be helpful would be to maybe look at live projects in other subcategories within the Theater category.  Some of the preliminary analysis looking at outcome by category is also helpful because that can tell us which categories do well for the most part and which ones don't.  It can give a quick glance at what category to target if ever needing to start a kickstarter campaign.



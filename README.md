# An Analysis of Kickstarter Campaigns.
	
## Overview of Project

This project was designed to analyze a data set of previously completed kickstarter fundraisers in order to help my client,
Louise, make an informed decision on the parameters of her own kickstarter campaign. I wanted to provide Louise with information
about the success or lack thereof kickstarter campaigns based off of two criteria; the month of when the kickstarter was launched
and what was the goal amount each kickstarter was asking for.

## Analysis and Challenges

In order to provide helpful data to Louise I started with a kickstarter campaign data set that included all categories of campaigns
between 2009 and 2017.  Based on the data given in the set, I decided to focus on finding possible correlations between two separate criteria; 
which month of the year a campaign was launched and how much was their funding goal in relation to their success.

### Analysis of Outcomes Based on Launch Date

I first focused on analyzing the data between the launch date of the kickstarter and its outcome. Outcomes were defined as successful, failed or 
canceled by the creator of the kickstarter. I created a pivot table in order to properly display the relevant data to best suit the needs for Louise.
Since Louise will be fundraising for a play, I filtered the kickstarter campaigns to only include the parent category of theater. I did not what data
from other parent categories such as technology, games, or music which are not related to Louise's play, to distort my findings. Included below is
a pivot chart in order to better visualize the data found. The chart shows the number of successful, failed, and canceled theater campaigns based of
which month of the year it was launched.  Data available for theater outcomes consists of the years 2014 through 2016. 

![alt text](https://github.com/jseverin1984/kickstarter-analysis/blob/master/resources/Theater_Outcomes_vs_Launch.png "Outcomes based on launch date chart")

### Analysis of Outcomes Based on Goals

Second, I focused on analyzing the data between the goal amount of the kickstarter campaign and its outcome. Outcomes were defined as successful, 
failed or canceled by the creator of the kickstarter. After breaking the goals amount into 12 different ranges, I filtered the campaigns to only
show the outcomes for the subcategory of plays. This was done to better compare the overall data with Louise's kickstarter.  I used the countifs
function in Excel in order to group the outcomes into their respected goal ranges for only the subcategory of plays. Then I used that data to find
the percentages for successful and failed campaigns. There is no percentage for canceled campaigns because the data set did not have any play kickstarters
that were canceled. Included below is a pivot chart in order to better visualize the data found. The chart shows the relative percentage for successful
and canceled kickstarter campaigns based on which goal range they fell into.

![alt text](https://github.com/jseverin1984/kickstarter-analysis/blob/master/resources/Outcomes_vs_Goals.png "Outcomes based on goals chart")

### Challenges and Difficulties Encountered

Based on the data I was given and the analysis I was looking for, there were no challenges or difficulties that arose.  If asked to define a direct
correlation between certain data points would have been difficult because of having limited information and too many outlying factors that I will list
below.  Also, if Louise would have had a more niche project to fund, it may have been difficult to find relative campaigns within the data to compare to.


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

	1. Campaigns launched during the month of May had the most successful number of campaigns.
	2. Campaigns launched during the month of December had the least successful number of campaigns.

- What can you conclude about the Outcomes based on Goals?

	The data showed that campaigns asking a goal of 5000 dollars or less had the highest success rate of meeting their goals,
	while campaigns asking for more than that were the least successful and fully funding their goal.
	
- What are some limitations of this dataset?

	1. An incomplete dataset of all actual kickstarter campaigns.
	2. This is data just for kickstarter campaigns. Louise might find greater success on another fundraising website.
	3. Correlation between my variables may be difficult to conclude because of outlying factors such as world events when a campaign was 
	   launched, economic downturn or upturn, if certain campaigns got more outside promotion to help reach their goal.
	4. Could the early years of kickstarter campaigns have worse outcomes and skewed data because the website was new and
	   and a small target audience to receive donations from. 

- What are some other possible tables and/or graphs that we could create?

	1. You could compare how successful parent each parent or subcategory were against each other.
	2. Does the length of the title of a campaign have any significance on outcome.
	3. Compare how successful parent or subcategory campaigns were between years.

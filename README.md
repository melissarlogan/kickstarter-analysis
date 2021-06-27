# Kickstarting with Excel

## Overview of Project

The Kickstarting with Excel project assesses data from a wide variety of Kickstarter campaigns. This data set contains information on 1,393 theatre productions with goals surrounding content creation (musicals and plays) and production space development across 7 years (2010-2017). A focus was placed on theatre productions specifically concentrating on plays. This project reviews trends in variables that could impact whether a campaign was deemed successful or not and ways a production could improve the likeliness that their campaign will be successful.

### Purpose

This project has been created to assist Louise in seeing how other fundraising campaigns performed in relation to their fundraising goals and their respective launch dates. 


## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

Below in Image 1- Theatre Outcomes Based on Launch Date the graph is showing how many theatre productions had successful, cancelled , or failing outcomes based on the month in which their campaign was launched. Kickstarter campaigns that are currently live have been excluded from this analysis as their results are not finalized.

Image 1- Theatre Outcomes Based on Launch Date shows that in May and June there is a spike in successful outcomes in campaigns that were launched during those months. While these months typically have higher success rates Image 1- Theatre Outcomes Based on Launch Date shows that in all months of the year there are more successful campaigns than failed campaigns. This spread in successful and failed campaigns narrows significantly in December where the two datapoints are extremely close where the number of campaigns that are deemed successful and failed are almost equal.

Image 1- Theatre Outcomes Based on Launch Date also shows an increase in campaigns that failed from May-August, a decrease in September, and then returning to similar failing amounts in October  before decreasing again for November-March. This failed line follows a similar track as the successful line, peaking and dipping in corresponding months.  

#### Image 1- Theatre Outcomes Based on Launch Date 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/85718354/123523400-415abe00-d691-11eb-883c-e36438a2b0a3.png)

### Analysis of Outcomes Based on Goal

Image 2- Outcomes Based on Goal is showing the fundraising goal and what percentage of campaigns with those goals were considered successful or failed as there were 0 cancelled plays.

Where the successful and failed lines intersect is showing that for campaigns with a goal between 15,000 and 19,999,  50% of them succeed and 50% fail. Fundraising targets below this point (<15,000) are more often a success. As the fundraising goals increase we can see the fail rate also increases, to a peak of 80% in the 25,000-29,999-goal range. 

It is noted that the fail rate decreases at the 35,000-39,999 and 40,000- 44,999 ranges where campaigns in these ranges are more likely to be successful, but above the 44,999 range there is a large increase in the probability that the campaign will fail. This discrepancy in the data is discussed more in [the dataset limitations section](#dataset-limitations) as this change is because of limited campaigns with fundraising goals that high. The most relevant data, with the larger number of data points, is for campaigns that have a fundraising goal of less than 9,999.

#### Image 2- Outcomes Based on Goal

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/85718354/123523856-a19f2f00-d694-11eb-8899-116d85e59a25.png)

### Challenges and Difficulties Encountered
Some challenges that were encountered when creating this data set are listed below along with how they were overcome:
Challenges

- Ensuring that the  data is being pulled correctly from the master list into the summary lists which helped create the graphs where multiple pulling formulas needed to be written.
   - This issue was overcome by once a formula was written, using the lock function on the formula to make the references remain static, so when dragging formulas to cover a wider array of information the references did not change.
- When creating formulas that are pulling the same information except changing the reference point from “successful” to “failed” there is the risk when doing it manually that some formulas get missed and an incorrect references are pulled
    - This was overcome by using the find+replace function in excel and highlighting the changing range. This allowed the references to change in bulk while also ensuring each formula reference was correctly changed . 

## Results

#### Outcomes based on Launch Date Results

We can conclude that the most promising time to launch a campaign would be when the gap between the lines is greatest (May and June) as this is showing that while there are more total campaigns launched, more often these campaigns launched in this period are deemed successful.

We can also conclude that December is the worst month to launch a campaign as this is when campaigns launched that were successful are that their lowest.

#### Outcomes based on Goals Results 
	
What we can conclude from the Outcomes based on Goals that as campaigns increase their fundraising goals they are less likely to achieve those goals. The most successful range for a campaign is when the fundraising goals are  between less than 1,000 and 4,999.


### Dataset Limitations

With the data and analysis above, there are some limitations:

The data is focused on campaigns deemed successful or failures. The above analysis does not regard the amount in which a campaign failed. This datapoint could be helpful in determining if some failing plays were extremely close to hitting their goal, as perhaps additional funding could have been secured from an alternative source to allow these plays to come to life. 

The data above also does not bring into consideration the length of time a campaign was launched. It would be beneficial to see if campaigns that are live longer are able to raise more funding or if shorter campaigns are able to push urgency in getting their goals met.

As mentioned in [the analysis of outcomes based on goals section](#analysis-of-outcomes-based-on-goals) we are missing a discussion on how many data points have been collected for various goal ranges in speficiation to theatre plays. It is important to note population size when analyzing data as a 50%/50% split when there are only 2 data points compared to 500 data points can indicate a stronger trend and provide more confidence in the results.

#### Additional Graphs
Other tables we could create could be:
1. A line chart showing time trends of how funding goals and success rates have changed over the years. What have plays launched more recently experineced?
2. How the % funded averages move over the months of the year displayed in a barchart, are campaings more likley to hit 90% funded in a particular month?
3. A line chart on how the amount of pledged money varies over length of the campaign. If a campaign is live longer do they typically raise more money?

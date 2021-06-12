# Kickstarting with Excel

## Overview of Project
To Create two Charts called "Theater Outcome By Start Date" and "Outcomes based on Goals"

### Purpose
My Stakeholder Louise’s recently watched a Play called "Fever" It was awesome, exciting but most importantly It made a profit. Louise wants to find out how different campaigns fare based on their launch date and funding goals. I must return my findings and submit a report to Louise.

## Analysis and Challenges
Pivot Table
Filter Parent category = theater
Formula =CountIfs, Sum


### Analysis of Outcomes Based on Launch Date
May is the best time to plan a campaign for theater. 
Oct is the worst time to plan a campaign for theater.

### Analysis of Outcomes Based on Goals
As Request for larger sum of Money increases, chance of Success decrease. Sweet Spot is around 15-19k. Data is skewed regarding larger sums. Could be fixed by including more rows. Perhaps increasing the timeline of the data to larger than 17 years. 

### Challenges and Difficulties Encountered

I was using "countif" and failing on the formula. I Got frusterated and just decided to manually added those numbers by filtering and sorting by subcategorie. Turns out thats not acceptable. Gotta be "CountIfs" with a "S" So I Decided to click the hint and watch the video about Countifs. Mega Face palm and re-did the entire spreadsheet correctly. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
- May Is the best month to host a Play. You will have most success at this time period
- Oct is the worst month to host a Play. You will have most difficulties at this time period. 

- What can you conclude about the Outcomes based on Goals?
- There is a 75% chance you will be successful with a goal less than $1000, this X axis decreases as you ask for more money in the Y Axis. 
- 25,000-29,000 is one major no go zone. 
- While 40,000-44999 may look like a bullish zone with 66%. This can be decieving as it only encouroprates 4 rows of data. If we had a larger timeline of data, perhaps we can get a clearer understanding of larger the outcome of larger donation goals. 

- What are some limitations of this dataset? 
- Time, we are only able to see 8 years worth of Data. From 2009 - 2016
- Fewer Datapoints as donation nunbers get larger. It can Skews our chart. 
- I tried doing a IQR in another sheet to understand how skewed our observation is. Successful scored a 27.25 IQR and failed scored a 16.5IQR. Successful has a larger standard deviation. 

- What are some other possible tables and/or graphs that we could create?
- a Simple Stacked Bar chart with the sum of Goal and Sum of Pledge $ Would be nice to look at. That way I can quickly glance and understand which Project (name) overachieved or underachieved their goals
- Maybe a Sankey chart to understand the total amount of money, and which countries contribute the most
- Perhaps a Timeline chart with each catagories as a line, perhaps we can justify when to put more budget into which avenue. If theaters are bullish in APR, May, June. While Film and video are bearish in APR, May June, Film and video does not need money for that 3 month.  We can more accurately adjust our budget to this outlier and get the maximum out of our spend. 

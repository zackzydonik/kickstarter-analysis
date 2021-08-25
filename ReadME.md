# Kickstarting with Excel

## Overview of Project

### Purpose

Kickstarter data has been gathered for various fundraising campaigns . These The purpose of this analysis is to investigate how different campaigns falling within the plays subcategory performed based on their launch dates and funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

The analysis was performed using excel. To investigate the efficiency of campaigns by launch date, a pivot table was created which provided a count of successful, failed and canceled campaigns in each month.

### Analysis of Outcomes Based on Goals

When looking into outcomes based on goals, the SUMIFS() function was used to evalute goal ranges from 1000 to 50000 in 50000 increments. A line chart was used to display the percentage that were successful, failed or canceled based on the goal range.

### Challenges and Difficulties Encountered

One thing that was challenging was copying the formulas into adjacent cells when changing the filter from successful to failed or canceled. I found that using the find and replace feature made it easy replace "successful" with "failed" allowing the forumla to query the new variable more quickly than if I had gone through each column and manually replaced the value.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

The most successful campaigns were launched in the month of May. The number of cancelled campaigns is very low compared to the total number and there are more successful campaigns than failed campaigns indicating that launching a campaign in the theater category may prove to be fruitful.

- What can you conclude about the Outcomes based on Goals?

The percentage of successful campaigns generally decreases as the gaol amount increases and vice versa for the percentage failed. There were no canceled campaigns in the plays subcategory.

- What are some limitations of this dataset?

Limitations of this dataset are plentiul. One such example is that only campaigns launched on Kickstarter are included: there are many other fundraising platforms that may be used to launch campaigns and those entries are not reflected here.

- What are some other possible tables and/or graphs that we could create?

We could create a pie charts that show the percentage of successful, failed and cancelled campaigns overall and for each category we are interested in. We may also wish to create a distribution chart for the data to see if the data is skewed right or left or else normally distributed.

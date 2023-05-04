# Research on A/A/B experiment and event funnels

I recommend checking out the project at [the following link](https://nbviewer.org/github/YarValerievich/Project2_AAB-test_sales_funnel/blob/main/Project2_AAB-test_sales_funnel.ipynb).

## Purpose: 

Based on the initial data, determine how users reach the purchase stage, how many users actually complete a purchase, and how many get stuck at previous steps.

## Description: 

Before analyzing the A/B test, data preparation was conducted, including column renaming, checking for missing values and duplicates, as well as splitting the timestamp column into date_time and date. During the exploratory data analysis, the total number of events and users in the log was calculated.

## Result:

The majority of users are lost when transitioning from the main screen to the offer screen, specifically 62%.

Overall, 48% of users made it from the main screen to the payment stage in all three groups. In group 246, 1200 users made it to the payment stage - 48% of the total. In group 247, 1158 users made it to the payment stage, 46% of the total. In group 248, 1181 users made it to the payment stage, 47% of the total.

To calculate the significance of the statistical differences among samples 246, 247, and 248, 12 statistical tests had to be conducted.

It is recommended to focus on improving the quality of user transitions from the main screen to the offer screen.

## Stack of technologies: 

- python
	- pandas
	- numpy
	- math
	- plotly
	- scipy
	- pyplot
- A/A/B-testing
- statistical hypotheses testing

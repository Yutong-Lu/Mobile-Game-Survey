# STA304 - Fall 2021 Assignment 1
**Author:** Yutong Lu 1005738356

## Overview
This survey explores the impact of the COVID-19 pandemic on the spending behaviors of mobile game players in Canada, focusing on in-game purchases.

## Objectives
- Investigate changes in monthly spending on in-game purchases and weekly gameplay time before and after the pandemic.
- Examine the influence of the pandemic on players' engagement with profitable online gaming platforms.

## Methodology
### Survey Distribution
- Targeted surveys distributed via multiple online platforms including gaming forums, social media, and video websites.
- Aimed to reach a broad spectrum of mobile gamers in Canada.

### Target Population
- Focus on active mobile game players in Canada with in-game purchase options.
- Consideration of changing demographics due to migration and varying gaming habits.

### Sampling Strengths and Drawbacks
- Online distribution enables rapid reach but may introduce biases such as over-representing active online community members.
- Possible underrepresentation of certain age groups and casual gamers.

## Key Questions
### Financial Impact
- Monthly spending on in-game purchases pre- and post-pandemic.

### Engagement with Gaming Platforms
- Involvement with platforms like Twitch and YouTube for gaming content creation or consumption.

### Perception of Pandemic Severity
- Personal assessment of COVID-19 impact in the respondent's area.

## Data Simulation
- Utilized R for simulating 200 observations with 11 variables, reflecting potential survey responses.
- Incorporated both numerical and categorical data, with assumptions based on existing literature.

## Data Cleaning
- Categorization of income levels and adjustment of any negative values in simulated data.

## Important Variables
- `money_diff`: Change in monthly in-game spending due to the pandemic.
- `time_diff`: Difference in weekly gameplay time pre- and post-pandemic.
- `platform`: Engagement with gaming-related online platforms.
- `severity_level`: Perceived severity of COVID-19 in the respondent's area.

## Results
### Hypothesis Testing and Confidence Interval
- Examined the average difference in gameplay time and monthly spending using t-tests.
- Constructed a 95% confidence interval for the true mean of differences in monthly spending.

## Conclusions
- Significant increase in average monthly spending on in-game purchases post-pandemic.
- Inconclusive results regarding changes in weekly gameplay time.
- Insights into the relationship between pandemic impact and mobile gaming behaviors.

---
[Link to the survey](https://docs.google.com/forms/d/e/1FAIpQLSeWViqOY5-jKN7r_3Fi7P_A7IhvBP3113SfRdHczGljLJ9WEw/viewform)

_Analysis performed using R version 4.0.2. Plots and tables created with Tidyverse, knitr, and kableExtra._

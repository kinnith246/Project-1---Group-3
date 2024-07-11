# Project-1---Group-3

Proposal: Does having a Fitbit inspire people to meet the recommended exercise guidelines

Project Overview
Project Name: 

Team: Group 3

Introduction
With the introduction of fitness apps and gadget, 


Objectives:
Data Cleaning and Preparation
1. Are there any missing or duplicate entries in the dataset? How can they be handled?
2. How can you handle outliers in the dataset, especially in TotalSteps or Calories?
3. Is there a need to normalize or standardize any columns for better analysis?

# Activity and Distance Analysis (Ken)
1. What is the correlation between Active Distance and Active minutes across different activity levels?
2. What is the distribution of TotalSteps against TotalActiveMinutes and how does it compare to TotalActive Distance vs. TotalActiveMinutes?
3. Is there a significant difference in the average active distances (Light, Moderate, and Very Active) between the first 7 days and the last 7 days of the survey to see if users improved over the duration of the survey?


# Time-Based Analysis (Cathy)
1. How do TotalSteps vary by day of the week?
   -You may need to extract the day of the week from ActivityDate.
2. What is the trend of TotalSteps over time?
  - Plot TotalSteps over the range of ActivityDate.
3. Is there a particular time period with higher VeryActiveMinutes compared to other periods?
4. Timeseries of how their exercise varied throughout the month


# Calorie Analysis (Sima)
1. What is the relationship between TotalSteps and Calories burned?
2. Which activity (Very Active, Fairly Active, Lightly Active, Sedentary) contributes most to calorie burn?
3. Is there a significant difference in the percentage of activity levels based on activity minutes?


# User engagement with 10,000 steps marketting, and is 10,000 steps a good metric? (Aisling)
1. How many entrees successfully achieved 10,000 steps or more per day?
2. What percentage of individual users achieved 10,000 steps?
3. What is the average steps completed?
4. How does each individuals average compare to 10,000 step goal?
5. what is the relationship between those that met the 10,000 steps and those that achieved 30 minutes of moderate exercise?

# Advanced Analysis
Statitistical summaries and tests
2. Is there a significant difference in the percentage of activity levels based on activity minutes?
All p-values are very low (0.0000), suggesting strong evidence against the null hypothesis.
This indicates significant relationships between each pair of activity metrics tested, such as TotalSteps vs TotalDistance, TotalSteps vs Calories, etc.

3. Is there a significant difference in the average active distances (Light, Moderate, and Very Active) between the first 7 days and the last 7 days of the survey to see if users improved over the duration of the survey?
This was tested with a t-test across the different activity levels and was found that the t-statistics were relatively low which showed there was no significant differences from the start to the end. Hence, within the time timeframe there was no improvement.

4. What is the distribution of activity levels by step?
This can be examined by comparing to an even distribution using a Chi-squared test. If we then do this for the Australian Bureau of statistics data, we can then see if our user activity levels are comparable to the Australian general population. 


Visualization
1. Create visualizations to show the distribution of TotalSteps among users.
2. Plot Calories burned against VeryActiveMinutes to see the relationship.
3. Visualize the average TotalSteps by day of the week.
4. Visualise total steps vs 10,000 step goal 

Key Questions:


Outcome:


References:
https://www.kaggle.com/datasets/arashnic/fitbit
https://www.kaggle.com/datasets/mjazzy/fitbit-fitness-bellabeat-high-tech-company
https://www.abs.gov.au/ausstats/abs@.nsf/Lookup/4156.0.55.001main+features4Nov%202013




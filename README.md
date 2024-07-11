# Project-1---Group-3
# MAIN GROUP CODE file name: "Group 3 NB.ipynb" found in Dataset
# Does Fitbit inspire users to exercise? 
Proposal: Does having a Fitbit inspire people to meet the recommended exercise guidelines? Does it inspire people to exercise more than the general public? 

Team: Group 3

Project members:
- Cathy Matthee
- Sima Moghadam
- Aisling Geraghty
- Kenneth Le

# Introduction
With the introduction of fitness apps and gadget, Fitbit trackers are ubiquitous in society today, tracking sensitive information such as age gender and geolocation which in the wrong hands can be used maliciously. Need to ensure to seek de-identified user data responsibly and carefully.

# Objectives:
Data Cleaning and Preparation
1. Are there any missing or duplicate entries in the dataset? How can they be handled?
2. How can you handle outliers in the dataset, especially in TotalSteps or Calories?
3. Is there a need to normalize or standardize any columns for better analysis?

# Activity and Distance Analysis (Ken)
1. What is the correlation between Active Distance and Active minutes across different activity levels?
2. What is the distribution of TotalSteps against TotalActiveMinutes and how does it compare to TotalActive Distance vs. TotalActiveMinutes?
3. Is there a significant difference in the average active distances (Light, Moderate, and Very Active) between the first 7 days and the last 7 days of the survey to see if users improved over the duration of the survey?

# Time-Based Analysis (Cathy)
1. How do minutes exercised vary by day of the week and specifically weekdays to weekends?
2. What is the trend of minutes of activity over the course of the study for single Fitbit users VS. multiple users?
3. What levels of exercise contributes to the minimum 150 minutes recommended guideline? And how does this compare to the Australian population data according the ABS?


# Calorie Analysis (Sima)
1. What is the relationship between TotalSteps and Calories burned?
2. Which activity (Very Active, Fairly Active, Lightly Active, Sedentary) contributes most to calorie burn?
3. Is there a significant difference in the percentage of activity levels based on activity minutes?


# User engagement with 10,000 steps marketting, and is 10,000 steps a good metric? (Aisling)
1. How many entrees successfully achieved 10,000 steps or more per day?
2. What percentage of individual users achieved 10,000 steps?
3. What is the average steps completed?
4. How does each individuals average compare to 10,000 step goal?
5. What are the activity levels like with step brackets?
6. What is the distribution of activity levels by steps, and how does this compare to the general population in Australia?

# Advanced Analysis 
Statitistical summaries and tests

1. How do minutes exercised vary by day of the week and specifically weekdays to weekends?
This can be explored by randomly splitting the data into 2 independent groups. After establishing normality, attending to independence and using a Welch's t-test where variance equivalence was not established, can conduct an independent t-test to see if it is statistically significant that users engaged in exercise more on weekends.

2. What is the impact of different levels of physical activity (VeryActiveMinutes, FairlyActiveMinutes, LightlyActiveMinutes, SedentaryMinutes) and TotalSteps on calorie burn?
we perform exploratory data analysis (EDA). Conduct simple linear regression with Calories as the dependent variable and TotalSteps as the predictor, followed by multiple regression including VeryActiveMinutes, FairlyActiveMinutes, LightlyActiveMinutes, and SedentaryMinutes. Evaluate the models, perform hypothesis testing to determine significance, and interpret the results, providing a concise report of findings and recommendations.

3. Is there a significant difference in the average active distances (Light, Moderate, and Very Active) between the first 7 days and the last 7 days of the survey to see if users improved over the duration of the survey?
This will be tested with a t-test across the different activity levels to find if there was any significant differences from the start to the end to see if there are any improvements.

4. What is the distribution of activity levels by step?
This can be examined by comparing to an even distribution using a Chi-squared test. If we then do this for the Australian Bureau of statistics data, we can then see if our user activity levels are comparable to the Australian general population. 


Visualization
1. Create visualizations to show the distribution of TotalSteps among users.
2. Plot Calories burned against VeryActiveMinutes to see the relationship.
3. Visualize the average TotalSteps by day of the week.
4. Visualise total steps vs 10,000 step goal 


Outcome:
Determine whether fitbit inspires users to exercise: 
Investigate this with the sub-questions: How do fitbit users compare to the general public, how they vary compared to one another, when are they more likely to exercise, whether they improve over time, and do they meet their daily exercise guidelines?
Generate answers that provide advice to Fitbit to improve their product and evaluate the limitations of the data and further studies that could be done. 


References:
https://www.kaggle.com/datasets/arashnic/fitbit
https://www.kaggle.com/datasets/mjazzy/fitbit-fitness-bellabeat-high-tech-company
https://www.abs.gov.au/ausstats/abs@.nsf/Lookup/4156.0.55.001main+features4Nov%202013
https://www.10000steps.org.au/articles/healthy-lifestyles/counting-steps/



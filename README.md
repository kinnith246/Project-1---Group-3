# Project-1---Group-3
# MAIN GROUP CODE file name: "Group 3 NB.ipynb"
# Does Fitbit inspire users to exercise? 
Proposal: Does having a Fitbit inspire people to meet the recommended exercise guidelines? Does it inspire people to exercise more than the general public? 

Team: Group 3

Project members:
- Cathy Matthee
- Sima Moghadam
- Aisling Geraghty
- Kenneth Le

Introduction
With the introduction of fitness apps and gadget, Fitbit trackers are ubiquitous in society today, tracking sensitive information such as age gender and geolocation which in the wrong hands can be used maliciously. Need to ensure to seek de-identified user data responsibly and carefully.

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
5. what is the relationship between those that met the 10,000 steps and those that achieved 30 minutes of moderate exercise?

# Advanced Analysis
Statitistical summaries and tests

1. How do minutes exercised vary by day of the week and specifically weekdays to weekends?
This can be explored by randomly splitting the data into 2 independent groups. After establishing normality, attending to independence and using a Welch's t-test where variance equivalence was not established, can conduct an independent t-test to see if it is statistically significant that users engaged in exercise more on weekends.

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


Outcome:
Overall,
We found that users were more inclined to work out on the weekend, suggesting Fitbit should work on weekday user engagement and encouragement, as well as investigate why this is the case. 

Fairly active to very active minutes and steps correlate to higher calorie burn, and are the recommended daily activities of Fitbit, with a focus on the 10,000 step goal. A higher percentage of users met daily exercise guidelines by minutes than the average population. However, when using the step count as a metric for activity, the levels of activity appeared similar to the general population. Additionally we found that user’s didn’t improve their activity over time. 

Therefore, we conclude that Fitbit does inspire people to meet exercise guidelines, but further inspiration is required from Fitbit to encourage users to maintain higher levels of activity, or to be improving over time. This would differentiate Fitbit users more clearly from the general public, and enhance the quality of the application service. 

We suggest that Fitbit reframe their use of goals and consider taking a personal approach for users. A personal approach would take into account the user’s initial fitness, and then focus on time-bound goals that individuals can aspire to. 

Next steps: From here, we could investigate this further with a stronger dataset by collecting our own research population data. We could do this using Fitbit web API with users’ express consent, so that we can look at more variables that are relevant to improving the Fitbit product. 

References:
https://www.kaggle.com/datasets/arashnic/fitbit
https://www.kaggle.com/datasets/mjazzy/fitbit-fitness-bellabeat-high-tech-company
https://www.abs.gov.au/ausstats/abs@.nsf/Lookup/4156.0.55.001main+features4Nov%202013




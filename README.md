# Aerobic-Anarobic

# QTM 151 Final Project Report

Team Name: Healthy Girls. 
Members: Sirui Hu,Sizhu Jiang,Meredith Jin,Joyce Liu, Fang Zhou

# Introduction
Maintaining a healthy status is always our life-long goal and many students are seeking a more efficient and effective way to exercise. We are interested in which exercise type is better for health condition. Therefore, we set up our research question “cardio exercise and strength training, which is better for our health condition?” We aim to determine the correlation between the number of days within a week people do cardio exercise versus strength training and comparing their health status. We could then infer which kind of exercise more beneficial and effective in terms of improving general health conditions.

# Data and Method
We picked the data files “Current Health Status” and “Physical Activity” under the provided questionnaire data from 2015 to 2016. We chose General Health Condition (HSD010) as our outcome variable. And past week number of days cardiovascular exercise (PAQ677), and past week number of days strengthened muscles (PAQ678) as our independent variables. The R packages we mainly utilized are: tidyverse, forcats, Hmisc and ggplot. We first join the two different data sets by left join and then filter out NAs. We mutate the health condition variable into different levels and then calculate the average workout days. After that, we constructed a bar graph for cardiovascular exercise and a line graph for strength exercise to demonstrate the correlation. 

# Result and Analysis
The first graph demonstrates the correlation between past week number of days doing cardiovascular exercises and current health condition. The y-axis represents different levels of current health condition, and the x-axis represents average number of days in a week for people of each health condition. We found that people with poor health condition practice cardiovascular exercises around 2.3 days a week. The days for people in fair, good, very good, and excellent conditions are about 3.09, 3.33, 3.58 and 3.63. The bar graph generally follows an upward trend with a gap between that for poor and fair condition. People with poor health condition may have trouble doing cardiovascular exercises, causing the number of days to be far less. The whole trend shows that as frequency of cardiovascular exercises increases, people’s health conditions also improve. 

The second graph has similar x-variable—number days of past week doing strengthened muscle exercises, and the same y-variable—current health condition (in score from 1 to 5, with 1 as poor and 5 as excellent). However, from the graph we found that except the group with poor condition who have a near-zero average frequency of strengthening muscles, others group all have average days around 2.5. There is no clear difference as the points cluster. The correlation between doing strengthening-muscle exercises and health condition is not strong. 

# Conclusion: 
From the graphs and the interpretation, we can conclude that the correlation between cardio exercises and health is much stronger than that between strength exercises and health. Although we couldn’t derive the effectiveness of the exercises from the result, we can infer that cardio exercises are more effective for people’s health condition. We should do more exercises to develop wellness for our study and work.

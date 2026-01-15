# Case Study: How Can a Wellness Technology Company Play It Smart?

## Introduction

This project is the capstone assignment for the [Google Data Analytics Professional Certificate](https://www.coursera.org/professional-certificates/google-data-analytics) program. The program prepares participants for a career in data analytics with training focused on key analytical skills (data cleaning, analysis, and visualization) and tools (Excel, SQL, R Programming, Tableau).

We'll be investigating data sets of FitBit usage to make high-level marketing recommendations for Bellabeat---a high-tech company that manufactures health-focused smart products.

## Contents 

- [Summary](#summary)
  - [Tools and Techniques](#tools-and-techniques)
  - [Recommendations](#recommendations)
- [Full Case Study](#full-case-study)
- [Contact](#contact)

## Summary

[Bellabeat](https://bellabeat.com/) was founded in 2013 and has grown to become a tech-driven wellness company for women. Since 2016, they have opened offices around the globe and launched multiple products. Their apps and devices collect data on activity, sleep, stress, and reproductive health, allowing Bellabeat to empower women with knowledge about their own health and habits.

Bellabeat also offers a subscription-based membership program for users. Membership gives users 24/7 access to fully personalized guidance on nutrition, activity, sleep, health and beauty, and mindfulness based on their lifestyle and goals. There products include: 

- **Bellabeat app**: The Bellabeat app provides users with health data related to their activity, sleep, stress, menstrual cycle, and mindfulness habits. This data can help users better understand their current habits and make healthy decisions. The Bellabeat app connects to their line of smart wellness products.
- **Leaf**: Bellabeat's classic wellness tracker can be worn as a bracelet,
necklace, or clip. The Leaf tracker connects to the Bellabeat app to track activity, sleep, and stress.
- **Time**: This wellness watch combines the timeless look of a classic
timepiece with smart technology to track user
activity, sleep, and stress. The Time watch connects to the Bellabeat app to provide you with insights into your daily wellness.
- **Spring**: This is a water bottle that tracks daily water intake using smart technology to ensure that you are appropriately hydrated throughout the day. The Spring bottle connects to the Bellabeat app to track your hydration levels.

### Guiding questions

The guiding questions for this case study are as follows: 

- What are some trends in smart device usage?
- How could these trends apply to Bellabeat customers?
- How could these trends help influence Bellabeat marketing strategy?

### Tools and Techniques

The following analysis makes use of the following tools and techniques: 

- R programming language and libraries; `ggplot2`, `tibble`, `tidyr`, `readr`, `purrr`, `dplyr`, `stringr`, `lubridate` and `forcats`
- Data transformations: joins, visualizations, summary statistics
- Data inspection: removal of duplicate/unnessary data, change format/datatype, verify unique values

### Recommendations

Based on the analysis, here are the recommendations:

- Double the Points Earned on Sundays
- Reminder Notifcations Following Active Days
- Encourage Rest Days

#### Double the Points Earned on Sundays

Based on the observations from the data, the largest trend that stands out is the increase in activity on Tuesday, Wednesday, and Thursday. Participants were most active on these days (both in terms of step count and calories burned). These also coincided with the days participants got the most sleep and spent the most time in bed. Further, we also know that Sunday is the least active day. 

In order to help Bellabeat customers reach their wellness goals, it is recommended that the product team implement the ablity to add reminders when customers have lower level of activities. In particular, if we know that Sunday (and indeed Friday and Satury to some degree) is the least active day the product team could add the ability for customers to increase their wellness score by more points when they are active on Sunday. For example, perhaps activities on Sundays count for 1.5 times or 2 times the regular amount of points awarded when calculating the Wellness Score. This is intended to incentivize customers to be more active on this day.

#### Reminder Notifcations Following Active Days

We know that Tuesday, Wednesday, and Thursday are the most active days. The product team could implement notifications on the following days. These notifications could include reminders about how active the individual has been the past day (or previous days) and offer encouragement to keep staying active. 

#### Encourage Rest Days

The Wellness Score in the Bellabeat app is a number calculated on a number of different factors, including activity. We know from the data that Sunday is the least active day. Perhaps, instead of encouraging individuals to be active on this day, rest should be encourage. Bellabeat takes a hollistic approach to wellness and while it is important to be active when achieiving fitness goals rest is also an important factor. In this case, perhaps the activities on Sundays (or on another rest day specified by the customer) would count for silently less so that the overall Wellness Score isn't adversely affected.

## Full Case Study

The full case study can be viewed at the following places: 
- [my portfolio website](https://ananfito.github.io/case-study_bellabeat/bellabeat.html)
- [Kaggle](https://www.kaggle.com/code/anthonynanfito/case-study-how-can-a-wellness-technology-company) 
- [RPubs](https://rpubs.com/anthonynanfito/bellabeat) 

## Contact
- <a href="mailto:msg.for.anthony.p6ht3@simplelogin.com?subject=Nice Case Study Project&body=Hey Anthony, I saw your Case Study. Let's talk!">Email</a>
- [LinkedIn](https://www.linkedin.com/in/anthonynanfito/)
- [GitHub](https://www.github.com/ananfito)
- [Portfolio](https://ananfito.github.io)

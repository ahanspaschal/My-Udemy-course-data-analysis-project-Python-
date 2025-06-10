# 📊 Udemy Course Data Analysis Project

## 🔍 Overview
This project involves an exploratory data analysis (EDA) on a real-world Udemy course dataset using Python (Pandas, Matplotlib). The dataset includes key attributes such as course price,
subject category, subscriber count, course level, content duration, and whether the course is free or paid.
The aim is to uncover insights that can help maximize revenue and increase course subscriptions based on user preferences and course performance metrics.

## 🧠 Project Objectives
* Determine subscriber trends across different subjects.

* Analyze the distribution of free vs. paid courses per subject.

* Investigate how content duration, price, and popularity vary by subject.

* Evaluate the average price of web development courses by course level.

* Identify the top 20 most popular courses, including their:

  Level

  Free or paid status

  Duration

  Whether they are beginner-friendly and free

  Assess the relationship between content duration and:

  Course price

  Number of subscribers

## 🧰 Tools & Technologies
Python 3

Pandas – Data manipulation

Matplotlib – Data visualization

Jupyter Notebook – Analysis environment

## 🔄 Data Preparation Steps
Loaded the dataset using pandas.read_csv()

Cleaned the data:

Dropped empty and irrelevant columns

Created new columns (e.g., free_or_paid) for categorization

Converted incorrect data types (e.g., Price and Content Duration)

Performed groupby aggregations to compute averages and totals

Built visualizations (bar plots, pie charts) to enhance interpretation

## 📊 Key Insights
### Subject & Subscriber Trends
Web Development dominates with 68% of all subscribers, confirming its popularity and commercial viability.

Business Finance and Musical Instruments have significantly fewer subscribers.
### Pricing Patterns
Web Development courses have the highest average price.

Musical Instruments are the cheapest and least subscribed.
Course Accessibility
Certain subjects offer a good balance of free and paid courses.

Free beginner-level courses exist but are rare among the top courses.

### Content Duration vs. Pricing
No meaningful correlation between content duration and price.

Similarly, duration does not strongly impact number of subscribers — indicating user interest and subject matter are more critical.

### Top 20 Courses (Sample View)
Majority are web development courses.

Levels vary from beginner to expert, with a few free beginner options.

These courses tend to have longer durations and high engagement rates.









## SUMMARY OF FINDINGS
1) After carefully analyzing the dataset, it was observed that about 68% of total subscribers in udemy went for web development courses. And also the top five most subscribed courses are web development courses.
2) It was also observed that on average, web development courses are the most expensive, and has the longest content duration.
3) On a closer look, it was observed that on average, musical instrument courses are the cheapest, have the shortest duration of content, but still has the least number of subscribers.
4) It can be confirmed that content duration have no impact on the price of course, as well as the number of subscibers.
5) Subscribers are willing to pay higher and spend longer time on a course. What matters most id their choice of interest. 

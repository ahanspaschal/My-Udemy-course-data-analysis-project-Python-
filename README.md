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
* Python 3

* Pandas – Data manipulation

* Matplotlib – Data visualization

* Jupyter Notebook – Analysis environment

## 🔄 Data Preparation Steps
* Loaded the dataset using pandas.read_csv()

* Cleaned the data:

* Dropped empty and irrelevant columns

* Created new columns (e.g., free_or_paid) for categorization

* Converted incorrect data types (e.g., Price and Content Duration)

* Performed groupby aggregations to compute averages and totals

* Built visualizations (bar plots, pie charts) to enhance interpretation

## 📊 Key Insights
### Subject & Subscriber Trends
* Web Development dominates with 68% of all subscribers, confirming its popularity and commercial viability.
* Business Finance and Musical Instruments have significantly fewer subscribers.

![subscriber distribution](https://github.com/ahanspaschal/My-Udemy-course-data-analysis-project-Python-/blob/main/subscriber%20distribution.png)

### Pricing Patterns
* Web Development courses have the highest average price.

* Musical Instruments are the cheapest and least subscribed.
* Course Accessibility
* Certain subjects offer a good balance of free and paid courses.

* Free beginner-level courses exist but are rare among the top courses.

### Content Duration vs. Pricing
* No meaningful correlation between content duration and price.

* Similarly, duration does not strongly impact number of subscribers — indicating user interest and subject matter are more critical.

### Top 20 Courses (Sample View)
* Majority are web development courses.

* Levels vary from beginner to expert, with a few free beginner options.

* These courses tend to have longer durations and high engagement rates.

## 💡 Recommendations
### Focus on High-Demand Subjects:

* Prioritize Web Development and similar tech-driven subjects for new course creation.

### Reassess Pricing Strategy:

* Content length alone doesn't justify higher prices. Focus instead on value and quality of subject matter.

### Offer Free Starters:

* Providing more free beginner-level courses could improve platform adoption and lead to higher paid conversions.

### Leverage Course Popularity Metrics:

* Highlight and promote top-performing courses as case studies for new creators.










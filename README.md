# Google Play Store Apps Analysis

This repository contains an exploratory data analysis (EDA) project focused on analyzing Google Play Store apps data. The Play Store is a significant platform for Android app developers, offering vast potential for app-making businesses to thrive. By extracting actionable insights from the available data, developers can gain valuable knowledge to capture the Android market successfully.

## Problem Statement
The objective of this project is to explore and analyze the Google Play Store apps dataset, which includes information such as category, rating, size, and more. Additionally, a dataset containing customer reviews of the Android apps is provided. The goal is to discover key factors that contribute to app engagement and overall success.

## Summary and Conclusion
Google Play Store is renowned as one of the largest and most popular Android app stores worldwide. With its extensive collection of apps and a wealth of data, it presents an optimal opportunity for creating effective models and identifying trends and future challenges.

In this EDA project, we utilized two raw datasets from Kaggle: one containing Play Store attributes and the other consisting of user reviews. The first dataset encompasses 13 different attributes, while the second dataset provides five additional features for data manipulation and analysis.

To ensure data integrity, we began by performing crucial data cleaning steps. This involved removing duplicate entries and dropping non-essential null values. However, due to a large number of null values in the rating column (1645), dropping them entirely would have adversely affected our final results. Therefore, we replaced these null values with the mode of ratings.

After cleaning the data, we conducted exploratory data analysis to gain a comprehensive understanding of our dataset. This involved various analyses, such as examining the number of installations for each category and exploring the correlation between app size, Android version, and the number of installs. 

Furthermore, we merged both dataframes to discover correlations between the columns of the two datasets, which yielded fascinating results.

Key insights and conclusions drawn from our analysis include:
- Positive correlation between reviews and installs, while price and rating exhibit negative correlation.
- The "Art and Design" category has the highest number of installs.
- Developing apps within the "Family" and "Lifestyle" categories may result in higher revenue.
- Approximately 61% of users have a positive sentiment, while only around 15% express negative sentiment.
- Free apps account for 92.12% of the dataset, while paid apps constitute 7.81%.
- The "Everyone" content rating category dominates, representing 81.80% of all apps.
- The most prevalent categories on the Play Store are "Family," "Game," and "Tools."
- "Game" category presents potential opportunities for developers due to its high number of installs.
- Popular genres for app downloads include "Tools," "Entertainment," "Education," "Business," and "Medical."
- The average rating of apps on the Play Store is 4.17, indicating a satisfactory overall quality.
- Users prefer lightweight apps and may be hesitant to download larger, paid apps.
- Apps reviewed by a larger number of people tend to be downloaded more frequently.
- Users tend to leave harsher reviews for paid apps.
- A positive correlation exists between installs and rating.
- Developing an app with a high rating requires timely updates and optimal app size.
- Developing free apps with a content rating suitable for everyone is beneficial.
- The dataset holds immense potential for improving business value and making a positive impact. It extends beyond the specific problem addressed in this project, with numerous other interesting possibilities waiting to be explored through further analysis.

By successfully achieving our project objectives and answering our research questions, we have obtained valuable insights into the Google Play Store apps ecosystem and the trends within.
**************************************************************************************************************************************************
Feel free to explore the repository to gain further insights into the code implementation, methodology, and findings.

Connect with me on [Linkedin](https://www.linkedin.com/in/shahrukhahmad26).

Happy Learning!
**************************************************************************************************************************************************

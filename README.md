# Project1: NETFLIX Data Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Libraries Used](#libraries-used)
- [Key Objectives](#key-objectives)
- [Data Preparation](#data-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)

  
### Project Overview
This project aims to comprehensively analyze Netflix’s dataset to gain insights into its content library, top Directors and Actors, trends in releases, and user preferences. This analysis will help in identifying patterns related to the type of content Netflix offers and which categories are more popular over time, which can be useful for decision-making in content creation, marketing, and user engagement strategies

### Data Source
The Dataset includes information such as
- show_id, type (Movie/ TV Show), title, director, cast, country, date_added, release_year, rating, duration, listed_in, description.

The dataset was sourced from Kaggle. [Download Here](https://www.kaggle.com/datasets/shivamb/netflix-shows)

### Libraries Used
- NumPy (for linear algebra operations)
- pandas (for data preparation)
- plotly (for data visualization)
- Textblob (for sentiment analysis)

### Key Objectives
1. Content Rating Distribution:
   - Analyzing content by its rating to understand which types of content are suitable for various age groups and
   - Netflix can tailor its library to different demographics.
2. Director and Cast Analysis:
   - Identify top directors and actors to highlight individuals who are consistently associated with popular or successful content. 
   - Popular actors or famous directors can often draw in larger audiences, as fans are likely to watch content featuring their favorite stars. Analyzing the impact of these individuals can help predict future successes based on their involvement in new content.
3. Trend Analysis Over Time:
   - Analyze the number of movies vs. TV shows available on Netflix.
   - Identify trends in the number of their releases over the years.
4. Sentiment Analysis using Description:
   - Use the description field for text analysis to evaluate sentiment (positive, neutral, negative).

### Data Preparation
1. Data loading and inspection
2. Handling the missing values(Nan)
3. Data cleaning and formatting

### Exploratory Data Analysis

EDA involved exploring the Netflix data to answer the key questions, such as:
- What is the Content Rating Distribution?
- Who are the top 5 Directors and Actors?
- What is the trend in releasing movies and TV Shows over time?
- What is the overall sentiment?

### Findings
The analysis results are summarized as follows:
1. Pie Chart:
   ![PieChart](https://github.com/user-attachments/assets/ba60ccc1-dac2-4ba1-bb5c-ad10d9acae17)
- The largest portion of the chart, representing 36.4%, is content-rated TV-MA, which is intended for mature audiences.
- The smallest section is TV-G, making up only 2.5% of the total content.
- The TV-MA and TV-14 content each make up a significant part of the chart.
  
2. Horizontal Bar Chart:
  ![HorizontalBar1](https://github.com/user-attachments/assets/332385ce-f038-451c-abcf-4d128c0809b3)
![HorizontalBar2](https://github.com/user-attachments/assets/01f8e6f4-4ebd-47bb-b1dd-99fc7d4599a3)
- The top Director was Rajiv Chilaka with a total of 22 Movies and TV Shows, and the top actor was Anupam Kher with a total of 39 shows.
  
3. Line Graph:
  ![LineGraph](https://github.com/user-attachments/assets/29ee5c0a-9e43-408b-ad81-8f31096e2182)
- The line for TV shows has shown a steady rise over the past few years, while the line for movies initially remained flat but has recently experienced a significant increase between the years 2015 and 2020.
- We notice that the production of Movies has generally outpaced TV Shows over the years. But both the lines have seen declining drastically after the year 2020.
  
4. Bar Chart:
  ![Bar](https://github.com/user-attachments/assets/15b2c92e-3a66-4fc2-82bf-c4725cefe48c)
- According to the chart, a majority of content descriptions fall under the Positive category, suggesting that most movies and TV shows are described in upbeat or exciting descriptions.
- Followed by the negative sentiment accounts, typically corresponding to horror, drama, or intense thrillers, having a higher portion compared to neutral sentiments.

### Recommendations
  - Given that TV-G (general audience) content is only 2.5%, Netflix could expand its library with more family-friendly and children’s programming to attract younger viewers and families.
  - Marketing efforts can focus on TV-MA and TV-14 content for adult and teen demographics, highlighting new releases in these categories to retain current viewers.
  - Highlight content that features popular directors and actors to attract their fan base. Leverage the popularity of top directors and actors like Rajiv Chilaka and Anupam Kher by producing more projects with them.
  - Analyze factors contributing to the decline in content production.
  - Since movies saw a sharp rise until 2020, Netflix could focus on reviving movie production with strong original content.
  - Since most content descriptions are positive, focus marketing efforts on promoting content with upbeat or exciting themes.
  - With a higher portion of negative sentiment related to intense genres like thrillers or horror, Netflix could create specialized collections of these genres to cater to fans of darker content, while also marketing new releases in these categories.

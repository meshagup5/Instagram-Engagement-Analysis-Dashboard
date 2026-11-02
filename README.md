# Instagram Engagement Analysis Dashboard | Excel

## Project Overview

This project analyses Instagram engagement and content performance for **Data Analyst Duo (@dataanalystduo)**, an account with approximately 133,000 followers.

The objective was to build an interactive Excel dashboard to understand how different content formats perform, identify audience characteristics, and uncover opportunities to improve engagement, reach and follower growth.

The analysis focuses on post performance, audience demographics, geographic distribution, content keywords and follower acquisition.

## Project Objectives

- **Track audience growth:** Analyse total reach, profile visits and new followers over time.
- **Understand audience demographics:** Examine follower distribution by age and gender.
- **Explore geographic distribution:** Identify the top cities and countries represented in the audience.
- **Analyse content performance:** Compare images, Reels, carousels and other content formats using engagement and retention metrics.
- **Identify effective keywords:** Examine commonly used keywords and hashtags across different impression categories.
- **Support content strategy:** Translate findings into recommendations for improving engagement and follower growth.

## Dataset Description

The project uses seven datasets covering different aspects of Instagram performance:

1. **Reach:** Daily audience reach.
2. **Profile Visits:** Daily profile visits.
3. **New Followers:** Daily follower acquisition.
4. **Content:** Post-level performance, including likes, comments, shares, saves, reach and video views.
5. **Age & Gender:** Audience demographic distribution.
6. **Top Cities:** Geographic distribution of followers by city.
7. **Top Countries:** Geographic distribution of followers by country.

## Data Cleaning & Preparation

- Explored the seven datasets to understand their structure, column names, data types and data quality.
- Selected December 2022 onward as the common analysis period because the New Followers and Content datasets began in December 2022, while the Reach and Profile Visits datasets contained earlier records.
- Separated date and time information in the Reach, Profile Visits and New Followers datasets.
- Consolidated the daily reach, profile visits and new follower data into a single worksheet.
- Created calculated metrics to evaluate audience growth, conversion, engagement and video performance.
- Grouped video content by duration to compare performance across different video lengths.

## Key Performance Metrics

The following metrics were calculated as part of the analysis:

| Metric | Calculation |
|---|---|
| Conversion Rate | New Followers ÷ Reach |
| Daily Growth Rate | (Current Day's New Followers ÷ Previous Day's New Followers) − 1 |
| Engagement Rate | Average of (Shares ÷ Reach, Likes ÷ Reach, Comments ÷ Reach and Saves ÷ Reach) |
| Retention Rate | 3-second Views ÷ Reach |

*Note: Unfollows were not considered when calculating follower growth.*

## Analysis & Key Insights

### 1. Audience Demographics

- Men represent the majority of the audience, particularly in the 18–34 age groups.
- The 25–34 age group has the strongest representation among both men and women.
- Audience representation declines considerably in age groups above 35.

### 2. Geographic Audience Distribution

- **Bangalore** has the largest city-level audience, with 13,217 individuals.
- Hyderabad, Chennai, Mumbai and Pune also have substantial audience representation.
- Mumbai (7,076) and Chennai (6,942) have similar audience sizes.
- **India accounts for approximately 81% of the audience**, with 95,720 users.
- The United States is the second-largest market, with 11,748 users.
- Canada (3,605), the UK (3,605) and Indonesia (2,270) represent additional international audience segments.

### 3. Keyword & Hashtag Analysis

The analysis compared the most frequently appearing keywords across three impression categories: above 100K, 50K–100K and below 50K.

- **"Data"** appeared consistently across all three categories, indicating its strong relevance to the account's content.
- **"SQL"** appeared in the above-50K impression categories but not in the below-50K category.
- **"DataAnalystDuo"** appeared in the 50K–100K and below-50K categories, highlighting its role in brand recognition.

### 4. Content Format Performance

- **Reels achieved a 54% retention rate** and the highest conversion rate from reach to followers at 0.38%.
- Reels and carousels recorded the same engagement rate of 2.8%.
- Single-image posts performed the weakest, with a 1.2% engagement rate and 0.06% conversion rate.
- Carousels maintained strong engagement despite the reported 0% retention rate.

### 5. Video Duration Analysis

- **Videos between 11 and 30 seconds** achieved the highest retention rate at 61%.
- **Videos longer than 30 seconds** recorded the highest engagement rate (3.41%) and conversion rate (0.41%).
- **Videos of 10 seconds or less** had the lowest engagement rate at 2.07%, with a retention rate of 34%.

## Recommendations

Based on the findings, the following recommendations were developed:

1. **Focus on regional audience preferences:** Develop content relevant to major audience locations, particularly Bangalore, Hyderabad, Mumbai, Chennai and Pune.
2. **Prioritise Reels and carousels:** Increase the use of these formats while reducing reliance on standalone image posts.
3. **Experiment with video duration:** Use 11–30-second videos to improve retention and test longer videos to encourage engagement and follower conversion.
4. **Optimise keyword strategy:** Prioritise relevant high-performing keywords such as "data", "SQL", "statistics" and "data science", while retaining branded hashtags.
5. **Use audience insights for content planning:** Tailor content topics and formats to the account's demographic and geographic audience distribution.

## Tools & Techniques

- **Microsoft Excel**
- Pivot Tables and Pivot Charts
- Data Cleaning and Preparation
- KPI Calculation and Performance Tracking
- Exploratory Data Analysis (EDA)
- Data Visualisation
- Interactive Dashboard Development

## Project Outcome

Developed an interactive Excel dashboard that brings together audience growth, content performance, demographic insights and geographic distribution. The analysis identified differences in engagement across post formats and video durations, highlighted key audience segments and generated actionable recommendations to support content planning and audience growth.

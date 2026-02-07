# Video Game Sales Analysis – Ice Online Store

## Project Overview
Ice is an online store that sells video games worldwide. To support future marketing campaigns, the company needs to understand which factors determine whether a video game is successful.

This project analyzes historical video game sales data, reviews, genres, platforms, and ESRB ratings to identify patterns that influence game performance. The analysis is performed using data available up to 2016, simulating planning decisions for 2017.

## Objective
The main objectives of this project are to:
- Identify patterns that determine video game success.
- Analyze sales trends across platforms and time.
- Evaluate the impact of user and critic reviews on sales.
- Compare regional preferences across North America, Europe, and Japan.
- Test business hypotheses using statistical methods.
- Support data-driven marketing and product decisions.

## Dataset
The dataset includes historical video game data with the following attributes:
- Game name
- Platform
- Year of release
- Genre
- Regional sales (NA, EU, JP, Other)
- Critic scores
- User scores
- ESRB rating

Global sales were calculated as the sum of all regional sales.

## Data Preparation
- Standardized column names to lowercase.
- Converted data types as required for analysis.
- Identified and handled missing values.
- Processed special values such as `TBD` in user scores.
- Calculated total global sales per game.

## Exploratory Data Analysis
- Analysis of game releases by year.
- Platform lifecycle analysis and identification of leading platforms.
- Selection of relevant time period for forecasting and trend analysis.
- Comparison of sales distributions across platforms using boxplots.
- Analysis of sales performance by genre.
- Study of the relationship between reviews (critic and user scores) and sales using correlation analysis.

## Regional Analysis
User profiles were created for each major region:
- North America (NA)
- Europe (EU)
- Japan (JP)

For each region, the following were analyzed:
- Top platforms by market share.
- Most popular genres.
- Impact of ESRB ratings on sales.

## Hypothesis Testing
The following hypotheses were tested:
1. The average user ratings for Xbox One and PC platforms are the same.
2. The average user ratings for Action and Sports genres are different.

Statistical hypothesis testing was conducted using a defined significance level (alpha), and conclusions were drawn based on the results.

## Tools Used
- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

## Business Value
This analysis helps Ice:
- Identify promising platforms and genres for future campaigns.
- Understand regional differences in customer preferences.
- Optimize marketing strategies based on data insights.
- Reduce risk when selecting games to promote.

This project demonstrates a complete data analysis workflow, from data preparation to statistical testing and business-oriented conclusions.

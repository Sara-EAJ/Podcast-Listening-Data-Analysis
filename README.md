# Podcast Listening Data Analysis and Recommendation System

## Project Overview

This project analyzes podcast listening behavior by processing data from users, episodes, and listening history. It provides insights into user preferences and engagement, visualizes key trends, and implements a basic episode recommendation function based on user listening history.

## Features

* Data cleaning and preprocessing to handle missing or invalid values
* Merging user, episode, and listen data for comprehensive analysis
* Exploratory data analysis (EDA) including:

  * Most popular episode categories
  * Average listening duration by gender
  * Average number of unique episodes listened to per user
* Visualizations using Matplotlib and Seaborn for clear insights
* A recommendation function suggesting new episodes based on user’s favorite categories

## Usage

1. Load and clean the datasets
2. Merge data to create a unified DataFrame
3. Perform analysis and generate visualizations
4. Use the `recommend_episodes(user_id, listens_df, episodes_df)` function to get personalized episode recommendations

## Technologies

* Python 3
* Pandas
* Matplotlib
* Seaborn

## Conclusions and Recommendations

* Society and Sports episodes are the most popular, indicating high listener interest in these categories.
* Females tend to listen longer than males, suggesting potential for targeted content strategies.
* Users engage with multiple unique episodes on average, supporting personalized recommendation systems.
* Future improvements include expanding recommendation algorithms and incorporating additional user behavior data.


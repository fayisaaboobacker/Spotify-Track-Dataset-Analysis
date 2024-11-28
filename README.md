# Spotify-Track-Dataset-Analysis
The "Spotify Tracks Analysis" project uses Python to explore and visualize a Spotify dataset, uncovering song characteristics, patterns, and feature correlations with libraries like Pandas, NumPy, Matplotlib, and Seaborn.


![Image](https://github.com/user-attachments/assets/22902b0f-a436-4496-ae31-66c5d863340c)

## INTRODUCTION ##

The "Spotify Tracks Analysis" project focuses on exploring and visualizing a dataset of Spotify tracks. The main aim is to gain insights into song characteristics, spot patterns, and analyze how different features are related. Python is used for the analysis, along with popular libraries like Pandas, NumPy, Matplotlib, and Seaborn.

## BUSINESS TASK ##

### Data Loading and Cleaning ###

The data is in .csv format, load data using the pandas library. The dataset includes information about each track, such as its ID, name, popularity, duration, artists, release date, and various musical features. Make sure data quality using pd.isnull() and info() functions.

### Exploratory Data Analysis ###

1. 10 Least Popular Songs
This analysis identifies and displays the 10 songs with the lowest popularity scores in the dataset. The songs are sorted in ascending order of popularity, and key details are presented.

2. Top 10 Songs with Popularity > 90
This exploration highlights the 10 most popular songs that have a popularity score above 90, filtered and sorted for easy interpretation.

### Data Transformation ###

Duration is given in milliseconds, the column duration_ms is dropped and a new column is created duration in seconds as duration.

### Visualization ###

Correlation Heatmap

Regression Plots

Duration of Songs Over the Years

## Conclusion ##

The "Spotify Tracks Analysis" project delves into a dataset of Spotify tracks, uncovering patterns, correlations, and trends. Using descriptive statistics and visualizations, it highlights song characteristics, offering insights into the musical landscape represented in the data.

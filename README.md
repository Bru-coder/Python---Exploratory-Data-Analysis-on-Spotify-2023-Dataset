# Spotify 2023 EDA

## Overview

This repository presents an exploratory data analysis (EDA) of the dataset **Most Streamed Spotify Songs 2023**, sourced from [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023). The goal of this analysis is to uncover meaningful insights into popular Spotify tracks by examining metrics such as stream counts, musical attributes, artist contributions, and platform popularity. These insights help us understand what makes a track popular and how different characteristics influence its performance.

The analysis utilizes Python libraries such as **pandas** for data manipulation, and **matplotlib** and **seaborn** for visualization.

## Repository Structure

- **`spotify-2023-analysis.ipynb`**: This Jupyter Notebook contains all the code and analysis performed on the dataset. It is organized into several sections:
  - Initial setup and loading the data.
  - Basic descriptive statistics.
  - Analysis of top performers and temporal trends.
  - Examination of genre and music characteristics.
  - Insights on platform popularity and advanced analysis based on patterns among key, mode, and genres.
- **`README.md`**: This file provides an overview of the repository, its structure, and instructions for use.

## Dataset Description

The dataset includes detailed information about the most streamed Spotify tracks in 2023. Key features include:
- **Track Name**: Title of the track.
- **Artist**: Name of the artist(s).
- **Streams**: Number of times the track was streamed.
- **Released Year**: Year the track was released.
- **Musical Attributes**: Characteristics such as tempo (bpm), danceability, energy, valence, etc.
- **Platform Popularity**: Number of playlists or charts where the track is featured (e.g., Spotify playlists, Apple playlists).

## Analysis Objectives

The EDA is divided into the following main sections:

1. **Initial Data Exploration**:
   - Loading and displaying basic information about the dataset (e.g., number of rows and columns, data types, and missing values).
   - Providing summary statistics for key numerical features such as streams, artist count, and musical attributes.

2. **Top Performers**:
   - Identifying tracks with the highest number of streams and determining the top-performing artists based on the number of tracks.

3. **Temporal Trends**:
   - Exploring trends in track releases over time, both by year and by month.
   - Analyzing the number of tracks released per year and per month to identify temporal patterns.

4. **Genre and Music Characteristics**:
   - Investigating correlations between streams and musical attributes such as bpm, danceability, and energy.
   - Examining relationships between other characteristics like danceability and energy or valence and acousticness.

5. **Platform Popularity**:
   - Comparing the number of tracks on Spotify playlists, Spotify charts, and Apple playlists to determine which platform favors popular tracks the most.

6. **Advanced Analysis**:
   - Analyzing patterns in streams based on musical key and mode (e.g., major vs. minor).
   - Investigating whether specific artists or genres consistently appear in playlists or charts, indicating their popularity or platform preference.

## Key Insights

- **Popularity Trends**: Tracks with higher energy and danceability tend to accumulate more streams, suggesting that these characteristics resonate well with audiences.
- **Temporal Patterns**: The number of tracks released peaks in certain months, indicating that some times of the year are preferred for releasing new music.
- **Platform Insights**: Spotify playlists tend to include more popular tracks compared to Apple playlists, which may reflect Spotify's bias or strategy in promoting hits.
- **Top Artists and Tracks**: Certain artists consistently appear in more playlists and charts, underscoring their strong influence in the music industry.

## Next Steps and Recommendations

Based on the findings, the following recommendations are provided:
- Artists aiming for popular tracks may benefit from focusing on high-energy and danceable characteristics.
- Strategic releases during peak months could enhance track visibility.
- Artists should consider expanding their presence across multiple playlists and charts to maximize reach and audience engagement.

## Contact
If you have any questions or suggestions regarding this project, feel free to open an issue or submit a pull request.


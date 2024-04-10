## YouTube Video Analytics and Comments Analysis

This repository contains Python code for analyzing YouTube video analytics and comments using the YouTube Data API v3.

### Overview

The code performs the following tasks:

1. **Data Retrieval**: Retrieves video metadata, including title, description, view count, like count, comment count, duration, and publication date, using the YouTube Data API.
   
2. **Data Processing and Analysis**: Processes the retrieved data, performs exploratory data analysis (EDA), and computes various statistics such as video duration, likes per view, comments per view, etc.

3. **Visualization**: Utilizes matplotlib and seaborn libraries to create visualizations such as bar plots, histograms, scatter plots, and word clouds to gain insights from the data.

4. **Comments Analysis**: Collects comments from the top videos of selected channels and analyzes them to identify common trends and sentiments.

## Dependencies

- pandas
- isodate
- google-api-python-client
- matplotlib
- seaborn
- nltk
- wordcloud

## Usage

1. Ensure you have all the required dependencies installed.
2. Obtain an API key for the YouTube Data API v3 and replace `'API_KEY'` in the code with your actual API key.
3. Run the provided Python script `youtube_video_analytics.py`.

## File Structure

- `youtube_video_analytics.py`: Main Python script for retrieving and analyzing YouTube video analytics and comments.
- `video_data.csv`: Dataset containing video metadata.
- `comments_data.csv`: Dataset containing comments from selected videos.
- `channel_data.csv`: Dataset containing channel metadata.
- `README.md`: This file, providing an overview of the project and instructions for use.

## Acknowledgements

This project utilizes the YouTube Data API v3 for retrieving video metadata and comments. Special thanks to YouTube for providing access to their API for data analysis and research purposes.

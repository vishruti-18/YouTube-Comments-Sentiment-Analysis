# YouTube-Comments-Sentiment-Analysis

Project Overview
This project performs sentiment analysis on YouTube comments to extract meaningful insights and visualize trends. Using Python, Google API, and various data visualization libraries, this analysis provides an understanding of comment sentiment, commenter activity, and time-based patterns.

Objectives
Sentiment Analysis: Determine the sentiment (positive, negative, neutral) of YouTube comments.
Time-based Patterns: Explore how sentiment and comment activity change over time.
Data Visualization: Create visualizations to illustrate findings and trends.

Dataset
Source: Comments retrieved using the YouTube Data API.
Fields: Comment text, timestamp, commenter name.

Installation
To get started, install the required libraries:
pip install google-api-python-client pandas nltk wordcloud matplotlib textblob

Usage
API Key Setup: Ensure you have a valid YouTube Data API key.
Run the Analysis: Execute the provided Jupyter Notebook to perform the analysis.

Project Structure
notebook.ipynb: Jupyter Notebook containing the analysis and visualizations.
youtube_comments.csv: Raw data of YouTube comments.
youtube_comments_with_timestamps.csv: Processed data with sentiment analysis.

Key Visualizations
1. Sentiment Over Time

Description: This line plot shows the average sentiment of comments over time, illustrating trends and fluctuations.

2. Top Commenters

Description: This bar plot displays the top 10 commenters by the number of comments, highlighting the most active users.

3. Average Sentiment by Hour of Day

Description: This bar plot shows the average sentiment of comments by hour of the day, revealing how sentiment varies throughout the day.

4. Sentiment Distribution

Description: This bar plot illustrates the distribution of comment sentiments (positive, negative, neutral), providing a breakdown of overall sentiment.

5. Comment Length Distribution by Day of the Week

Description: This box plot shows the distribution of comment lengths across different days of the week, indicating variations in comment size based on the day.

Future Work
Advanced Sentiment Analysis: Explore more sophisticated sentiment analysis techniques.
Feature Expansion: Integrate additional features such as video view counts and like/dislike ratios.
Extended Data Set: Analyze comments from a wider range of videos for more comprehensive insights.

Acknowledgments
Google YouTube Data API
TextBlob
WordCloud
Matplotlib
Seaborn


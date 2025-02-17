# Web_scraping_reddit

Project Overview
This project focuses on analyzing sentiment trends in news articles and Reddit discussions related to avian influenza (bird flu). The goal is to extract, analyze, and interpret text data using sentiment analysis to gauge the overall tone of media and public discourse surrounding the topic.

The project consists of two major components:

**News Article Sentiment Analysis** – Fetches news articles from NewsAPI, processes their text, and performs sentiment analysis using TextBlob.


**Reddit Discussion Scraper** – Extracts Reddit posts and comments containing relevant keywords, then stores them for further analysis.

**Files Included**

**News_Scraper_+_Sentiment_Analysis**: Python script that retrieves news articles using NewsAPI, performs sentiment analysis, and saves results in a CSV file.


**Reddit_scraper.ipynb**: Jupyter Notebook that scrapes Reddit posts and comments using PRAW, filters relevant content, and stores it in a structured format.

**analyzed_data.xlsx**: The final output of the sentiment analysis code on a large chunk of the reddit posts

**1. News Article Sentiment Analysis**

Description

Uses NewsAPI to fetch articles related to "avian influenza".

Extracts key metadata (source, title, author, date, content, and URL).

Performs sentiment analysis using TextBlob to determine if the article is positive, neutral, or negative.

Saves the analyzed data into news_articles.csv.


**2. Reddit Scraper**

Description

Uses PRAW (Python Reddit API Wrapper) to fetch posts and comments from Reddit.

Filters posts based on relevant keywords (e.g., "bird flu").

Saves post details (title, author, timestamp, comments, score, etc.) into a CSV file.

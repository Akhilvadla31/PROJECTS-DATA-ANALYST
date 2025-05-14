# PROJECTS-DATA-ANALYST
Real-Time Public Sentiment Dashboard (Twitter/X)

Presented by: Akhil Vadla

Date: 19 May 2025

Introduction

In an era where brand perception can shift overnight, staying connected to public opinion is more important than ever. This project focuses on developing a real-time sentiment analysis dashboard using Twitter (now X) data to help brands understand what people are saying about them—right now.

Abstract

This project brings together real-time data collection, natural language processing (NLP), and interactive visualization to track public sentiment. By leveraging Twitter’s API and tools like NLTK and Power BI, we analyze how people feel about a product or brand and present these insights in a clear, visual format. The goal is to empower businesses with the ability to respond promptly and strategically based on public opinion.

Tools Used

- Python: Scripting and data processing
- Tweepy: Accessing and streaming tweets via Twitter API
- NLTK: Text preprocessing and sentiment analysis (VADER)
- Power BI: Visualizing sentiment insights in real time
- Pandas: Handling and storing tweet logs

Steps Involved in Building the Project

1. Twitter API Setup:
   - Connected to the Twitter API using Tweepy to stream tweets in real-time based on selected keywords or brand names.

2. Data Preprocessing:
   - Cleaned tweets by removing noise such as links, mentions, emojis, and unnecessary characters using NLTK.

3. Sentiment Analysis:
   - Applied VADER sentiment analyzer from NLTK to classify tweets as Positive, Neutral, or Negative based on their sentiment score.

4. Data Logging:
   - Saved real-time results in structured CSV logs, capturing essential information like timestamp, tweet text, and sentiment.

5. Dashboard Integration:
   - Used Power BI to create dynamic visualizations updated at regular intervals. Charts include sentiment trends, volume of tweets, and overall sentiment breakdown.

Conclusion

This real-time sentiment dashboard offers a fast and effective way to understand the voice of the public. Brands can use it to stay ahead—identifying potential PR issues early, measuring campaign success, or simply listening better. This project is a step toward data-driven brand intelligence powered by live social media insights.

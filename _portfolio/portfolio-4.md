---
title: "Web Scraping and Sentiment Analysis"
excerpt: "Using Python I web scraped Google reviews from the Lambton College review page then conducted senttiment analysis to asses weather the stars rating alligned with the overall sentiment of the comments.<br/><img src='/images/rsz_1sentiment.png'>"
collection: portfolio
---
In this project, I employed Selenium WebDriver for web scraping Google reviews for Lambton College's review page. I iteratively scrolled through the page to load all comments, extracted the relevant review data—names, comments, and star ratings—and saved it into a DataFrame. I then conducted sentiment analysis using NLTK's VADER tool to evaluate the sentiment of the review comments, which allowed me to compare them against the star ratings to assess their consistency. The process involved normalizing the text, handling emojis, and calculating sentiment scores to ensure a thorough analysis.[Check the code](https://github.com/Carvas91/Carlos_Vasconez_portfolio/tree/main/sentiment_analysis)



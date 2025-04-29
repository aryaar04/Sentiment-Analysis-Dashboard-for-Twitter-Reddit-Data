# Sentiment-Analysis-Dashboard-for-Twitter-Reddit-Data
This project is a real-time sentiment analysis dashboard that fetches tweets from Twitter based on a given keyword or topic, analyzes their sentiments, and visualizes the results.

Key Features:
Tweet Fetching: The program uses the Tweepy library to search for recent tweets related to a specific keyword, excluding retweets, and filtering by the English language.

Sentiment Analysis: The sentiment of each tweet is analyzed using the VADER sentiment analysis tool from the NLTK library. Tweets are classified as Positive, Negative, or Neutral based on their sentiment scores.

Visualizations:

Pie Chart: Displays the distribution of positive, negative, and neutral sentiments.
Bar Chart: Provides a visual count of each sentiment category.
Line Chart: Optionally, visualizes the trend of sentiment scores over time.
Sample Output: The dashboard also displays a few sample tweets along with their sentiment classification and score.

This project serves as a quick tool to assess the overall sentiment surrounding a specific topic or keyword on Twitter.

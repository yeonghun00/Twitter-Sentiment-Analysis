# Twitter-Sentiment-Analysis

This project performs sentiment analysis on Twitter data using Google Colab. It utilizes snscrape, OpenAI, and VaderSentiment to scrape tweets, perform sentiment analysis, and visualize the results.

## Usage
1. Open the twitter_sentiment_analysis.ipynb file in Google Colab.
2. Set the search parameters: Follow the instructions in the notebook to set the search parameters for the tweets you want to analyze. You can specify the search query, dates, language, and other parameters to customize your search. 
3. Run the cells to perform the sentiment analysis and generate visualizations.

## Visualizations
The notebook generates several visualizations to help understand the sentiment of the scraped tweets:

<img width="700" alt="Word Cloud" src="https://user-images.githubusercontent.com/44548828/218994078-b87fd0c9-c8a2-4e0a-9bac-0054dc8e5009.png">

- **Word Clouds**:  These are used to visualize the most common words in the tweets, with the size of the word indicating its frequency. Many stop words, such as "and" and "the", are excluded to provide better word cloud results. This can help the user to quickly understand the most commonly used words and topics in the tweets. 

<br />

<img width="700" alt="Sentiment Trend" src="https://user-images.githubusercontent.com/44548828/218994095-6871c05b-600b-4b3d-b2d2-c6068cc9cec4.png">

- **Sentiment Trends**: This chart shows the overall sentiment of the tweets over time, allowing the user to see how the sentiment changes during the time period specified. There are three types of sentiment scores: positive, negative, and compound. The compound score is an overall sentiment score that takes into account both positive and negative sentiment in a single value.

<br />

<img width="700" alt="Sentiment Scatter" src="https://user-images.githubusercontent.com/44548828/218994100-73b10d3f-f974-4c62-ab52-9e49436420f8.png">

- **Sentiment Scatter Plot**: This chart shows the sentiment of each tweet, with polarity on the x-axis and subjectivity on the y-axis. The color of each point represents the number of likes for the tweet, and the size of each point represents the number of views. This allows you to see not only the sentiment of each tweet, but also its popularity and reach.

<br />

<img width="700" alt="Fear & Greed" src="https://user-images.githubusercontent.com/44548828/218994072-a870cb5d-822b-4fb7-9df9-45cb8aedcc7a.png">

- **Fear and Greed Index Gauge Graph**: This chart shows the Fear and Greed Index, a sentiment indicator that tracks the emotions and sentiments of investors. The gauge graph displays the current index as well as the index for previous months. This information can be useful in understanding how the stock market may react to the sentiment of the tweets.


## Dependencies

This project relies on the following libraries and services:

- snscrape
- OpenAI API
- VaderSentiment

## Conclusion

This project can be used to perform sentiment analysis on Twitter data and visualize the results. It can be a helpful tool for understanding the sentiment around a particular topic or for tracking sentiment trends over time.

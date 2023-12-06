# Twitter_Sentiment_Analysis

### Real-time Twitter Sentiment Analysis for Brand Improvement and Topic Tracking


Dive into the industry and get my hands dirty. That's why I start this self-motivated independent project.

Try this awesome Real-Time Twitter Monitoring System here on Heroku server. Read a series of related articles below:

- Chapter 1: Collecting Twitter Data using Streaming Twitter API with Tweepy, MySQL, & Python
- Chapter 2: Twitter Sentiment Analysis and Interactive Data Visualization using RE, TextBlob, NLTK, and Plotly
- Chapter 3: Deploy a Real-time Twitter Analytical Web App on Heroku using Dash & Plotly in Python
- Chapter 4 (In Progress): Parallelize Streaming Twitter Sentiment Analysis using Scala, Kafka and Spark Streaming

---

### Inspiration
The solution for evaluating Twitter data to perform better business decisions is to keep tracking all relevant Twitter content about a brand in real-time, perform analysis as topics or issues emerge, and detect anomaly with alert. By monitoring brand mentions on Twitter, brands could inform enagement and deliver better experiences for their customers across the world.

---

### Interesting facts from exploratory data analysis
- Less 0.01% users will push tweets with their locations.
- Tweets grabbed from streaming data won't have more than 0 LIKE or RETWEET, since you have already captured them even before others press buttons :p
- More than 65.6% users will write the locations in their profile, although very few of them don't live on Earth according to that fact.
- The numbers of positive and negative tweets are relatively close and stay low compared with neural tweet number. Unless emergency events happen, lines won't fluctuate acutely.

---

## Challenges

- Unstructured tweet texts may contain messy code and emoji characters
- Some brands may take a long time to collection enough data to perform analysis on issue emerging since they target specify groups of people
- Some hot words will uncover useful insights only after appearing more than 10k times on tweets
- Plotly doesn't have well-document on reference making customize dashboard much harder
- More challenges on the way, but Google, StackOverFlow, Towards Data Science, and GitHub will always be your best friends

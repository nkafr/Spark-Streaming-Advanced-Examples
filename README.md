# Spark-Streaming-Advanced-Examples
Examples of analyzing Tweets, csv files and Apache logs using Spark Streaming, Spark SQL and MLlib

These cases include:

**LogAlarmer:** Monitors a stream of Apache access logs on port 9999, and prints an alarm if an excessive ratio of errors is encountered.

**LogParser:** Maintains top URL's visited over a 5 minute window, from a stream of Apache access logs on port 9999.

**LogSQL:** Using SparkSQL with Spark Streaming, to issue queries on Apache log data extracted from a stream on port 9999.

**AverageTweetLength:** Uses thread-safe counters to keep track of the average length of Tweets in a stream.  

**PopularHashtags:** Listens to a stream of Tweets and keeps track of the most popular hashtags over a 5 minute window.  

**PrintTweets:** Simple application to listen to a stream of Tweets and print them out  

**SaveTweets:** Listens to a stream of tweets and saves them to disk.  

**Sessionizer:** An example of using a State object to keep persistent state information across a stream. This example keep track of clickstreams on sessions tied together by IP addresses.  

**StreamingKMeansClass:** Example of using streaming K-Means clustering to cluster people by income and age into 5 clusters.  

**StreamingRegression:** Example of using streaming linear regression with stochastic gradient descent. Listens to port 9999 for data on page speed vs. amount spent, and creates a linear model to predict amount spent by page speed over time.  

**StructuredStreaming:** Example of Structured Streaming  

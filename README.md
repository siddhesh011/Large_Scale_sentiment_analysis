#Sentiment Analysis on Movie Reviews using Spark
This project focuses on performing a rudimentary sentiment analysis on a dataset of movie reviews using Apache Spark. The primary objective is to determine whether a movie review is positive or negative based on the frequency of predefined positive and negative words in the review.

Dataset
The dataset comprises 2000 individual files, each containing a unique movie review. These reviews are stored in a compressed zip file named movie_review.zip.

Predefined Word Lists
To aid the sentiment analysis, two lists of words have been provided:

Positive Words: A list of words that typically indicate a positive sentiment, such as "happy", "joy", "excited", and "elated".
Negative Words: A list of words that usually convey a negative sentiment, including "sad", "bad", "unhappy", and "pity".
Methodology
The sentiment analysis is carried out using various features and capabilities of Apache Spark, including RDDs, DataFrames, SparkSQL, and Spark ML. The approach is as follows:

Data Ingestion: Load the movie reviews dataset into Spark for processing.
Text Processing: Tokenize each review and convert it into a format suitable for analysis.
Sentiment Scoring: For each review, count the frequency of positive and negative words present.
Sentiment Assignment: Based on the positive and negative scores obtained, assign a final sentiment label to each review (either positive or negative).
Example
Consider a sample review:

"I was excited to see this movie. Although the movie had a sad story but had a happy ending."

Positive Score: 2 (Words: excited, happy)
Negative Score: 1 (Word: sad)
Final Sentiment: Positive
Usage
To run this project, follow these steps:

Ensure you have Apache Spark installed on your machine or cluster.
Download the movie_review.zip file and extract it to access the dataset.
Clone this repository and navigate to the project directory.
Execute the Spark application/script designed for sentiment analysis.
Conclusion
By leveraging the capabilities of Apache Spark, this project demonstrates a basic yet effective approach to sentiment analysis on movie reviews. By analyzing the frequency of positive and negative words in each review, the model assigns a sentiment label, thereby providing insights into the overall sentiment associated with the movie reviews.

For any queries or suggestions, feel free to reach out!


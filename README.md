# twitter_hashtag_sentiment_analysis
Sentiment analysis is the process of identifying and categorizing opinions expressed in a piece of text to determine whether a writer's attitude towards a topic or product is positive, negative or neutral.

Sentiment analysis is also known as opinion mining, an area of natural language processing that is useful to a wide range of problems that are of interest to human-computer interaction. Systems built from sentiment analysis try to identify and extract opinions within text such as the polarity, subject and opinion of the writer.

For the purpose of this project, real time tweets and trending hashtags are streamed using Twitter's API by
<ol>
<li> Creating a developer account on twitter to allow access to tweets </li>
 <li>Unique credentials are generated to give user permission to stream tweets</li>
<li>Live-streaming tweets based on trending hashtags</li>
</ol>
 
A sentiment classification system is then built to determine the general sentiment of a trending hashtag using the text contained in the tweet using Python

The main python package used for the sentiment classification is VADER (Valence Aware Dictionary for sEntiment Reasoning) because of its suitability for analyzing social media text.

The sentiment score of sentence is calculated by summing up the sentiment scores of each VADER-dictionary-listed word in the sentence
<ol>
<li>Individual words have a sentiment score between -4 and 4</li>
<li>Sentence sentiment scores are then normalized to have a score between -1 and 1</li>
</ol>

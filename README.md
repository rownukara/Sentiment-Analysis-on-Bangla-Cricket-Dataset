# Sentiment-Analysis-on-Bangla-Cricket-Dataset-by-LSTM
Here I used LSTM to do sentiment analysis.
LSTM stands for Long Short-Term Memory, and it is a type of recurrent neural network (RNN) architecture.
LSTMs are designed to address the limitations of traditional RNNs in capturing long-term dependencies in sequential data.

Cricket Dataset
The Cricket dataset consists of 2900 different comments from different online sources with
five different aspect categories. Most of the comments are collected from Facebook pages
(https://www.facebook.com/BBCBengaliService/; https://www.facebook.com/DailyProthomAlo/).
Some comments are collected from two popular Bengali Websites, BBC Bangla (http://www.bbc.com/
bengali), and the Daily Prothom Alo (http://www.prothomalo.com). This dataset was collected by the
authors of this paper. The comments are of different lengths and each review contains approximately
3–100 Bangla words. The reasons behind choosing these Websites for collecting data are given below:
• BBC Bangla and the Daily Prothom Alo are very popular online news sites for the Bengali
community all around the world. They are popular for publishing trustworthy and authentic
news. Bengali people frequently read the news and sometimes make comments to share their
opinion. Although people write their comments or opinions in both Bangla and English, most of
the time, they choose Bangla. We studied different articles and found that in almost 90% of the
cases, people expressed their opinion in Bangla.
• The Facebook page of Prothom Alo has over 13 million followers, and BBC Bangla has over
11 million. These two pages provide enormous text posts as well as a large number of comments.
• Cricket is one of the most popular games nowadays for Bengali people. We found that people
are more interested in making comments on cricket-related news than on any other topic.
Thus, we chose this category for our experiment.

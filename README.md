# Building-Fast-Queries-on-a-CSV-Climate-Change-

The goal of this project is to create a class that represent the comments about the climate changes on reddit, monitoring the discourse about the climate changes, to find out what people think and discuss on this topic.. The methods in that class will implement the queries that we want to answer about our search. We will also preprocess that data to make those queries run faster.
#
To use this class, first you need to download the database from project on kaggle through this link: https://www.kaggle.com/datasets/pavellexyr/the-reddit-climate-change-dataset.
# 
In this class we have 3 methods:
- Finding a Comment Form the Id.
- Getting a Message Form the Analized Sentiments.
- Getting Two Messagens Whose Sum of a Score.
# Finding a Comment Form the Id
In this method, we give a Id form the database and it'll return all information about the message.
Put a id from the "Id column" on "get_comment_from_id" method and it'll return the information we want to find.
# Getting a Message Form the Analized Sentiments
In this method, we give a lower and upper bound of the "sentiment" column and it'll return all messagens with sentiment values between the lower and upper bounds.
Put a interval between -1 and 1 on "analized_sentiment" method and it'll return all the messagens between those values.
# Getting Two Messagens Whose Sum of a Score
In this method, we give a score and it'll return two messagens whose sum of the "score return" column value is equal to the score.
Put a score on "score" method and it'll return the messagens whose sum of the "score return" column value is equal to the score.

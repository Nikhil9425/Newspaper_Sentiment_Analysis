# Newspaper_Sentiment_Analysis

This Project comes up with the applications of NLP (Natural Language Processing) techniques for 
detecting the 'fake news', that is, misleading news stories that comes from the non-reputable sources.
Only by building a model based on a count vectorizer (using word tallies) or a (Term Frequency 
Inverse Document Frequency) tfidf matrix, (word tallies relative to how often they’re used in other 
articles in your dataset) can only get you so far. But these models do not consider the important 
qualities like word ordering and context.
It is very possible that two articles that are similar in their word count will be completely different in 
their meaning. The data science community has responded by taking actions against the problem.
There is a Kaggle competition called as the “Fake News Challenge” and Facebook is employing AI
to filter fake news stories out of users’ feeds. Combatting the fake news is a classic text classification 
project with a straight forward proposition. Is it possible for you to build a model that can 
differentiate between “Real “news and “Fake” news? So a proposed work on assembling a dataset of 
both fake and real news and employ a Naive Bayes classifier in order to create a model to classify an 
article into fake or real based on its words and phrases.

## Newspaper Sentiment Analysis
To detect the given newspaper article text as input and perform analysis on the data and show 
the score of the polarity of input text. The score shows the polarity of the text. If it is greater 
than zero means sentiment is positive else negative.
The input will be taken from the user by copying the news article as text format. After 
inputting the text, the approaches used in this project classify/tokenize the text in tokens. 
When tokenization is completed, it starts operation of tagging to each token and then 
evaluates it. This generates a score which after conversion from integer to string is displayed 
on the screen.

## Fake News Detection
In this project, we have used various natural language processing techniques and machine 
learning algorithms to classify fake news articles using sci-kit libraries from python.
The data source used for this project is LIAR dataset which contains 3 files with .tsv format 
for test, train and validation. Below is some description about the data files used for this 
project.
To make things simple we have chosen only 2 variables from this original dataset for this 
classification. The other variables can be added later to add some more complexity and 
enhance the features. The dataset used for this project were in csv format named train.csv, 
test.csv and can be found in repo. The original datasets are in "liar" folder in .tsv format.
This project brings to life a fake news classifier, by deploying it using Flask. The 
classification model is inspired by work from Aaron Edell.

![image](https://github.com/Nikhil9425/Newspaper_Sentiment_Analysis/assets/68101064/f6e978fa-f571-4a12-81fe-a74b85997db3)

![image](https://github.com/Nikhil9425/Newspaper_Sentiment_Analysis/assets/68101064/0ec81c77-6966-4cd4-aa7f-f5d5a9a94c2d)

![image](https://github.com/Nikhil9425/Newspaper_Sentiment_Analysis/assets/68101064/da74de46-d0d0-4b0c-a52b-bee1e85bac7d)



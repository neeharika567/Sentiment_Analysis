# Sentiment_Analysis

Link for my app: [https://muted-dazzling-flight.anvil.app/](https://muted-dazzling-flight.anvil.app/)
(For now this app is not full-time hosting)

## Objective:
Sentiment analysis (or opinion mining) is a natural language processing (NLP) technique used to determine whether data is positive, negative or neutral. Sentiment analysis is often performed on textual data to help businesses monitor brand and product sentiment in customer feedback, and understand customer needs.

![img](https://d33wubrfki0l68.cloudfront.net/9e1b2a906ae6b01cfe2d5d237e1e51f5d41864e3/2a5f9/static/348bb1d70089176ca2f61ea402094382/50bf7/main.png)

## Data Description
The sample Dataset summarizes the sentiment of 900 reviews which are labeled as positive and negative with 1 and 0 respectively.

## Data
The dataset is available in files section.

## Algorithms used :
In this dataset I've used **Naive Bayes Classifier**  to predict the sentiment.

In Naive Bayes, probabilities are assigned to words or phrases, segregating them into different labels. Naive Bayes works on the Bayes theorem. Here we will understand Naive Bayes with the help of an example.
![img](https://cdn-images-1.medium.com/max/800/0*U9z35NZCyt0r6MpR.png)

From the table above, a generative model like Naive Bayes will try to learn how these sentiments are classified usingthe corresponding text. For example, it will see that a sentence having the word "good" has a high probability of being a positive sentiment. Using such a probabilistic value, a total probability of a test sentiment being positive or negative can be assigned.


## Final Model :
I have created an Anvil Application based on this clustering technique, where I am taking one or more reviews of a customer and displaying the positive and negetive intent of the statement.

![sentipic](https://github.com/neeharika567/Sentiment_Analysis/assets/111648731/0a3d68dd-b211-497f-9085-1f03aa999277)


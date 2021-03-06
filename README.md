# SentimentAnalysis_NaturalDisaster
## IDEA
Mitigating the effects of Natural Disasters is an arduous task, requiring an understanding of the effect it will have on the people and economy in the short-term and long-term. With the ever-increasing frequency of disasters like tsunami, earthquakes and floods in India, being able to prioritize the response based on their potential impact on people and economy, and distribute resources accordingly becomes critical for an effective use of resources. But how can one predict the impact of a natural disaster at its onset? Evidence shows that public discourse in online sources, such as social media, blogs, and forums, is strongly correlated with the occurrence of real world behavior. We aim to investigate whether the same information can provide a reliable predictive indicator of the impact of natural disasters. Specifically, we want to design algorithms for applying sentiment analysis to user posts on twitter, blogs and forums related to natural disaster to efficiently make a prediction of the impact of those natural disasters.

Some of our preliminiary work has shown a promising result of using sentiment analysis to predict the impact of a natural disaster. For example, we created a basic algorithm using SentiWordNet, Natural Language Processing (NLP) and Machine Learning techniques to implement sentiment analysis on Cyber Attack and movie review data (as it is easily available on Kaggle) and our early work has proven to be a success to push us forward to create an efficient algorithm. In the below images, we can see that impact of a cyber attack (in terms of monetary impact) is linearly related to the sentiment score. Also, we can see on the right side image that, as sentiment score tends toward 10, success of a movie(in terms of points) also increases.


![adj_verb_adv_noun](https://user-images.githubusercontent.com/14362968/46847887-65ecaa00-ce04-11e8-9a6e-d6b9279d0105.png)
![recommendation](https://user-images.githubusercontent.com/14362968/46847889-66854080-ce04-11e8-8840-beb5e345697e.png)


On the similar ground, we expect to achieve some promising results on implementing sentiment analysis to predict the impact of a natural disaster. We will basically be targeting blogs, forums and twitter to extract data of some recent natural disasters like August 2018 flood in kerala, 2017 Gujurat flood and 2015 Nepal Earthquake.

## Actual Implementation

![graph](https://user-images.githubusercontent.com/14362968/47568257-47cb9180-d94e-11e8-8995-47a807cd261e.png)

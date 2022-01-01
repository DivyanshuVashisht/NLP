# Netflix Recommendation System
## Outline of the Program flow:
1. Preprocessing data
2. Transfer Learning using Google Pretrained Data
3. Create Word2Vec Model
4. Content based Recommendation System; Find 'what to watch'  based on which movie you've watched.

In this project we recommend a movie title to the user('what to watch') based on the description of a movie that the user has just watched. The recommendation system recommends that movie which has almost similar, if not the same plotline/theme as the movie just watched.

<strong>Note: Regex has been used to clean data, you can add/modify/omit that cell according to your needs.</strong>

The Transfer Learning model used is the word2vec pre-trained Google News model(GoogleNews-vectors-negative300).

<strong>Note: This is a basic model using a small dataset. Hence, there are limited recommendations provided. A larger dataset will provide us with better and more appropriate results, almost similar to the real deal!

# Personality Predictor

This project predicts the personality of any person based on any kind of document or tweets.
The result will be MBTI(Myers Briggs Type Indicator). Which describes the personality as well as some basic characteristics of the person and career choice.

# Types
This file contains the information about each of 16 MBTI types. This is used to display the results.

# Program:

There are many sections in the code which are explained in detail as follows:

## 1. Import

There are several import files which can be used or can be changed according to preference

## 2. EDA (Exploratory Data Analysis)

This section tells what kind of data we are dealing with and what are the limitations of this data. This is an important section because here we can get to know many important things like - is the data balanced?, is there any bias?...
After knowing such details we can decide how to proceed further and which algorithm we should use.

## 3. Preprocessing
 This step includes data cleaning and similar things which will make it easy to learn and remove unecessary things from the data.

 ## 4. Processing

 Here we apply TF-IDF. We can also use BOW or Words to Vectors but TF-IDF works the best.

 ## 5. Training

 Here we train the classifier. I have trained 4 separate classifiers and one extra classifier. The reason can be seen in the program comments.

 ## 6. Testing

 Here we test our classifiers.

 ## 7. Prediction

 We can predict in 2 ways:
 
 1. Type or Copy-Paste the document(story, poem, journal...).
 2. Use the Tweepy API to get latest 200-1000 tweets.
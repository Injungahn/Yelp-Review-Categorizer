# Yelp-Review-Categorizer

## Problem Statement

Yelp has revolutionized the way that we choose restaurants. With just a click of a button we can search by cuisine, distance, price, and more. The recommender system is based on reviews that are made by users. These reviews cover different aspects of the restaurant: food, service, wait time, etc., but the resulting rating is for all of these aspects combined. I want to be able to filter on these specific attributes. Using NLP I will parse these reviews into their different categories and use Sentiment Analysis to give scores in each of these categories.

## Data and Collection

### Size

San_Francisco_restaurant_reviews.csv (50_000, 4)

 - 50 Restaurants each with their 1000 most recent reviews
    
San_Francisco_restaurant_reviews_first_5.csv (40_930, 4)

 - 5 Restaurants with 40_930 total reviews
    
San_Francisco_restaurant_reviews_sentences.csv (469_663, 4) 

 - 50 Restaurants with their reviews parsed into 469_663 sentences

San_Francisco_restaurant_reviews_first_5_sentences.csv (390_257, 4)

 - 5 Restaurants with their reviews parsed into 390257 sentences

#### Data Dictionary

San_Francisco_restaurant_reviews.csv (50_000, 4)
San_Francisco_restaurant_reviews_first_5.csv (40_930, 4)

|Feature|Type|Description|
|---|---|---|---|
|restaurant_name|object|Name of restaurant|
|restaurant_rating|float|Yelp rating of restaurant|
|customer_rating|int|Individual review rating|
|review_text|object|Text of review|


San_Francisco_restaurant_reviews_sentences.csv (469_663, 4) 
San_Francisco_restaurant_reviews_first_5_sentences.csv (390_257, 4)

|Feature|Type|Description|
|---|---|---|---|
|restaurant_name|object|Name of restaurant|
|restaurant_rating|float|Yelp rating of restaurant|
|customer_rating|int|Individual review rating|
|review_text|object|Text of review|
|review_text_length|int|Character count of review|
|sentences|list|List of sentences of review|
|sentence_count|object|Number of sentences in review|
|review_id|int|Id for review|
|sentence|object|Individual sentence|



### Collection Notes

- Collected the first 1000 reviews from 50 restaurants for variety
- Data collection took around 30 minutes
- Collected all the reviews for 5 restaurants


## Data Cleaning and EDA




## Removed terms

## Sentence Categorization

## Sentiment Analysis

## Conclusions
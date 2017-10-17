# Suspicous Tweets

## Motivation
Twitter role in U.S. politics has increased in the last few years, in part due to President Trump's constant use the social media plaftorm, but also due to accounts linked to terrorist groups or foreign govenments interfering with the electoral process. For more information on the challengs of balancing free speech, a social media plaform, and nefarious groups and people see the following articles
http://nypost.com/2017/10/16/roy-moore-flooded-with-fake-russian-twitter-followers/
https://www.salon.com/2017/09/29/congressmen-warner-schiff-blast-twitter-over-russian-bot-report/?source=newsletter
http://www.politico.com/story/2017/10/13/twitter-russia-data-deleted-investigation-243730

## Data
Collected in March-April of 2017, with a filter for ISIS related tweets, JSON files were scraped from Twitter using firehose

## Workflow
1. Identify users who are sending tweets that contain suspicous accounts or accounts with tweets that are suspicious
2. Scrape these accounts for Arabic text, build a model based on these tweets 
3. Integrate new accounts and use old tweets to predict whether new tweets are suspicious 

## Results:
1. It works, i.e. it can identify whether a profile is suspicious or possibility terrorist related based on tweets. Needs more data and more time to build robust model.

## Extensibility
1. Could feed in more data to identify more suspended accounts
2. Pipeline to evaluate differences in vectorizers
3. Improved translation packages or libraries
4. Incorporate deep learning LSTM to perform training and predictions
5. To name a few



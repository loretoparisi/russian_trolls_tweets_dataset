# russian_trolls_tweets_dataset
Russian Troll Tweets Dataset

# Disclaimer
This dataset is taken as-it-is and published by **NBC News** in the article

[Twitter deleted 200,000 Russian troll tweets, Ben Popken, Feb.14.2018, NBC News](https://www.nbcnews.com/tech/social-media/now-available-more-200-000-deleted-russian-troll-tweets-n844731)

# Description
A database of more than 200,000 tweets that Twitter has tied to "malicious activity" from Russia-linked accounts during the 2016 U.S. presidential election.
To recreate a link to an individual tweet found in the spreadsheet, replace "user_key" in `https://twitter.com/user_key/status/tweet_id` with the screenname from the "user_key" field and "tweet_id" with the number in the "tweet_id" field.

# The Datasets

## Tweets
Tweets Dataset Header
```
"user_id","user_key","created_at","created_str","retweet_count","retweeted","favorite_count","text","tweet_id","source","hashtags","expanded_urls","posted","mentions","retweeted_status_id","in_reply_to_status_id"
```

## Users
Users Dataset Header
```
"id","location","name","followers_count","statuses_count","time_zone","verified","lang","screen_name","description","created_at","favourites_count","friends_count","listed_count"
```

## 3 million Russian troll tweets
From [fivethirtyeight/russian-troll-tweets](https://github.com/fivethirtyeight/russian-troll-tweets/).
This data was used in the FiveThirtyEight story [Why We’re Sharing 3 Million Russian Troll Tweets](https://fivethirtyeight.com/features/why-were-sharing-3-million-russian-troll-tweets/).


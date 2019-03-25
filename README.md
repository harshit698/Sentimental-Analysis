# Twitter Sentiment Analysis 
## Prediction of BJP Win 2019 using Twitter
#### The project is about searching the twitter for predicting the chances of BJP winning 2019 elections using popular [#hashtags](https://twitter.com/search?q=%23bjp&src=typd) and applying sentiment analysis on this using tweepy and textblob.
#### Few popular hashtags - 
### `#BJP` `#Modi` `#ModiAgain` `#PhirEkBarModiSarkar`
### `#ModiPhirse` `#ChowkidarModi` `#BJPFor2019` `#MainBhiChowkidar`

### About the Project

#### What is Sentiment Analysis?

Sentiment Analysis is the process of ‘computationally’ determining whether a piece of writing is positive, negative or neutral. It’s also known as opinion mining, deriving the opinion or attitude of a speaker.

#### Steps involved in this project

3 major steps in `main.py` code :

1. Authorize twitter API client.
2. Make a GET request to Twitter API to fetch tweets for a particular query.
3. Parse the tweets. Classify each tweet as positive, negative or neutral.
4. Shows Pie Charts for better visualisation.
5. Csv File for storing tweets
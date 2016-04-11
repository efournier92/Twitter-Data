## Twitter Data Challenge

This is a bit of code I wrote for parsing through an array of hashes.

I built my example working with a compound data structure, scraped from the Twitter API.

The `twitter_data` method returns the data structure used by the rest of my code.

**Based on the data obtained from calling the `twitter_data` method, `app.rb` contains code that outputs the following:**

1. Each username followed by its description (`NA` if none)

+ Each username followed by total number of followers

+ Each username and the length of that user's latest tweet

+ Each username followed by the total character count used in that user's last twenty tweets

+ The user with the most followers

+ The user with the most friends

+ The user with the greatest number of tweets

+ The users with a `description` listed in `twitter_data`

+ The users with a `location` listed in `twitter_data`

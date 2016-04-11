## Twitter Data Challenge

This is some code I wrote for parsing through an array of hashes. The example metaphor I built this code around was working with a compound data structure, scraped via the Twitter API.

In the example, the method `twitter_data` returns the data structure used by my code.

Based on the data obtained from calling the `twitter_data` method, `app.rb` contains code that outputs the following:

1. Each username followed by its description
..* `NA` if there is no description

2. Each username followed by total number of followers

3. Each username and the length of that user's latest tweet.

4. Each username followed by the total character count used in that user's last twenty tweets.

5. The user with the most followers

6. The user with the most friends

7. The user with the greatest number of tweets

8. The users with a `description` listed in `twitter_data`

9. The users have a `location` listed in `twitter_data`?

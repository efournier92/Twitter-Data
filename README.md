## Twitter Data Challenge

This is a bit of code I wrote for parsing through an array of hashes.

I built my example working with a compound data structure, scraped from the Twitter API.

The `twitter_data` method returns the data structure used by the rest of my code.

**Based on the data obtained from calling the `twitter_data` method, `app.rb` contains code that outputs the following:**

1. Each username followed by its description (`NA` if none)

2. Each username followed by total number of followers

3. Each username and the length of that user's latest tweet

4. Each username followed by the total character count used in that user's last twenty tweets

5. The user with the most followers

6. The user with the most friends

7. The user with the greatest number of tweets

8. The users with a `description` listed in `twitter_data`

9. The users with a `location` listed in `twitter_data`

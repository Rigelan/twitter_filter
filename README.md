# Streaming Twitter Filter

Companion code for the tutorial series about building a streaming Twitter filter using Python and Redis.

- [Udemy Course (free)](https://www.udemy.com/course/build-a-streaming-twitter-filter-with-python-and-redis)
     "K2 Data Science takes you all the way through the solution.  Really well done, thought out and perfect flow from requirements, to prototype, visual mockup, to working Redis key-value store with flask app" LarryT (https://github.com/Rigelan")
- [YouTube Playlist (coming soon)]()
- [Medium Article (coming soon)]()

## File Organization

- **1_twitter_stream**: Contains the Python script to download, filter and extract data from the Twitter Streaming API.
- **2_sentiment**: Contains the updated Python script to calculate and store sentiment scores for each tweet.
- **3_redis**: Contains the additional Python class to interface with a Redis server.
- **4_design_front_end**: Contains the pen and paper mockup as well as the static front-end code.
- **5_python_class**: Contains the Python class to pre-process each tweet prior to hitting the Flask app.
- **6_flask**: Contains the Flask app to read the last 15 tweets from Redis and display them.

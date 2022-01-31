# twitter-streaming-data-pipeline
GOAL: Implement a data pipeline, using your programming language of choice, that outputs a machine-learning ready dataset <br>
Steps Performed:
- Connect to the Twitter streaming API and do a keyword search on Justin Beiber
- Filter out all tweets having to do with music
- Store the tweets into a database 
- Avoid duplicates
- Produce a count of all tweets consumed
- Produce a count of unique tweets
Pre Requisite 1: Generate tokens on Twitter Developer Portal <br>
![Screen Shot 2022-01-31 at 12 26 25 AM](https://user-images.githubusercontent.com/31439770/151769021-4450bf11-3117-4cd2-a5e4-f51578fbec09.png)
Pre Requisite 2: Connect to Twitter API using endpoints according to your access level <br>
References Used:<br>
- https://developer.twitter.com/en/docs/twitter-api/tweets/search/introduction
- https://developer.twitter.com/en/docs/twitter-api/tweets/search/api-reference/get-tweets-search-recent<br>
Database Used:<br>
Postgres database on AWS Relational Database Service<br>
![Screen Shot 2022-01-31 at 1 35 52 AM](https://user-images.githubusercontent.com/31439770/151770180-1b3899e2-5774-4dd0-9d74-4d68a92bf88c.png)
Note: Bearer token, database username and password have been removed from the code for security and privacy purposes.

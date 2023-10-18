# news-aggregator-new-api

**Endpoints**

 - POST /register -> To register a new user.
 - POST /login -> To login a user.
 - GET /preferences -> To retrieve the news preferences based on logged-in user.
 - PUT /preferences -> To update the news preferences based on logged-in user.
 - GET /news -> To fetch news articles based on the logged-in user preferences.


## Optional Tasks
 - POST /news/:id/read -> Mark a news article as read.
 - POST /news/:id/favorite -> Mark a news article as a favorite.
 - GET /news/read -> Retrieve all read news articles.
 - GET /news/favorites -> Retrieve all favorite news articles.
 - GET /news/search/:keyword -> Search for news articles based on keywords

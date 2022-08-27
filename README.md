# auto-reply-twitter-bot

### Description

A simple JAVA project/Twitter Bot to search for Twitter Tweets, based on a search query, using Twitter's own API and to reply to all those tweets with a reply text. Could be integrated as REST API for higher access or could be integrated as Client Side application.

### Setup
1. Create a .env at root level of the project after cloning the project into local environment.
2. Go to twitter developers dashboard/portal and get yourself essential access. Make a project.
3. Go to settings->User Authentication settings. Check Read and Write app permission and select Web app/bot for type. Give a random url for Website Url and Callback url. Save.
4. In the .env file. Set the following keys in .env API_KEY, API_KEY_SECRET, BEARER_TOKEN, ACCESS_TOKEN, ACCESS_TOKEN_SECRET from the keys under developers dashboard-><project-name>.
5. Compile and run src/main/java/dwaipayan/App.java. Give input and execute.
### Limitations

1. The Search query only returns data from last 7 days. Querying from all data was allowed only for developers' with Academic access.
2. Could have implemented with a REST API for better distribution.


# Reddit Webscraping Project: Exploring the Palestine Subreddit 


Welcome to our Reddit webscraping project focusing on the Palestine subreddit. In this project, we delve into the heart of the community, meticulously collecting and analyzing data through the Reddit API.

## Team Members:
* Rihab Id m’hand
* Asmaa Bazighe
* Lina mouissou
* Yahia Bourraoui

## Project Structure:
### General Analysis:
This directory contains the script ***Reddit.ipynb***, which performs sentiment analysis on the titles of posts from the subreddit "Palestine". Additionally, it outputs two files:

* ***Palestine.csv***: Contains general data collected from the subreddit, including post IDs, titles, submissions, authors, timestamps, upvotes, percentage of upvotes, URLs, and number of comments
* ***headlines_score.csv***: Contains sentiment analysis scores associated with each post title.
### Comments Analysis:
This directory contains the script ***most-famous.ipynb***, which conducts sentiment analysis on the comments of the most popular posts in terms of the highest number of comments. It generates the following output data:

* ***Top-post-comments.csv***: Contains data extracted from comments of the top posts, including post IDs, comment IDs, comment bodies, comment authors, comment timestamps, and sentiment analysis scores.
### Old Submissions:
This directory contains the script ***reddit_collection_(2).ipynb***, which performs a more extensive search to collect older data from the "Palestine" subreddit. It outputs two files:

* ***Palestine.csv***: Contains historical data collected from the subreddit, including post IDs, titles, submissions, authors, timestamps, upvotes, percentage of upvotes, URLs, and number of comments.
* ***merged_data.csv***: Contains merged data from the sentiment analysis performed on the historical submissions, including sentiment scores associated with each submission.

## Licence:
This project is licensed under [MIT License].

# Profilator - User Guide
Profilator is Flask application for generating user's Twitter profile report. It was created by group of students who were participating in school project in order to improve their programming, communicating, learning and working in group skills.

This application collects, processes and shows information about any Twitter account. It shows diagrams, histograms, wordclouds created out of most frequent words and more.

## How to install and run our app?
1. Before you run our app, you need to clone this repository to your local computer at first place:
> git clone https://github.com/profilator/profilator.git
2. Then go to the project directory:
> cd profilator
3. Next, you need to install necessary packages with pip (you have to be in ~/profilator/ directory):
> pip3 install -r requirements.txt
4. Finally, head to source directory and run app server:
> cd source
> python app.py
5. Congratulations, you've made it! Now we can describe how to use our app.
### Important info
To run this app, you need to get the token and place it in the _~/profilator/source/_ directory.

## Main Page
The design of our application is as simple as it can be.
- At the top of the page there is simple bar with the logo of our project.
- Below the logo we can see the most important part here - the input bar. Here you can type the name of any existing Twitter account.
- At the bottom there are suggestions of nicknames. If you don't remember any nickname and you only want to test the profilator, give it a try.

## Header bar
Header bar shows basic information about account that is being analysed. Here there is description of every value that 'Header bar' section contains:
- _Twitter nickname_ - the unique name of Twitter account that is being currently targeted by our application.
- _Tweets_ - total number of current account's tweets.
- _Following_ - number of Twitter users followed by this account.
- _Followers_ - number of this account's followers.
- _Likes_ - amount of liked posts by this account.
- _Scanned Posts_ - quantity of scanned latest posts.
- _Posts Date Interval_ - dates of the earliest post and the latest one.
- _Input tab_ - a place where you can input any Twitter nickname that you want.

## Favorites
This histogram shows number of posts and their popularity (favorite count). It means, we can see how many posts received lots of 'favorites' and how many weren't so popular.

## Posts in days of week
It's a simple diagram, which describes amount of entries in every single day of week.

## Published posts in hours of day
This one is similar to previous one, but instead of days, it operates on hours. For example, we can see when the user likes to add new content the most.

## Replies count
Replies count let us know how many of this person's entries are posts and how many are replies. It's showed on simple pie chart. I'd like to mention, that the Twitter's API let us only get 200 latest user's activities. So keep that in mind.

## Tweets length
Length of entries frequency. It shows intervals of characters and numbers of tweets, whose lengths contains in mentioned intervals.

## Tweets grouped by content
It place gained groups depending on topic of it. So, If there were many motivational themed entries, the program will place them close to each other. The purpose of it is to extract the most common topics of entries.

## Wordcloud
It creates an image composed of words. Pretty smart and interesting way to present most frequently used words by this account. The bigger word is the more often it was written and vice versa.

## Enjoy our app!
We hope that you will use our application without any problems. If you have any questions, contact us via social media.

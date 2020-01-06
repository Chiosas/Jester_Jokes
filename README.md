# Jester Jokes - Project

![Jokes](https://short-funny.com/cartoon-jokes/400/donkey-joke.jpg)

Jester is an online joke recommender system developed by Ken Goldberg and the team at UC Berkeley. Users are presented jokes through an HTML client interface and allowed to rate jokes. Once a user rates all jokes in the gauge set, the system recommends new jokes to the user.

The dataset contains over 1.7 million continuous ratings (-10.00 to +10.00) of 150 jokes from 59,132 users. The dataset was collected between November 2006 - May 2009. The complete dataset has two CSV files:
* *jester_ratings.csv* - Ratings of jokes
* *jester_items.csv* - Contents of jokes

The ratings are real values ranging from -10.00 to +10.00.
As of May 2009, the jokes {7, 8, 13, 15, 16, 17, 18, 19} are the "gauge set".

The columns of *jester_ratings.csv* file are:

* User ID — unique ID of a website user,
* Joke ID — unique ID of a joke posted on the website,
* Rating — rating of the joke assigned by the user.

The columns of *jester_items.csv* file are:

* Joke ID — unique ID of a joke posted on the website,
* Joke Text — actual joke content.


We will use the dataset to build a collaborative filtering or hybrid recommender system model.

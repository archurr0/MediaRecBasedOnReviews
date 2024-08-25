Introduction - 

A movie/TV/Anime recommendation system that suggests media based on sentiment analysis of user reviews using NLP. The AI will identify certain aspects of the show that a majority of watchers liked or disliked by analyzing the reviews and can output a show based on the user’s desired elements of the show they want to watch.

Problem Statement - 

Often people search out and consume media that aligns with their tastes and interests. However, often these shows or movies are organized by genre only, which makes it hard to ascertain the nuances in each piece of media. For example, a show may be labeled as comedy, but only a certain type of comedy interests the watcher. For this reason, this NLP application will sift through user reviews to find out which aspects and specific details in the show were most liked. Perhaps the characters, plot, or action scenes were especially good, and the reviewers can expand upon these good aspects in a way that just looking at the genre or synopsis won't tell you.

Tools used - 

Website and Frontend built with HTML/CSS/SCSS/Flask (Python)

Machine Learning Model built with OpenAI API

Containerized with Docker

Launch the Application with Docker - 

$ git clone https://github.com/app-generator/boilerplate-code-flask.git
$ cd boilerplate-code-flask

$ docker-compose up --build 

Todo - 

Model training, tuning, and evaluation, integration into application using API

Publish web application to the internet
# Classifying Genre:<br>Using a Random Forest Model to predict genre

Blake Spencer<br>
February 2019

The goal of this project was to build a model that would take in features of a song provided by Spotiy's API to then predict what genre it belongs to. Choosing six generic genres defined by curated spotify playlists, 6000 songs were used to train the model.<br>

You can test the model yourself here:<br>
https://blake-spencer-projects.herokuapp.com/classification#model

The main steps where:

1. [Obtain the features of a song in a playlist and create dataframes](https://github.com/blakespencer/classifying-genre/blob/master/Spotify_api.ipynb)
2. [Train a model being able to predict and create data for Flask app to use](https://github.com/blakespencer/classifying-genre/blob/master/analysis.ipynb)
3. [Link Spotiy's API to try out the model on any song in their library](https://blake-spencer-projects.herokuapp.com/classification#model)

Each of the links above is a Jupyter Notebook file with Python code to complete each step.

The Flask App backend:

- [Flask app code in Python](https://github.com/blakespencer/personal-site-backend)

The React App frontend:

- [React app code in Javascript](https://github.com/blakespencer/personal-site-frontend)

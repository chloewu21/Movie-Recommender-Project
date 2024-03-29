# Movie Finder
## Introduction
With so many movies to choose from, it has become harder to find one that suits your personal taste. Movie Finder is a movie recommendation system that uses Python to produce accurate recommendations based on a film's genre, release year, and rating. Three different types of recommendation systems (content-based, collaborative, and demographic) that are commonly used by companies like Netflix and Amazon to recommend products and services were incorporated.
## Features
* Textbox to input a movie title
* Genre dropdown menu that filters out a chosen genre
* Release year dropdown menu that filters out a chosen year
* Table of results that displays movie id, recommendation score, title, genres, and release year
## Built With
* [2019 Movielens dataset (created by the University of Minnesota)](https://grouplens.org/datasets/movielens/25m/)
* Jupyter Notebook
* Python
* Voila
* Binder
## Usage
Binder link (click to launch): https://mybinder.org/v2/gh/chloewu21/Movie-Recommender-Project/HEAD?urlpath=voila%2Frender%2Fmovie_recommender.ipynb
1. Begin by inputting the title of a film you enjoyed.
2. Select a genre or release year from the dropdown menus to add additional filters (optional).
3. The top 10 most similar movies will be displayed below. <br />

To run the Jupyter notebook:
1. Clone the repository in your local system.
2. Create a conda environment and install libraries in the [environment.yml](https://github.com/chloewu21/Movie-Recommender-Project/blob/main/environment.yml) file with the command `conda env create -f environment.yml`.
4. In your terminal or command prompt, execute the command `voila .\movie_recommender.ipynb`. 
5. Try it out!

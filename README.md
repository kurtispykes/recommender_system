# Recommender System

The purpose of this project is to employ a comprehensive analysis of the movielens dataset to gain interesting insights that may be considered before exploring various ways of building a recommendation system.
The data may be accessed via [MovieLens 100K Dataset](https://grouplens.org/datasets/movielens/100k/) and it contains 3 data sources useful for our task - namely `u.data`, `u.item` and `u.user`and may be described as follows: 

**u.data** - The full dataset, 100K ratings by 943 users on 1682 items. Each User has rated atleast 20 movies. Users and items are numbered consecutively from 1. The data is randomly ordered and in formated in a tab seperated list of `user_id`, `item_id`, `rating` and `timestamp` -  `timestamp` is in UNIX seconds. 

**u.item** - Information about the movies; A tab seperated list of `movie_id`, `movie_title`, `release_date`, `video_release_date`, and `IMDb_url`. The following 19 fields are the genres where 1 indicates a movie is of a particular genre and 0 indicates that it is not. 

**u.user** - Demographic information about the users; A tab seperated list of `user_id`, `age`, `gender`, `occupation` and `zip_code`

## Dependencies 
* `pandas` == 1.0.5
* `numpy` == 1.19.1
* `matplotlib` == 3.2.2

Data directory: /data (data needs to be downloaded from https://grouplens.org/datasets/movielens/1m/)
Extract the zip and copy `u.data`, `u.item` and `u.user` to this directory.

Exploration Notebook: notebook/01_kpy_explorations.ipynb
Approaches to Recommendations Notebook: notebook/02_kpy_ideas.ipynb


Run each cell of the jupyter notebook in the order.

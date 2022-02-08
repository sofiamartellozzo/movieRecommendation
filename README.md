# movieRecommendation

Recommender System is a system that seeks to predict or filter preferences
according to the user’s choices. They are utilized in a variety
of areas including movies, music, news, books, research articles, search queries,
social tags, and products in general. This project is focused on movies.

## Group Components

| Surname    | Name       | E-mail                             | Person Code    |
|------------|------------|------------------------------------|----------------|
| Martellozzo| Sofia      | sofia.martellozzo@mail.polimi.it   | 10623060       |
| Nunziante  | Matteo     | matteo.nunziante@mail.polimi.it    | 10670132       |


## Algorithm description

Two different approaches have been used:


* Collaborative filtering + content-based filtering

* Neural networks

### Collaborative filtering

It builds a model from the user’s past behavior as well as similar decisions made by other
users. This model is then used to predict ratings for items that users may
have an interest in.

### Content-based filtering

It uses a series of discrete characteristics of an item in order to recommend additional
items with similar properties. Content-based filtering methods are totally
based on a description of the item and a profile of the user’s preferences.
It recommends items based on the user’s past preferences.

### Neural network

Neural networks are at the base of machine learning algorithms. In this project a NN for each user is been 
created. In that context, the aim of the neural network is to return a probability that a rating is given to a 
movie by the user.


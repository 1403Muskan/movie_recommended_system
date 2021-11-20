# Movie Recommender System
![Python](https://img.shields.io/badge/Python-3.8-blueviolet)
![DASHBOARDING TOOL](https://img.shields.io/badge/DASHBOARDING-TOOL-streamlit-red)
![API](https://img.shields.io/badge/API-TMDB-fcba03)
![DEPLOYMENT](https://img.shields.io/badge/DEPLOYMENT-Heroku-purple)

Content Based Recommender System recommends movies similar to the user entered movie using cosine similarity.

# Demo : 
https://app-recommend-movie.herokuapp.com/

## How to get the API key?
The poster of the movie is fetched by using API by TMDB.

Create an account in https://www.themoviedb.org/. Go in the settings and take the API key(v3 auth) and then go toh TMDB API where you will get the various API for the movies. The API used in project is : https://api.themoviedb.org/3/movie/(movie_id)?api_key=8265bd1679663a7ea12ac168da84d2e8&language=en-US , providing movie id you will get the details of the movie.

## How Cosine Similarity works?
Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.
  
  ![image](https://user-images.githubusercontent.com/36665975/70401457-a7530680-1a55-11ea-9158-97d4e8515ca4.png)

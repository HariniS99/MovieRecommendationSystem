# MovieRecommendationSystem

### Movie Recommendation based on Content with User Interface using Streamlit 

## Abstract:
Recommendations systems are an important part of suggesting items especially in streaming services. A recommendation system is a system that provides suggestions to users for certain resources like books, movies, songs, etc.
Recommendation systems have several benefits, the most important being customer satisfaction and revenue. 
## Problem statement:
  - The goal of the project is to recommend a movie to the user. 
  - Providing related content out of relevant and irrelevant collection of movies to users of online service providers.
## Different types of Recommendation Systems:
  #### Content based
   - uses metadata such as genre, producer, actor, musician to recommend items.
   - Content-based systems are based on the idea that if you liked a certain item, you are most likely to like something that is similar to it.
  #### Collaborative filtering
   - the behavior of a group of users is used to make recommendations to other users
   - There are two types of collaborative models **Memory-based** methods and **Model-based** methods
## Dataset:
  * We have used tmdb_5000_movies and tmdb_5000_credits datasets for our project.
  * We have collected the datasets from Kaggle website.
  * TMDB – The Movies Database – user editable database for movies
## Algorithms used:
  #### Cosine Similarity:
   Cosine Similarity is a measure for similarity between two non-zero vectors of an inner product space that measures the cosine of the angel between them .
  #### CountVectorizer: 
   CountVectorizer is used to convert a collection of text documents to a vector of term/token counts. It also enables the pre-processing of text data prior to generating the vector representation. This functionality makes it a highly flexible feature representation module for text.

## To run the code: 
```
Streamlit run app.py
```
 ## References:
  - Content-Based Movie Recommendation System Using Genre Correlation - SRS Reddy, Sravani Nalluri, Subramanyam Kunisetti, S. Ashok and B. Venkatesh
  - Dataset : https://www.kaggle.com/tmdb/tmdb-movie-metadata



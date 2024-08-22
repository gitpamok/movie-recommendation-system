# movie-recommendation-system

There are basically two types of recommender systems implemented in the project:-

**1. Content Based Filtering** - They suggest similar items based on a particular item. This system uses item metadata, such as genre, director, description, actors, etc. for movies, to make these recommendations. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.

**2. Collaborative Filtering** - This system matches persons with similar interests and provides recommendations based on this matching. Collaborative filters do not require item metadata like its content-based counterparts.

After preprocessing the datasets I decided to keep these columns in order to proceed further,

| Column | Description |
| --- | --- |
| Movie ID | Unique ID for identification of movie and fetch appropriate poster for the same |
| Title| Title was used to get recommendations |
| Tags | Tags column was made using 'Overview','Cast','Genres','Keywords','Crew'|
| crew | Kept it to fetch recommendations based on Directors |

## Built With

* Python 3.6
* nltk.stem.porter
* CountVectorizer
* cosine_similarity

## Imprtant Note:
Instead of the two systems implemented here in code, generally a hybrid of the two systems used.

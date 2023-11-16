# MAUVi
A content-based movie recommender system that focuses on the characteristics of the movies themselves. It analyzes the features of a movie (e.g., genre, actors, director) and matches them to the user's preferences. For example, if a user enjoys action movies with Tom Cruise, the system can recommend other action movies featuring Tom Cruise.
![mauvi](https://github.com/22anjalihasani/MAUVi/assets/76697404/e80283bb-269b-4acf-8575-3dbae5b08811)

I have worked specifically on features like genre, cast, crew, movie id, and overview which is the summary of a movie in order to determine the 5 most related movies that match the user's preferences. Natural Language processing techniques to remove stop words, for case standardization, have been used including the bag of words algorithm which extracts specific features from the text and to convert the text into vectors.
How does it decide which item is most similar to the item user likes? Here we use the similarity scores.
It is a numerical value that ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. Here I have cosine similarity as a metric that is used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space.


Movie Recommendation Engine

M1: Load TMDB 5000 dataset, merge movies + credits, parse JSON columns, build tags column
M2: CountVectorizer on tags, cosine similarity matrix 4803×4803, recommend() function, save similarity.pkl + movies.pkl
M3: Flask form — enter movie title → top 5 similar movies + similarity scores
M4: Deploy, live URL, dem

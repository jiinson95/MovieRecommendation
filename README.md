# MovieRecommendation
Built collaborative filtering recommendation engines and posted the result on the Data Column. https://datacolumn.wordpress.ncsu.edu/blog/2020/02/10/building-a-collaborative-filtering-recommendation-engine/ 

# Choose algorithm
## 1. User-based Collaborative Filtering
## 2. Item-based Collaborative Filtering

# Followings are the steps to build the engines:
# User-based Collaborative Filtering
1) Make a dictionary of users and all of the movies they rated
2) Create a Euclidean Similarity function
3) Create a recommend function
4) Input the Uwer ID and how many movies you want to recommend
5) Convert the movie ID to an actual movie title
6) Evaluate the recommendation function

# Item-based Collaborative Filtering
1) Convert raw IDs into movie names and vice versa
2) Compute similarities between movies based on users' ratings
3) Read the raw IDs <-> movie names mappings
4) Retrieve inner IDof Snow White and the Seven Dwarfs and inner IDs of the nearest neighbors of Snow White and the Seven Dwarfs
5) Convert inner IDs of the neighbors into movie names
6) Evaluate the recommendation function 

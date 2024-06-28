# Movie Recommendation System

This project is a simple movie recommendation system that uses collaborative filtering, Singular Value Decomposition (SVD), and cosine similarity to recommend movies. The dataset used is similar to the Netflix movie ratings data.

## Overview

This recommendation system:
- Reads and processes movie ratings data.
- Creates a user-movie rating matrix.
- Normalizes the rating matrix.
- Applies Singular Value Decomposition (SVD) to reduce the dimensionality of the data.
- Uses cosine similarity to find and recommend similar movies.
- Visualizes the results using Principal Component Analysis (PCA).

## Methodology

1. **Collaborative Filtering**: This approach relies on user interactions (ratings) with movies to find similar movies and recommend them.

2. **Singular Value Decomposition (SVD)**: SVD is used to reduce the dimensionality of the user-movie rating matrix, making it easier to compute similarities and recommendations.

3. **Cosine Similarity**: This metric measures the cosine of the angle between two vectors (in this case, movie vectors). It is used to find movies that are similar to a given movie.

## Files

- `ratings.dat`: Contains user ratings for movies.
- `movies.dat`: Contains movie titles and genres.
- `recommendation_system.py`: The main Python script that implements the recommendation system.

## How to Run

1. **Install Necessary Libraries**: Make sure you have the required Python libraries installed. You can install them using pip:

   ```sh
   pip install numpy pandas matplotlib scikit-learn
2.**Prepare Data Files: Ensure you have the ratings.dat and movies.dat files in the same directory as your script.

3.**Run the Script: Open a terminal in your project directory and run the script:
-python recommendation_system.py

##Example Output
**Recommendations for <Movie Title>: 
-1. Similar Movie 1
-2. Similar Movie 2
-...
##Visualization
The PCA plot shows the distribution of movies in a 2D space, with the queried movie highlighted in blue and the recommended movies highlighted in red.

##Conclusion
This project demonstrates a basic movie recommendation system using collaborative filtering, SVD, and cosine similarity. It provides a simple yet effective way to recommend movies based on user ratings.

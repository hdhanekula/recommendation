# recommendation


1. Bar Chart of Movie Ratings:

   A bar chart was plotted showing the count of each unique rating given by User 2.

   The chart was sorted for better visualization using sort_index().


2. Top Movies of User 2:

   The top-rated movies were identified based on User 2's highest ratings.

   Movie titles were retrieved by merging with the movie dataset using merge().


3. Finding the Most Similar User:

   Two similarity metrics were used to find the most similar user:

      Cosine Similarity (measuring angle-based similarity)

      Euclidean Distance (measuring absolute rating differences)

  The closest user to User 2 was identified based on these metrics.


4. Movie Recommendations for User 2:

   Movies highly rated by the most similar user (but not watched by User 2) were recommended.


5. Analysis of Results:

   The recommendations were evaluated to see if they aligned with User 2’s preferences.

     Cosine Similarity was preferred because it normalizes rating patterns, making it useful for user-based collaborative filtering.

     Euclidean Distance was used for comparison, but it might not be as effective due to differences in rating scales.
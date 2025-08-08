Hybrid Movie Recommendation Engine
(Python, Numpy, Scikit-learn, NLP, Cosine Similarity)

Designed a three-tier recommendation system combining demographic, content-based, and collaborative filtering to personalize movie suggestions.

Demographic Filtering: Ranked top 10 films by weighted ratings (IMDb formula) for cold-start scenarios.

Content-Based Filtering: Vectorized movie plots/genres using TF-IDF and directors/actors using CountVectorizer then calculated cosine similarity to recommend films with comparable themes.

Collaborative Filtering(User based): Identified similar users via cosine similarity on user-item matrices.

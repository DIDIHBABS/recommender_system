
Collaborative filtering (CF) is a method used by recommender systems to make predictions about the interests of a user by collecting preferences from many users. The underlying assumption of CF is that if a person A has the same opinion as a person B on an issue, A is more likely to have B's opinion on a different issue.

Types of Collaborative Filtering

- User-Based Collaborative Filtering: This approach finds users similar to the target user and recommends items these similar users liked.

- Item-Based Collaborative Filtering: Instead of finding user’s look-alike, it finds item’s look-alike. Once the items are identified, it recommends items similar to what the user has liked in the past.

Measure for determining user or item simillarity 
Jaccard Similarity: Effective for binary data.
Pearson Correlation: Suitable for continuous data.
Cosine Similarity: Often used for user-based CF.




Recent advancements in CF have been discussed in papers like "Neural Collaborative Filtering" (He et al., 2017), which introduces a neural network-based approach to collaborative filtering, moving beyond traditional matrix factorization methods.

A significant contribution in this area is "Deep Learning-based Recommender System: A Survey and New Perspectives" (Zhang et al., 2019), which discusses various deep learning techniques applicable in CF.

Generally techniques that perform best for this task including
- Matrix factorization (Singular Value Decomposition SVD, - Alternating Least Squares ALS)
- memory-based models 
- nearest neighbors models 


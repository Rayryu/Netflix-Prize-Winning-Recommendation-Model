# Netflix-Prize-Winning-Recommendation-Model

This project involves implementing 5 models for film recommendation systems based on Netflix data.

The models to be implemented are presented in the [article](https://www.cs.rochester.edu/twiki/pub/Main/HarpSeminar/Factorization_Meets_the_Neighborhood-_a_Multifaceted_Collaborative_Filtering_Model.pdf) by Koren. The final model in the article is titled Integrated Model. It won the Netflix Prize in 2008.

The dataset (downloadable from this link) contains 100 million ratings of 480,000 users on 17,000 films. The goal of each of the models to be implemented consists in predicting the rating of a given user on all of the films that the user has not yet watched. The recommendation for this user is to offer him the list of films in descending order of predicted ratings.

Each model is formulated as a Linear Regression whose parameters are to be estimated by the Gradient Descent procedure. The performance of each model is evaluated by the RMSE criterion (square root of the Mean Squared Error).

The models to be implemented are:

- Baseline Estimates described in section 2.1 of the article;
- Correlation-Based Neighborhood described by equation (3) in section 2.2;
- Correlation-Based Neighborhood with implicit data described by equation (10) in section 3;
- SVD ++ described by equation (15) in section 4;
- Integrated Model described by equation (16) in section 5.

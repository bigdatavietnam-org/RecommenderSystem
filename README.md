# Part 1
## RecommenderSystem
The project is a dating website recommendation system.
Here we build two collaborative filtering models, KNN and SVD. We select the most popular 10000 male and 1000 female users' ratings from Czech dating site libiseti in 2006 http://www.occamslab.com/petricek/data/ (where poplairy is calculated by the number of rating received).
The goal is to provide users with personalized dating candidates, according to the rating history of a user to the others. This project implements collaborative filtering algorithms in two parts: "building from scratch" and "using Surprise package." Each part would construct two models based on neighborhood-based or model-based algorithms. Through tuning the hyper parameter, evaluating the coverage, and calculating the accuracy, the models are continuously optimized. 

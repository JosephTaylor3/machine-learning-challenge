# machine-learning-challenge
Machine Learning Homework

Comparison and Evaluation of Models: 
Originally, my intent was to compare a KNN model versus a Deep Neural Network with 2 hidden layers, with the expectation that the NN would outperform the KNN significantly. However, I had difficulty tuning the NN, and was unable to produce a NN model that provided any significant accuracy. This is not to say that a properly developed NN would not have outperformed the KNN, but in this instance the best performing that I was able to create was the KNN. 

KNN Model Overview: 
- Utilized Grid Search to optimize parameters 
- Optimal parameters found: {'metric': 'manhattan', 'n_neighbors': 15, 'weights': 'distance'}
- Accuracy achieved: 0.832365003417635
- Conclusion: this model could definitely be used for classifying exoplanet candidates, but should sought to be improved upon 

# custom_nearest_neighbors
#### Regression based on k-nearest neighbors
The target is predicted by weighted average of the targets associated of the k nearest neighbors in the training set, <br />
proportional to the inverse of the distances.
#### Weights
Before calculating distances features are scaled using weights which are optimized by the model. <br />
Weights are larger for features with more importance.

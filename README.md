# Dimensionality-Reduction-for-visualization
PCA
PCA is applied on MNIST dataset to convert 784 features into 2D for visualization purpose. PCA is applied from scratch in the code (not using sklearn library)

Confusion matrix is used to calcualte the eigen vector and eigen values and 2 vectors with maximum eigen values are used for the visualization.
Maximum eigen values refers to the percentage of variance that is explained by a particular feature

t-SNE (t-distribution stochastic neighborhood embedding)
t-SNE is used to reduce the dimensions from 784 to 2
It gives better results than PCA (computationally expensive)

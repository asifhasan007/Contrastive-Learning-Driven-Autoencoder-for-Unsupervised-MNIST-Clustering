Enhanced Autoencoder with Contrastive Learning for MNIST Clustering
A PyTorch implementation of an enhanced convolutional autoencoder that combines reconstruction loss with contrastive learning for improved feature representation. The model learns meaningful embeddings that are then used for unsupervised clustering using K-Means with silhouette score optimization.
Key Features:

Convolutional autoencoder with batch normalization and LeakyReLU activation
Contrastive learning loss for better feature separation
Automated hyperparameter tuning for optimal clustering
t-SNE visualization for embedding analysis
Comprehensive evaluation metrics (Silhouette Score, Davies-Bouldin Index)

Tech Stack: PyTorch, scikit-learn, NumPy, Matplotlib, PIL

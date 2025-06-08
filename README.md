# unsupervised--learning--clustering--kmeans--pca
## Machine Learning Exercise 5

## Overview
This project applies K-Means clustering and Principal Component Analysis (PCA) to synthetic 2D datasets. The goal is to explore unsupervised learning techniques for pattern recognition and dimensionality reduction.

The assignment involves working with both convex and non-convex synthetic datasets to observe how K-Means and PCA behave in different scenarios.

## K-Means Clustering Progression
### Iteration 1: Random Initialization
![WhatsApp Image 2025-06-08 at 19 37 25_09563687](https://github.com/user-attachments/assets/da4d763a-ccf8-4d46-8504-82ca1fedb6f8)

In the first iteration, cluster centers (red Xs) are placed randomly. The K-Means algorithm begins by assigning points to the nearest center, but initial assignments are often inaccurate due to poor starting positions.

Key Insight: Early cluster boundaries are unreliable — some clusters overlap heavily or are assigned incorrectly.

### Iteration 6: Converged Clusters
![WhatsApp Image 2025-06-08 at 19 37 35_9e09f7b4](https://github.com/user-attachments/assets/73d65222-e24f-4b57-a0ad-5a4cff4152c6)

By the 6th iteration, K-Means has converged: cluster centers have stabilized and point assignments are now much more accurate.

Key Insight: The algorithm has successfully identified the four true clusters. This image highlights how K-Means iteratively improves its cluster assignments through center updates.

## PCA Image Reconstruction
![image](https://github.com/user-attachments/assets/7b1609a3-17aa-411e-b6ed-0f2336e8be1d)

This figure demonstrates how Principal Component Analysis (PCA) can be used to compress and reconstruct images. The original image on the left is progressively reconstructed using only the top n principal components.

- n = 3: Only very coarse structure is retained — the image is blurry and hard to recognize.
- n = 10: Some recognizable features begin to emerge, but the image remains noisy.
- n = 100: The reconstruction closely resembles the original, with much more detail restored.

## Convolutional Neural Network (CNN) Architecture
![image](https://github.com/user-attachments/assets/c13bfbc5-8c74-4f03-8feb-161620f139f9)
This illustration shows the architecture of a Convolutional Neural Network (CNN) used for image classification.

- The input image (e.g., a boat) is passed through multiple convolution layers with ReLU activation, which extract spatial features.
- Pooling layers reduce spatial dimensions and help retain important information.
- The resulting feature maps are flattened and passed through fully connected layers.
- The final layer outputs probabilities for each class — here, the model predicts “boat” with a confidence of 94%.






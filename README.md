This repository contains custom implementations of various machine learning models and algorithms. It involves two datasets - an Animal Image Dataset for image classification and clustering, and a News Text Dataset for text classification.

For the Vision Dataset, tasks include:
* 10-class classification problem with a CNN.
* Dimensionality reduction using PCA and applying MLP.
* Transformer model with self-attention on PCA’ed features.
* K-means on raw pixels and PCA’ed data features.
* Ensemble of CNN/MLP/Decision trees in an Ada-boost framework.
* Feature extraction from a pre-trained Imagenet, appended and trained an MLP on top of it.
  
For the Text Tasks, tasks include:
* 12-class classification problem using an MLP.
* Transformer with self-attention.
* Random forest and a Gradient boosted tree.

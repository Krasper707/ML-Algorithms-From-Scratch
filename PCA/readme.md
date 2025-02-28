# Principal Component Analysis (PCA) from Scratch
A clean, efficient implementation of Principal Component Analysis (PCA) from scratch in Python. This repository provides a comprehensive implementation that follows scikit-learn's API style while exposing the underlying mathematics of PCA.

### 🚀 Features


- Pure NumPy implementation (no black-box dependencies)
- Support for explained variance analysis
- Visualization utilities


### 🧮 Mathematical Background


Principal Component Analysis works by finding the directions (principal components) that maximize the variance in the dataset. Mathematically, this involves:

- Centering the data: Subtract the mean from each feature
- Computing the covariance matrix: Measure how features vary together
- Eigendecomposition: Find eigenvalues and eigenvectors of the covariance matrix
- Selecting principal components: Choose eigenvectors with largest eigenvalues
- Projecting data: Transform original data to the new coordinate syst


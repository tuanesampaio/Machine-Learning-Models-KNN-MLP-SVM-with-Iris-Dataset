# Machine Learning Models: KNN, MLP, SVM with Iris Dataset

This repository contains implementations of K-Nearest Neighbors (KNN), Multi-Layer Perceptron (MLP), and Support Vector Machine (SVM) machine learning algorithms using the Iris dataset. Each model is tested with various configurations and evaluated using 10-fold cross-validation.

## Dataset

The Iris dataset is a classic dataset in machine learning and contains measurements of various iris flowers. It consists of 150 samples with 4 features each (sepal length, sepal width, petal length, petal width), and each sample belongs to one of three classes (setosa, versicolor, virginica).

## Models Implemented

### K-Nearest Neighbors (KNN)
- Implemented KNN algorithm using different numbers of nearest neighbors.
- Evaluated performance using 10-fold cross-validation.

### Multi-Layer Perceptron (MLP)
- Implemented MLP using TensorFlow/Keras with varying numbers of hidden layers and neurons per layer.
- Tested different architectures to evaluate model performance.
- Used 10-fold cross-validation for robust evaluation.

### Support Vector Machine (SVM)
- Implemented SVM using scikit-learn with at least two different kernels (e.g., linear, radial basis function).
- Assessed SVM performance using 10-fold cross-validation.

## Folder Structure

- `data/`: Contains the Iris dataset file or data loading scripts.
- `src/`: Includes Python or R scripts for each machine learning model.
- `results/`: Stores evaluation metrics and visualizations.

## Usage

1. **Clone the repository:**

# Clustering Algorithm Comparison

This repository contains Python code to compare different clustering algorithms using the PyCaret library. The code evaluates the performance of various clustering algorithms under different preprocessing conditions and with varying numbers of clusters.

## Prerequisites

Before running the code, ensure you have the following dependencies installed:

- pandas
- pycaret
- ucimlrepo

You can install these dependencies using pip:

```bash
pip install pandas
```
```bash
pip install pycaret
```
```bash
pip install ucimlrepo
```

## Usage

1. Clone the repository or download the provided code files.

2. Open a Python environment and execute the provided code.

3. The code will fetch the Wholesale Customers dataset from the UCI Machine Learning Repository, preprocess the data, and compare the performance of different clustering algorithms.

## Code Overview

- `wholesale_customers.py`: Python script containing the code to compare clustering algorithms.

- `README.md`: This README file providing instructions and information about the code.

## Dataset

The code fetches the Wholesale Customers dataset from the UCI Machine Learning Repository. This dataset contains information about the annual spending of various customers on different product categories.

## Clustering Algorithms

The following clustering algorithms are compared in the code:

- K-Means
- Affinity Propagation
- Mean Shift
- Spectral Clustering
- Hierarchical Clustering
- DBSCAN
- OPTICS
- Birch

## Evaluation Metrics

The code evaluates the clustering algorithms based on the following metrics:

- Silhouette Score
- Calinski Harabasz Score
- Davies Bouldin Score
- Inertia
- Score

## Parameters and Preprocessing Techniques

The code compares the clustering algorithms under different preprocessing conditions, including:

- No Data Processing
- Normalization
- Transformation
- Normalization + PCA
- Transformation + Normalization
- Transformation + Normalization + PCA

## Results

The evaluation results for each algorithm, parameter, and number of clusters are stored in the `evaluation_results` dictionary.

## License

This code is provided under the MIT License. See the LICENSE file for more details.

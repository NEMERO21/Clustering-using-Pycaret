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

- `main.py`: Python script containing the code to compare clustering algorithms.

- `README.md`: This README file providing instructions and information about the code.

## Dataset

The code fetches the Wholesale Customers dataset from the UCI Machine Learning Repository. This dataset contains information about the annual spending of various customers on different product categories. You can also just download the `Wholesale customers data.csv` file of the dataset provided in this repository. 

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

The evaluation results for each algorithm, parameter, and number of clusters are stored in the `evaluation_results` dictionary. The output displays the following for each combination of Clustering Algorithm, Cluster numbers, Evaluation Metrics, Parameters and Processing Techniques:

- Pipeline Plot:
 ![image](https://github.com/NEMERO21/Clustering-using-Pycaret/assets/97607950/9609e9b1-0c3d-4a96-ae97-a48cad4410fa)

- t-SNE (3d) Dimension:
  ![image](https://github.com/NEMERO21/Clustering-using-Pycaret/assets/97607950/ddefa625-4030-4ff1-9223-aefa57792524)

- Cluster t-SNE (3d):
  ![image](https://github.com/NEMERO21/Clustering-using-Pycaret/assets/97607950/e26526ef-5c4b-4c47-bdb7-fddad2b1232a)

- Elbow Plot:
  ![image](https://github.com/NEMERO21/Clustering-using-Pycaret/assets/97607950/e2dbccc0-20d7-4c35-9cac-ba20729f8440)

- Silhouette Plot:
  ![image](https://github.com/NEMERO21/Clustering-using-Pycaret/assets/97607950/13d1f52e-d955-4c7b-ae66-14c3a87b245a)

- Distance Plot:
  ![image](https://github.com/NEMERO21/Clustering-using-Pycaret/assets/97607950/4b36e30a-f02c-4b17-b56b-d3ecc48e2ad7)

- Distribution Plot:
  ![image](https://github.com/NEMERO21/Clustering-using-Pycaret/assets/97607950/982aab8c-b63b-4712-aeb4-a996038478c0)


## License

This code is provided under the MIT License. See the LICENSE file for more details.

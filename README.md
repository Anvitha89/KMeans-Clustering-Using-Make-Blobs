# KMeans Clustering Using Make Blobs

## Project Overview
This project demonstrates **KMeans Clustering**, an unsupervised machine learning algorithm, using a synthetic dataset generated with Scikit-learn's `make_blobs()`.

The project explores different numbers of clusters and uses the Silhouette Score to evaluate clustering performance.

## Technologies Used
- Python
- NumPy
- Scikit-learn
- Jupyter Notebook

## Dataset
- Dataset: Synthetic dataset generated using `make_blobs()`
- Number of samples: 2,000
- Number of features: 2
- Custom cluster centers and standard deviations
- Random state: 43

## Algorithm
**KMeans Clustering**

The KMeans algorithm groups data points into clusters based on their similarity.

## Experiments and Results

Tested different values of K (number of clusters):

| Number of Clusters (K) | Silhouette Score |
|---|---:|
| 2 | 0.5513 |
| 3 | 0.5633 |
| 4 | 0.6465 |
| 5 | 0.5599 |

Based on the experiments, **K = 4** achieved the highest Silhouette Score among the tested values.

## Conclusion
Applied KMeans clustering to a synthetic dataset and evaluated different cluster counts using the Silhouette Score.

The experiment showed that K = 4 produced the best clustering result among the tested values.

## Repository Contents
- `KMeans-Clustering-Using-Make-Blobs.ipynb` – Jupyter Notebook containing the implementation and experiments.

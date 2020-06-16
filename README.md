# Kmeans algorithm

A custom implementation of Kmeans algorithm in Python (written inside a Jupyter Notebook).

The object Custom_KMeans is based on the scikit-learn implementation.

## Usage

In a new cell, create an instance of the Custom_KMeans object then fit and predict cluster labels of a normalized dataset X.

```python
model = Custom_KMeans(n_clusters = 2) 
cluster_predictions = model.fit_predict(X)
```

To get the centroids: 

```python
centroids = model.cluster_centers_
```





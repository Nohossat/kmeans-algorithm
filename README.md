# Kmeans algorithm

A custom implementation of Kmeans algorithm in Python (written inside a Jupyter Notebook).

The object Custom_KMeans is based on the scikit-learn implementation.

## Installation

```python
git clone https://github.com/Nohossat/kmeans-algorithm.git
cd kmeans-algorithm
python -m venv venv/ 
source /venv/bin/activate # OSX - bash/zsh
.\venv\Scripts\activate # Windows - Powershell
pip install -r requirements.txt
```

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

You can also plot the different stages of the algorithm for the first iteration of Kmeans. If needed, set the plot attribute to True during initialization.

```python
model = Custom_KMeans(n_clusters = 2, plot = True) 
```







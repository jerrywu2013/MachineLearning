# K-means
```
apt install build-essential
apt install python-dev
pip install numpy
pip install scikit-learn
```
```
from sklearn import datasets
from sklearn.cluster import KMeans
import numpy as np
iris = datasets.load_iris()
X = iris.data[:, :2] 
y_pred = KMeans(n_clusters=3, random_state=random_state).fit_predict(X)
for n,a in zip(list(X),list(y_pred)):
    print (n,a)
```

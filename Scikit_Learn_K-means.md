# K-means
```
sudo pip install -U scikit-learn
sudo pip install numpy
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

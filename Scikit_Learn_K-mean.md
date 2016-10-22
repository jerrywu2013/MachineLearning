# Scikit-Learn
```
from sklearn import datasets
from sklearn.cluster import KMeans
import numpy as np
X = iris.data[:, :2] 
y_pred = KMeans(n_clusters=3, random_state=random_state).fit_predict(X)

```

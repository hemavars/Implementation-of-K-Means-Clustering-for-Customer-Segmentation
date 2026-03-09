# Implementation-of-K-Means-Clustering-for-Customer-Segmentation

## AIM:

To write a program to implement the K Means Clustering for Customer Segmentation.

## Equipments Required:

1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm

1. Choose the number of clusters (K).

2. Randomly initialize K centroids.

3. Assign each data point to the nearest centroid.

4. Recalculate the centroids.

5. Repeat steps 3 and 4 until centroids do not change.
## Program:

```
/*
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.cluster import KMeans
data = pd.read_csv("Mail_Customers.csv")
X = data[['Annual Income (k$)', 'Spending Score (1-100)']]
print(data.head())
kmeans = KMeans(n_clusters=5, random_state=42)
y_kmeans = kmeans.fit_predict(X)


data['Cluster'] = y_kmeans

print("\nClustered Data:")
print(data.head())


plt.figure()
plt.scatter(X[y_kmeans == 0]['Annual Income (k$)'], 
            X[y_kmeans == 0]['Spending Score (1-100)'], label='Cluster 0')

plt.scatter(X[y_kmeans == 1]['Annual Income (k$)'], 
            X[y_kmeans == 1]['Spending Score (1-100)'], label='Cluster 1')

plt.scatter(X[y_kmeans == 2]['Annual Income (k$)'], 
            X[y_kmeans == 2]['Spending Score (1-100)'], label='Cluster 2')

plt.scatter(X[y_kmeans == 3]['Annual Income (k$)'], 
            X[y_kmeans == 3]['Spending Score (1-100)'], label='Cluster 3')

plt.scatter(X[y_kmeans == 4]['Annual Income (k$)'], 
            X[y_kmeans == 4]['Spending Score (1-100)'], label='Cluster 4')

plt.scatter(kmeans.cluster_centers_[:,0], 
            kmeans.cluster_centers_[:,1], 
            s=200, label='Centroids')

plt.title("Customer Segmentation using K-Means")
plt.xlabel("Annual Income (k$)")
plt.ylabel("Spending Score (1-100)")
plt.legend()
plt.show()

Developed by: HEMAVARSHINI A
RegisterNumber:  25017769
*/
```

## Output:

<img width="803" height="317" alt="Screenshot 2026-03-08 232857" src="https://github.com/user-attachments/assets/8cb50214-fa7c-44be-ada7-e1d8f1a70b76" />

<img width="889" height="585" alt="Screenshot 2026-03-08 232913" src="https://github.com/user-attachments/assets/43844c96-723c-4aa0-a88e-dd1f9502de3f" />

## Result:

Thus the program to implement the K Means Clustering for Customer Segmentation is written and verified using python programming.

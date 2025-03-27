# CryptoClustering

Unsupervised learning challenge
- using both the KMeans method alone and with principal compenent analysis (3 components used), cryptocurrency data is grouped into clusters for predictive use.
- Both models are fit and transformed to the crypto data and then scaled using the Standard Scaler from sci-kit learn with the coin id as the index for ease.
- An elbow curve is graphed for both models, showing the best value of k (clusters) to be 4.
<img width="706" alt="Screenshot 2025-03-27 at 12 13 38 PM" src="https://github.com/user-attachments/assets/2b268163-6319-43f7-bb2a-814ef3081986" />
<img width="706" alt="Screenshot 2025-03-27 at 12 14 48 PM" src="https://github.com/user-attachments/assets/3d1603fb-a75c-48b7-9ea4-8d749885933d" />
- For both models, a KMeans of 4 is used to predict data clusters
- in Kmeans alone, the two comparative values are 24 hr price change and 7 day price change for the KMeans model and, the colors as the predicted clusters
<img width="671" alt="Screenshot 2025-03-27 at 12 18 14 PM" src="https://github.com/user-attachments/assets/851045b2-a215-44ff-a816-90f452252010" />
- in PCA paired with KMeans, the first two components are compared with the colors as the predicted clusters.
 <img width="664" alt="Screenshot 2025-03-27 at 12 19 37 PM" src="https://github.com/user-attachments/assets/981bcb3c-6d5a-4404-8388-bc6afdf0831a" />
 - While both models call for  four clusters, the PCA model demonstrates increased clarity as to why four clusters are needed to decrease the inertia in the elbow curve, cleary showing the two points as outliers to the rest of the data points. 


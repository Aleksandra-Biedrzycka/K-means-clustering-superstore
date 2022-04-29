# store
Clustering (using k-means method) store clients in odrer to findout their products preferences. Dataset from kaggle: https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

The goal was to grup clients by the key: in which State clients buy products from which category, and what is the profit.
First data was cleaned and prepare to analize.
Then, from the elbow and silhouette method, it was decided that there was 3 group of clients.
By the K-means method the clients can be divided into 3 groups (represented by the centers of clusters):
1st cluster: Clients from Minnesota, buy technology produkts. Profit from that clients: 106 coins.
2nd cluster: Clients from Virginia, buy office products. Profit from that clients: 20 coins.
3rd cluster: Clients from Utah, buy office products. Profit from that clients: 3 coins.

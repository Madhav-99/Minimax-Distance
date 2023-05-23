# Minimax-Distance
The given Project is based on the Research Paper "Classification with Minimax Distance Measures" by Morteza Haghir Chehreghani
Aim: to classify data points into different classes based on the concept of minimizing the maximum distance between a data point and the centroids of each class

Minimax distance: The Minimax distance is a distance metric that measures the maximum distance between a data point and the centroids of each class. It seeks to minimize this maximum distance in order to assign the data point to the most appropriate class.

Algorithm:
1. Get the complete graph with edge weights as the base distance between the vertices(treat each datapoint as vertex)
2. Compute the Minimum Spanning tree out of it.
3. Get the pairwise minimax distance between each vertex.
4. After going through the certain procedure.
5. Apply singular value decomposition and pick first k eigen values and the vectors that represents the vector in the embedded space.

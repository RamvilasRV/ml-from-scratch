KNN (classification Algorithm)

This is a classification algorithm that classifies a new data point based on the nearest data points that lie around it.
Takes the distance metric and the value of K as the paramters.

- Distance metric measure the closeness of a data point to another data point. It can be calulated using multiple methods like Euclidean distance, Manhattan Distance, Minkowski Distance, Cosine Similarity.
- K is the number of nearest neighbours to consider. (Rule of thumb - Start the K value with $$\sqrt{N}$$

Choosing the value of K depends on the input data.
Data with high noise will perform much better with higher value of K. It is also recommended to choose a odd number for K to avoid ties.


PROS:
- Easy to implement
- Less number of hyper parameters
- Very adaptible

CONS:
- Does not scale very well, since the data is stored in the memory.
- Curse of Dimentionality. Does not perform well with high dimentional data.
- Overfitting.


USECASES:
- Data preprocessing (Missing data imputaion)
- Finance
- Health Care (calulation of most likely gene expressions)

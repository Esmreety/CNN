
Explanation of CNN model:

The 1st hidden layer is a convolution layer and 32 filters each of size 5*5 is used followed by a maxpooling layer with a pool size of 2*2. Another convolution layer with 64 filters with size 5*5 each foolowed by a maxpooling layer with a pool size of 2*2. The next layer is Flatten layer that converts 2D matrix data to 1D vector before builfing fully connected layer. After that a fully connected layer with 1024 neurons and relu activation function is used. And then Dropout regularization is used to reduce overfitting.  We add a dense layers at the end which is used for class prediction (0–9). That is why it has 10 neurons. It is also called output layer. This layer uses softmax activation function instead of ReLU.

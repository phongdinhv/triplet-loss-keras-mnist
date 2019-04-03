# triplet-loss-keras-mnist
# A simple Keras implementation of triplet loss for MNIST images embeddings

- I use embeddings size of 32, which result in faster converge and more stability during training
- The implementation use all anchor-positive and hard-negative for triplet generate. More specifically, I use 10 sample per digits while selecting 5 negative digits

# A simple Keras implementation of triplet loss for MNIST digit embeddings

- I use embedding size of 32, which result in faster converge and more stability during training. You can try to increase the embeddings size but remember to increase network depth.
- The implementation use all anchor-positive and hard-negative for triplet generate. More specifically, I use 10 sample per digits while selecting 5 negative digits
- Visualize result using tSNE on MNIST test set: 
![alt text](https://github.com/phongdinhv/triplet-loss-keras-mnist/blob/master/mnist-triplet-loss.png)

Requirements:
- tensorflow, keras, matplotlib (for visualize), sklearn (for tSNE), jupyter notebook

How to use this repo:
- The notebook contain all thing you need (e.g data loader, model, triplet loss implementation, ...).
- Share if you like my work!

References: 
- FaceNet: A Unified Embedding for Face Recognition and Clustering: https://arxiv.org/abs/1503.03832
- tSNE to visualize digits: https://scipy-lectures.org/packages/scikit-learn/auto_examples/plot_tsne.html

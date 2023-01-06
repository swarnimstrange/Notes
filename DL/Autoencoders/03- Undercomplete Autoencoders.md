# Undercomplete Autoencoders

- An autoencoder whose code dimension is less than input dimension is called undercomplete autoencoder

Architechture form -:

- constrain number of nodes present in the hidden layer of the network

- limiting the amount of information that can flow through the network

- by penalising the network according to the reconstruction error, the model can then learn the most important attributes of the input data and how to best recontruct the original input from encoded state.

- copying the input to the output may sound useless, but we are training the autoencoder to perform the input copying task that will result in hidden layer h taking on useful properties. One way to obtain useful features is to constrain h to have a smaller dimension than input x.
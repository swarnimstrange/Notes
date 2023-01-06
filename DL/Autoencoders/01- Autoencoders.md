# Autoencoders

- artificial neural networks capable of learning efficient representations of the input data, called codings, without any supervision.

- these codings typically have a much lower dimensionality that the input data, making autoenders useful for dimentionality reduction and compression.

- code is the compression of the input, also called as latent-space representation.

- More importantly, autoencoders act as powerful feature detectors, and they can be used for unsupervised pre-training of deep neural network.

# Component of Architechture of Autoencoders

- Encoder -:
    - It compresses the input into a latent space represention (the code).
    - the encoder layer encodes the input image as a compressed representation in a reduced dimension.
    - distorted verson of original image

- Code -:
    - this is the compressed input which is fed to the decoder for reconstructing the original input later.

- Decoder -:
    - It decodes the encoded output.
    - back to original input.
    - lossy reconstruction.
    - the goal is to get an output as identical as was the input.
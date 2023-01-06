# Regularised Autoencoder

- regularised AE provide the ability to choose the code dimension and the capacity of the encoder and decoder based on the complexity of distribution to be modelled.

- rather than limiting the model capacity by keeping the encoder and decoder shallow and the code size small, RAE use a loss finction that encourages the model to have other properties besides the ability to copy it's input to it's output.

- these other properties include sparcity of representation, smallness of the derivative of representation, and robustness to noise or to missing input.

- A RAE can be non-linear and overcomplete but still learn something useful about the data distribution, even if the model capacity is great enough to learn identity function

- Sparce and denoising are RAE.

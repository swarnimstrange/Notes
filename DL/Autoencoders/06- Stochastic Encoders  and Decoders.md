# Stochastic Autoencoder

- Both encoder and decoder are not simple functions but instead involve some noise injection.

- the output can be seen as sampled from a distribution, P( h|x ) for the encoder and P( x|h ) for the decoder
    - h is code and x is input/target

- The output variable are treated as being conditionally independent given h so that this probability distribution is inexpensive to evaluate, but some techniques, such as mixture density outputs, allow flexible modelling of outputs with correlation.
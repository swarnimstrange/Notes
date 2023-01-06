# Learning Representation of objects in Images by Predicting Reconstruction

- We train autoencoders as we would do for a regular autoencoder but drop the decoding part so as to only get codings that are the representations.

- After training, we discard all layers following the middle one. we are then left with a neural network that transforms images with millions of pixels into a small number of values that represent the object in those images.

- factors that makes representation good
  - Smoothness.
  - Multiple explanatory features.
  - shared factors across tasks.
  - semi-supervised learning.
  - Simplicity of factor dependencies
  - sparcity

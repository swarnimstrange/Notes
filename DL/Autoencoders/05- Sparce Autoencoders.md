# Sparce Autoencoders

- One of the constraints that often leads to good feature extraction is sparcity.

- Using sparsity, you can push the AE to reduce the number of active neuros in the coding layer.

- For example -:
    - it may be pushed to have on average only 5% significantly active neurons in the coding layer.

    - this forces AE to represent each input as a combination of small number of activations.

    - As a result, each neuron in the coding layer typically ends up representing a useful feature.
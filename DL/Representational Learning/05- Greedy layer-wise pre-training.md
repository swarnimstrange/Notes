# Greedy layer-wise pre-training

- Greedy layer-wise pre-training is also called as unsupervised pre-training.

- this procedure is an established example of how a representation learned in one task can be sometimes useful for another task.

- it relies on a single-layer representation learning algorithm such as an RBM (Reestricted Boltzmann machine), a single autoencoder etc.

- Each layer is pretrained using unsupervised learning, taking the output of the previous layer and producing as output a new representation of the data.

- reason for name -:

  - it is called greedy because it is greedy algorithm, means it optimizes each piece of the solution independently, one piece at a time, rather than jointly optimising all peices.

  - it is called layer-wise because these independent pieces are the layers of the network.

  - it is called unsupervised because each layer is trained with an unsupervised representation algorithm.

  - it is called pre-training because it is supposed to be only a first step before a joint training algorithm is applied to fine-tune all the layers together.

- GL-WUPT can also be used as initialisation for other unsupervised learning algorithms, such as deep encoders and probabilistic models with many layers of latent variables.

# Advantages

- more effective when the initial representation is poor.
- helpful when no of labelled example is very small.
- useful when function to be learned is extremely complicated.
- can yield substantial inprovement in test error of classification task

# Disadvantages

- requires two seperate phases
- each phase require its own hyperparameters
- does not offer a clear way to adjust the strength of the regularisation arising from the unsupervised stage.
- unsupervised pre-training is largely abandoned.

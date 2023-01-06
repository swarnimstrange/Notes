# Contactive AE

- the objective of a contractive AE is to have a robust learned representation which is less sensitive to small variation in the data. 

- Robustness of the representation for the data is done by applying a penalty term to the loss function.

- Contractive AE is another regularisation technique just like sparce and denoising AEs

- Contractive AE is a better choice than denoising to learn useful feature extraction.

- the model learns an encoding in which similar inputs have similar encodings.

- Hence, you are forcing the model to learn how to contract a neighbourhood of inputs into a smaller neighbourhood of outputs.

- denoising SE make the reconstruction function resist small but finite-sized changes in the input, while contractive AE make the feature extraction function resist small changes in the input
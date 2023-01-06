# Denoising AE

- You can force the autoencoder to learn useful features by adding noise to it's input and then training it to recover the original noise-free inputs.

- this prevents the AE from trivially copying its inputs to outputs and so it ends up having to find patters in the data.

- So, we are forcing the autoencoder to subtract the noice and produce the underlying meaningful data.
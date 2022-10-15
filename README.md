## VAE

**A variational autoencoder can be defined as an autoencoder whose training is regularized to avoid overfitting and ensure that the latent space has good properties that enable a generative process.
We proceed to modify the encoding-decoding process slightly: **instead of encoding an input as a single point, we encode it as a distribution over the latent space.

The reason why input is encoded as a distribution with some variance instead of a single point is that it makes it possible to express very naturally the latent space regularization.

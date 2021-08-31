# deep-convolutional-generative-adversarial-network

A DCGAN is simply a GAN that uses a convolutional neural network as the discriminator, and a network composed of transposed convolutions as the generator. We will be using this to generate new emojis from a dataset of emojis.

We implement the following to improve output.
*   Reduced learning rate
*   Normalized inputs
*   Applied smoothing to real and fake labels
*   Used normally distributed sample noise
*   Used custom kernel initialization
*   Added batch normalization and leaky relu at the output of each convolutional layer in discriminator

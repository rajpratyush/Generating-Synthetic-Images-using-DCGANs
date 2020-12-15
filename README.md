# Generating-Synthetic-Images-using-DCGANs

## Objective: 

To build and train a Deep Convolutional GAN (DCGAN) with Keras to generate images of fashionable clothes.  Here I have used the Keras Sequential API with Tensorflow 2 as the backend.

In the GAN setup,  I wanted to sample from a complex, high-dimensional training distribution of the Fashion MNIST images. However, there was no direct way to sample from this distribution. The solution was to sample from a simpler distribution, such as Gaussian noise. I wanted the model to use the power of neural networks to learn a transformation from the simple distribution directly to the training distribution that I care about. The GAN consists of two adversarial players: a discriminator and a generator. We’re going to train the two players jointly in a minimax game theoretic formulation.

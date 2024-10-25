# GAN-MNIST-Implementation
This project is an implementaton of Generative Adversarial Network (GAN) for The MNIST Dataset which consists 60,000 training examples and 10,000 testing set of handwritten digits. Each image is grayscale and has a resolution of 28x28 pixels. The task will be to train a GAN such that it can generate realistic-looking handwritten digits similar in appearance to the ones present in training data.
There are two major elements that make up GANs:
 * Generator: It learns to generate novel looking images that appears as handwritten digits in real world.
 * Discriminator: Learns to distinguish whether the image generated is real or fake.
Adversarial training wherein generator and discriminator learn to be good since each adversarially challenges the other helps in producing high quality digits.
# Features
* Created a GAN architecture from scratch in PyTorch.
* The generator with a very straightforward multilayer architecture to generate 28x28 resized digit images
* Discriminator for deciding whether the image is real or fake.
* Pooling: adversarial trained cross entropy loss
* Evaluation metrics: Visually inspecting the generated digits.
* Learning rate, Batch Size and Number of epochs are hyperparameters that can be configured

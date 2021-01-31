## Generate handwritten digits using GAN

In this project we will train a model which will eventually learn to write handwritten digits.

INPUT: we will use torchvision dataset that is built-in in PyTorch
![input](https://i.ibb.co/2Sd6RSk/input.png "input")

OUTPUT: generated data
![output](https://i.ibb.co/qxVFwmx/Output.png "output")

### Tools Used

- Python
- PyTorch
- Torchvision
- Matplotlib


### Concepts covered

- GAN (Generative Adversarial Networks)
- Generator
- Discriminator
- Leaky ReLU Activation Function

### Details

We used PyToirch built-in torchvision module as a data source which called MNIST handwritten digit. We implemented a GAN (Generative Adversarial Networks) model that implemented the Leaky ReLU activation function. We trained the Discriminator and Generator Neural Networks. The purpose of Generator is to create fake images and Discriminator to identify between the fake and real images. They worked together to finally generate some very realistic fake images which are hard to differentiate.

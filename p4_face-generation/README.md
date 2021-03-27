# Udacity Deep Learning Nanodegree - Project 4: Face Generation
Human face generation with DC-GAN architecture and Celebra dataset. Project 4 of Udacity's Deep Learning Nanodegree

Original repository: https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-face-generation


### Introduction
In this project, you'll define and train a DCGAN on a dataset of faces. Your goal is to get a generator network to generate *new* images of faces that look as realistic as possible!


### Results
[Discriminator and Generator Loss](loss.png)
Quickly, the Discriminator learns to tell which of the images given to it are fakes.  Over time the Generator learns to fool the Discriminator better and better before reaching an inflection point from which it stagnates and begins regressing.  It has possibly found an equilibrium by the end, but it would take more training timesteps to be certain.

[Example Generated Faces](generated_faces.png)
The Generator has learned a general representation of faces, with most being within a usual shape range; having what is recognizable as two eyes, a mouth, and nose; and having mostly uniform skintones.
Clearly is not capable enough to make any that humans would be fooled by, however.  This is most likely due to limitations of the DC GAN architecture -- there have been many new architectures and loss functions proposed since the original publication.

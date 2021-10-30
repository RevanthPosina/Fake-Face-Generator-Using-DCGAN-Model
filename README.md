# Fake-Face-Generator-Using-DCGAN-Model

GANs, in general, can be defined as a generative model that lets us generate a whole image in parallel. Along with several other kinds of generative models, GANs uses a differentiable function represented by a neural network as a Generator Network.

:globe_with_meridians:	CelebA resized dataset url is attached in the repository ( in celebA_url.txt )

The end goal of the Generator is to learn a distribution similar to the distribution of the training dataset to sample out realistic images. To be able to do so, the Generator Network needs to be trained. The training process of the GANs is very different, compared to other generative models( Most generative models are trained by adjusting the parameters to maximize the probability of Generator to generate realistic samples.

:artificial_satellite:	This models uses a second network to train the Generator, called Discriminator Network.

Built a Generator Network Model to generate new images of fake humans faces as realistic as possible.
Each transpose convolution layer is followed by Batch Normalization, Discriminator and Generator models are used to remove real and fake loss.
Training losses are recorded and plotted for Discriminator and Generator after each epoch

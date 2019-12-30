# Generative-Adversarial-Network

Generative adversarial networks (GANs) are one of the hottest topics in deep learning. From a high level, GANs are composed of two components, a generator and a discriminator. The discriminator has the task of determining whether a given image looks natural (ie, is an image from the dataset) or looks like it has been artificially created. The task of the generator is to create natural looking images that are similar to the original data distribution, images that look natural enough to fool the discriminator network.

The analogy used in the paper is that the generative model is like “a team of counterfeiters, trying to produce and use fake currency” while the discriminative model is like “the police, trying to detect the counterfeit currency”. The generator is trying to fool the discriminator while the discriminator is trying to not get fooled by the generator.

As the models train through alternating optimization, both methods are improved until a point where the “counterfeits are indistinguishable from the genuine articles”.

The tutorial is written in Python, with the Tensorflow library, so it would be good to have familiarity with Tensorflow before taking a look at this tutorial.

# More GAN Resources
The original paper written by Ian Goodfellow in 2014.
Ian Godfellow's keynote on GANs (More of a technical video)
Brandon Amos's image completion blog post
Blog post on using GANs in video games.
Andrej Karpathy's blog post with GAN visualizations.

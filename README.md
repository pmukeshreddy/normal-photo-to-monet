# normal-photo-to-monet

I have done this project using cyclegan

A deep learning model called CycleGAN is employed for image-to-image translation.
Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks was first discussed in a study published in 2017 by Jun-Yan Zhu, Taesung Park, Phillip Isola, and Alexei A. Efros.

CycleGAN's fundamental goal is to learn a mapping between two distinct picture domains—let's say, horses and zebras—without needing to train on pairs of examples from each domain. Instead, CycleGAN trains two generative adversarial networks (GANs) that cooperate to translate images from one domain to the other and back again using unpaired photos from the two domains.

The discriminator and generator are the two GANs. While the discriminator aims to differentiate between different picture domains, the generator learns to change an image between them.

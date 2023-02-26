# implmenting-srgan-with-pytorch

In this project, you will build super-resolution GAN (SRGAN), a GAN that enhances the resolution of images by 4x, to enrich the resolution of the images that are available from STL-10 dataset. The STL-10 dataset is an image recognition dataset for developing unsupervised feature learning, deep learning, self-taught learning algorithms. It is inspired by the CIFAR-10 dataset but with some modifications. In particular, each class has fewer labeled training examples than in CIFAR-10, but a very large set of unlabeled examples is provided to learn image models prior to supervised training. The primary challenge is to make use of the unlabeled data (which comes from a similar but different distribution from the labeled data) to build a useful prior.

We will first train a super-resolution residual network (SRResNet) with standard pixel-wise loss that achieves state-of-the-art metrics. Then insert this as the generator in the SRGAN framework, which is trained with a combination of pixel-wise, perceptual, and adversarial losses.

For notebook with populated outputs, please refer to Colab - https://colab.research.google.com/drive/18JMq53aDoaQ13CQZ6Bg3FO1shgkeN8XK?usp=sharing
(ran with premius GPU)

# pytorch-MNIST-Anime-Gans

Pytorch implementation of Generative Adversarial Networks (GAN) [1] and Deep Convolutional Generative Adversarial Networks (DCGAN)  for MNIST and Anime faces datasets.

    If you want to train using cropped CelebA dataset, you have to change isCrop = False to isCrop = True.

    you can download
        MNIST dataset: http://yann.lecun.com/exdb/mnist/
        CelebA dataset: http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html

    pytorch_CelebA_DCGAN.py requires 64 x 64 size image, so you have to resize CelebA dataset (celebA_data_preprocess.py).

    pytorch_CelebA_DCGAN.py added learning rate decay code.


### GAN-Art-Creating-Kaggle-Project
GAN Art Creating Kaggle Project Jupyter notebook


# Introduction

The objective of this project is to leverage the power of GANs to generate realistic Monet-style paintings from ordinary photographs. GANs are a type of deep learning model that consists of a generator and a discriminator. The generator learns to generate new images that resemble the target domain (Monet paintings), while the discriminator tries to distinguish between real and generated images. Through adversarial training, the generator improves over time and learns to produce high-quality Monet-style paintings.

This repository contains a notebook that demonstrates the conversion of photos into Monet-style paintings and vice-versa using a Cycle Generative Adversarial Network (cGAN). This project was inspired by the Kaggle competition on GAN image synthesis.

# Dataset

The dataset used in this project is the Kaggle Monet paintings dataset, which consists of a collection of Monet-style paintings and photographies. The dataset contains a total of 300 Monet paintings and 7000+ photos (from which only 2500 were used to reduce the training time per epoch). Each image is of size 256 x 256 pixels.

# Facial-Recognition-App-with-Tensorflow-and-Kivy
building a model using Deep Learning with TensorFlow which replicates what is shown in the paper titled Siamese Neural Networks for One-shot Image Recognition. Once that's all trained you'll be able to integrate it into a Kivy app and actually authenticate!

### Siamese networks with Keras, TensorFlow, and Deep Learning

In the first part of this tutorial, we will discuss siamese networks, how they work, and why you may want to use them in your own deep learning applications.

From there, you’ll learn how to configure your development environment such that you can follow along with this tutorial and learn how to train your own siamese networks.

We’ll then review our project directory structure and implement a configuration file, followed by three helper functions:

      - A method used to generate image pairs such that we can train our siamese network
      - A custom CNN layer to compute Euclidean distances between vectors inside of the network
      - A utility used to plot the siamese network training history to disk

Given our helper utilities, we’ll implement our training script used to load the MNIST dataset from disk and train a siamese network on the data.

We’ll wrap up this tutorial with a discussion of our results.

# What are siamese networks and how do they work?

![keras_siamese_networks_process](https://user-images.githubusercontent.com/19749662/220167334-de95318f-be8a-4b3a-8bbb-caa62308f9b2.png)

https://pyimagesearch.com/2020/11/30/siamese-networks-with-keras-tensorflow-and-deep-learning/

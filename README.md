#  AI-Based Photo Colorization using Convolutional Autoencoders

An advanced Deep Learning and Computer Vision project that automatically converts grayscale landscape images into realistic RGB colorized images using Convolutional Autoencoders built with TensorFlow, OpenCV, and Keras.

##  Overview

This project implements an AI-powered image colorization system using a Convolutional Autoencoder architecture.

The model learns how to reconstruct RGB color channels from grayscale landscape images by training on paired grayscale and color datasets.

The complete workflow includes:

- Dataset preprocessing
- Grayscale and RGB image pairing
- Image normalization and resizing
- Encoder-decoder based feature learning
- Deep learning model training
- Prediction on unseen grayscale images
- Visualization of generated colorized outputs

The project demonstrates practical applications of:

- Deep Learning
- Computer Vision
- Image Reconstruction
- Convolutional Neural Networks (CNNs)
- Autoencoders using TensorFlow/Keras


## 🖼️ Demo Results

The trained Convolutional Autoencoder successfully predicts realistic RGB outputs from grayscale landscape images.

### Grayscale to Colorized Transformation

<p align="center">
  <img src="images/grayscale_1.png" width="32%">
  
  &nbsp;&nbsp;&nbsp; ➜ &nbsp;&nbsp;&nbsp;
  
  <img src="images/colorized_output1.png" width="32%">
</p>

### Result Explanation

- Left Image → Original grayscale landscape image
- Right Image → AI-generated colorized output

The model learns textures, spatial structures, and semantic color patterns during training to reconstruct realistic RGB outputs from grayscale inputs.

The system is trained using grayscale input images and corresponding RGB target images to learn semantic color representations automatically.
 

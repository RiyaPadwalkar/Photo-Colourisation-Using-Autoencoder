#  AI-Based Photo Colorization using Convolutional Autoencoders

An advanced Deep Learning and Computer Vision project that automatically converts grayscale landscape images into realistic RGB colorized images using Convolutional Autoencoders built with TensorFlow, OpenCV, and Keras.

## 📌 Overview

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


## 📸 Demo Results

The trained Convolutional Autoencoder successfully predicts realistic RGB outputs from grayscale landscape images.

### Grayscale to Colorized Transformation

<table align="center">
<tr>
<td align="center">
<img src="test/input/img101_grayscale.jpg" width="250"/>
</td>

<td align="center" width="80">
<h1>➡️</h1>
</td>

<td align="center">
<img src="test/output/img101_color.jpg" width="250"/>
</td>
</tr>

<tr>
<td align="center"><b>Grayscale Input</b></td>
<td></td>
<td align="center"><b>Colorized Output</b></td>
</tr>
</table>

#### Result Explanation

- Left Image → Original grayscale landscape image
- Right Image → AI-generated colorized output

The model learns textures, spatial structures, and semantic color patterns during training to reconstruct realistic RGB outputs from grayscale inputs.

The system is trained using grayscale input images and corresponding RGB target images to learn semantic color representations automatically.

 ## 🔄 Workflow Diagram

The project follows a complete Deep Learning-based image colorization workflow.

<p align="center">
  <img src="workflow.png" width="35%">
</p>

###  Workflow Steps

1. Collect grayscale and RGB landscape image datasets
2. Resize all images to 120×120 dimensions
3. Normalize pixel values between 0 and 1
4. Create paired grayscale-RGB datasets
5. Train the Convolutional Autoencoder
6. Generate predictions on unseen grayscale images
7. Visualize generated RGB outputs

## 🕸️ Architecture Diagram

The project uses a Convolutional Autoencoder architecture consisting of Encoder and Decoder networks.

<p align="center">
  <img src="architecture.png" width="35%">
</p>

### Encoder Network

The encoder extracts important image features using convolutional layers.

#### Encoder Layers

- Conv2D → 64 filters
- Conv2D → 128 filters with stride=2
- Conv2D → 256 filters with stride=2

The encoder compresses grayscale image information into latent feature representations.

---

### Decoder Network

The decoder reconstructs RGB channels from compressed latent representations.

#### Decoder Layers

- Conv2DTranspose → 128 filters
- Conv2DTranspose → 64 filters
- Conv2D Output Layer → 3 RGB channels

---

### Activation Functions

- ReLU → Hidden layers
- Sigmoid → Output layer

---

### Optimizer & Loss Function

- Optimizer → Adam
- Loss Function → Mean Squared Error (MSE)

## ⚡ Future Improvements

The project can be enhanced further using advanced Computer Vision and Deep Learning techniques.

### Planned Improvements

- Train on larger and more diverse datasets
- Improve image resolution support
- Implement U-Net architecture
- Integrate GAN-based image colorization
- Add SSIM and PSNR evaluation metrics
- Improve edge and texture reconstruction
- Deploy as a Streamlit web application
- Build real-time image colorization system
- Add support for historical photograph restoration

---

### Research Extensions

Future versions may explore:

- Generative Adversarial Networks (GANs)
- Perceptual Loss Functions
- Transformer-based Vision Models
- Attention Mechanisms for improved color prediction

## 👨‍💻 Author

Developed by Riya Nitin Padwalkar

### About Me

- Computer Engineering Student
- AI & Machine Learning Developer
- Computer Vision Developer
- Deep Learning Practitioner

---

### Technical Skills

- Python
- TensorFlow/Keras
- OpenCV
- Deep Learning
- Computer Vision
- Image Processing

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| TensorFlow/Keras | Deep Learning |
| OpenCV | Image Processing |
| NumPy | Numerical Computation |
| Matplotlib | Visualization |
| Google Colab | GPU Training Environment |


### Connect With Me

- GitHub → https://github.com/RiyaPadwalkar

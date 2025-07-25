# Handwritten Digit Generation with DCGAN

This project implements a **Deep Convolutional Generative Adversarial Network (DCGAN)** to generate realistic handwritten digit images, using the MNIST dataset. The model is trained entirely in TensorFlow and Keras inside a Jupyter Notebook.

##Overview

Generative Adversarial Networks (GANs) are a powerful type of neural network used for unsupervised learning. This project focuses on using a DCGAN architecture to synthesize new handwritten digits, mimicking the style of the MNIST dataset.

The DCGAN consists of two primary models:
- **Generator**: Learns to create images from random noise.
- **Discriminator**: Learns to distinguish between real MNIST images and fake images generated by the generator.

These two models are trained simultaneously in a competitive setting (a min-max game), gradually improving the quality of generated images.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/ara2105/Handwritten-Digit-Generator---DCGAN.git
   cd handwritten-digit-dcgan
   ```
2. Install dependencies (you may use a virtual environment):
```bash
pip install -r requirements.txt
```
3. Run the Jupyter notebook:
```bash
jupyter notebook Handwritten_digit_images_DCGAN.ipynb
```





# Showcase---Hybrid-Image-Encryption-System-Using-Convolutional-Autoencoder-and-Chaotic-Cryptography


# Deep Learning Image Compression and Cryptographic Encryption Pipeline

## Overview
This project presents a hybrid approach to secure image transmission. It combines deep learning-based image compression with advanced cryptographic encryption to ensure that visual data is both lightweight and highly secure against corruption and attacks.

## Features
- **Autoencoder Compression:** Utilizes Convolutional Autoencoders in PyTorch and TensorFlow to compress images into a lower-dimensional latent space.
- **Cryptographic Encryption:** Secures the compressed latent representations using AES (Advanced Encryption Standard).
- **Chaos-Based Scrambling:** Applies dynamic image scrambling methods including Arnold's Cat Map, Logistic Map, and Henon Map for added security.
- **Performance Metrics:** Benchmarks image reconstruction quality (MSE, PSNR, SSIM) and encryption strength (NPCR, UACI, Information Entropy, Key Sensitivity).

## Repository Structure
- `PyTorch_Autoencoder_AES.ipynb`: The main PyTorch implementation featuring the complete compression, encryption, and evaluation pipeline.
- `TensorFlow_Version.ipynb`: An alternative implementation using TensorFlow/Keras.
- `data/`: Contains standard test images (Lena, Baboon, Peppers) used for benchmarking.

## Technologies Used
- **Deep Learning:** PyTorch, TensorFlow
- **Cryptography:** PyCryptodome (AES)
- **Computer Vision & Math:** OpenCV, Scikit-Image, NumPy, SciPy

## How to Run
1. Clone the repository and install the required dependencies (`torch`, `tensorflow`, `opencv-python`, `pycryptodome`, `scikit-image`).
2. Open the Jupyter Notebooks.
3. Ensure the test images from the `data/` folder are correctly referenced in the code.
4. Run the cells sequentially to train the autoencoder, encrypt the latent space, and view the evaluation metrics.

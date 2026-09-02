This revised version incorporates the specific architectural details and metrics from your resume, cleans up the formatting, and adds the crucial privacy disclaimer for engineering reviewers.

---

# Hybrid Image Encryption System (CNN/UNET Autoencoders & Chaotic Cryptography)

> **Note:** The source code for this project is currently hosted in a private repository due to confidentiality constraints. This repository serves as an architectural and technical overview of the system.

## Overview

This project presents a highly robust cascade architecture for secure image transmission. By combining deep learning-based compression with advanced cryptographic encryption, the system ensures that visual data is both extremely lightweight and highly secure against statistical and differential attacks.

## Core Performance Metrics

* **Compression:** Achieved a massive 1024x compression ratio.


* **Differential Security:** Reached an NPCR (Number of Pixels Change Rate) of 99.60%, demonstrating exceptional resistance to differential attacks.


* **Statistical Security:** Achieved a near-ideal Information Entropy of 7.998.



## System Architecture

1. **Deep Learning Compression:** Utilizes Convolutional Autoencoders and UNET architectures developed in PyTorch and TensorFlow to compress high-resolution images into a lower-dimensional latent space.


2. **AES Cryptography:** Secures the compressed latent representations using the Advanced Encryption Standard (AES) to establish a strong baseline layer of security.


3. **Selectable Chaotic Scrambling:** Applies a dynamic, multi-algorithmic scrambling module to the encrypted data to eliminate data patterns. Methods include Zig-Zag, Arnold-Affine, Logistic Map, and Henon Map.



## Repository Structure

* `PyTorch_Autoencoder_AES.ipynb`: The main PyTorch implementation featuring the complete compression, encryption, and evaluation pipeline.
* `TensorFlow_Version.ipynb`: An alternative implementation utilizing TensorFlow/Keras.
* `data/`: Contains standard test images (Lena, Baboon, Peppers) used for benchmarking.

## Technologies Used

* **Deep Learning:** PyTorch, TensorFlow/Keras
* **Cryptography:** PyCryptodome (AES)
* **Computer Vision & Math:** OpenCV, Scikit-Image, NumPy, SciPy

# 🌀 DeblurGAN: Image Blur Detection and Removal using GANs

DeblurGAN is a deep learning project aimed at restoring clarity to blurred images using Generative Adversarial Networks (GANs). The model is trained to take a blurred image as input and generate a deblurred version that closely resembles the original sharp image.

---

## 📌 Overview

In many real-world scenarios such as photography, surveillance, and medical imaging, motion blur or defocus blur can severely affect image quality. DeblurGAN is designed to address this issue using a GAN-based architecture trained on paired blurred and sharp images.

---

## 🎯 Objectives

- Detect and remove motion or defocus blur in images.
- Generate high-resolution, deblurred images using a GAN architecture.
- Evaluate model performance using PSNR, SSIM, and visual clarity.

---

## 🧠 Model Architecture

DeblurGAN follows a GAN-based framework consisting of:

- **Generator**: A U-Net-based architecture to generate deblurred images.
- **Discriminator**: A convolutional neural network that distinguishes between real (sharp) and generated (deblurred) images.
- **Loss Functions**:
  - Adversarial Loss (GAN)
  - Content Loss (L1 or Perceptual)
  - Optional: Edge Loss or Total Variation Loss

---

# Enhancing Perceptual Quality of Images using Deep Residual U-Net and PatchGAN Discriminator

Project Overview
This repository contains the code for the research project, "Enhancing Perceptual Quality of Images using Deep Residual U-Net and PatchGAN Discriminator," which applies a deep residual U-Net with PatchGAN for high-quality image enhancement. Key features include:

•Perceptual Loss using a pre-trained VGG16 for improved colour, clarity, and high-level feature retention.

•Generator and Discriminator setup inspired by GANs for structural and perceptual quality enhancement.

Abstract: This paper presents a novel approach for perceptually-aware image enhancement utilizing a deep residual U-Net generator combined with a Patch-based Generative Adversarial Network (PatchGAN) discriminator. Our method incorporates a perceptual loss function based on a pre-trained VGG16 network, ensuring that enhanced images exhibit improved color sharpness, clarity, and retention of critical high-level features. Extensive experiments demonstrate significant improvements in structural similarity, achieving an average Structural Similarity Index (SSIM) of 0.9270 and a Feature Similarity Index (FSIM) of 0.9998. These results indicate both perceptual and structural enhancement, while the model efficiently generates high-quality images with minimal training. Our method consistently outperforms conventional approaches in visual appeal and computational efficiency, making it relevant for real-world applications such as radiology, self-driving vehicles, and low-light photography.

Dataset- DIV2K dataset has been used, sourced from - https://www.kaggle.com/datasets/joe1995/div2k-dataset.
This link was used to download the dataset on which the model was trained and tested.

In this page, the first file- enhancing_images.ipynb contrains the code for the model trained on 10 epochs.

While the second file - image_proj.ipynb contains the code trained on 25 and 55 epcohs. The results shown are from the model that was trained on 55 epochs.

The code can be run by opening any of the files and then opening that using Google colab. 


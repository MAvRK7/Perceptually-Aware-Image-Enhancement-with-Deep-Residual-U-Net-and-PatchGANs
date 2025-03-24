# Enhancing Perceptual Quality of Images using Deep Residual U-Net and PatchGAN Discriminator

Project Overview
This repository contains the code for the research project, "Enhancing Perceptual Quality of Images using Deep Residual U-Net and PatchGAN Discriminator," which applies a deep residual U-Net with PatchGAN for high-quality image enhancement. Key features include:

•Perceptual Loss using a pre-trained VGG16 for improved colour, clarity, and high-level feature retention.

•Generator and Discriminator setup inspired by GANs for structural and perceptual quality enhancement.

Abstract: Developed a novel image enhancement model that combines a U-Net-like generator with residual connections
and PatchGAN as a discriminator, focusing on improving both technical and visual features. This approach
achieved excellent results, with an average SSIM of 0.9270 and FSIM of 0.9998, producing high-quality,
visually appealing outputs. 

Dataset- DIV2K dataset has been used, sourced from - https://www.kaggle.com/datasets/joe1995/div2k-dataset.
This link was used to download the dataset on which the model was trained and tested.

In this page, the first file- enhancing_images.ipynb contrains the code for the model trained on 10 epochs.

While the second file - image_proj.ipynb contains the code trained on 25 and 55 epcohs. The results shown are from the model that was trained on 55 epochs.

The code can be run by opening any of the files and then opening that using Google colab. 

<img width="482" alt="image" src="https://github.com/user-attachments/assets/292ae452-6d22-4c26-8caa-127cea5a8070" />

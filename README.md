# Enhancing Perceptual Quality of Images using Deep Residual U-Net and PatchGAN Discriminator

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)]() [![Framework](https://img.shields.io/badge/Framework-TensorFlow%20%7C%20Keras-orange)]() [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)]()

## 🚀 Overview
This repository contains the code for the research project:  
**"Enhancing Perceptual Quality of Images using Deep Residual U-Net and PatchGAN Discriminator"**  

We propose a **U-Net-like generator with residual connections** and a **PatchGAN discriminator**, optimised with **perceptual loss (VGG16)** to enhance both structural fidelity and perceptual quality of images.

---

## 🔑 Key Features
- **Residual U-Net Generator** – captures fine details and global context.  
- **PatchGAN Discriminator** – enforces local structural realism.  
- **Perceptual Loss (VGG16)** – preserves colour, clarity, and high-level features.  
- **Quantitative Metrics:**  
  - SSIM: **0.9270**  
  - FSIM: **0.9998**

---

## 📊 Results Summary
| Model Variant (Epochs) | SSIM   | FSIM   |
|-------------------------|--------|--------|
| 10 epochs              | 0.8912 | 0.9965 |
| 25 epochs              | 0.9134 | 0.9982 |
| 55 epochs (final)      | **0.9270** | **0.9998** |

👉 Final model (55 epochs) produced the best perceptual and structural quality.

<img width="948" height="484" alt="image" src="https://github.com/user-attachments/assets/03ddc6e8-393d-41fd-b209-d7c36e62309d" />


---

## 🛠️ Dataset
- **DIV2K Dataset** (high-quality image dataset)  
- Source: [Kaggle – DIV2K Dataset](https://www.kaggle.com/datasets/joe1995/div2k-dataset)

---

## ⚡ Quick Start
1. Clone the repo:
   ```bash
   git clone https://github.com/MAvRK7/Perceptually-Aware-Image-Enhancement-with-Deep-Residual-U-Net-and-PatchGANs.git
   cd Perceptually-Aware-Image-Enhancement-with-Deep-Residual-U-Net-and-PatchGANs


In this page, the first file- enhancing_images.ipynb contrains the code for the model trained on 10 epochs.

While the second file - image_proj.ipynb contains the code trained on 25 and 55 epcohs. The results shown are from the model that was trained on 55 epochs.

The code can be run by opening any of the files.

## Visualization

<img width="482" alt="image" src="https://github.com/user-attachments/assets/292ae452-6d22-4c26-8caa-127cea5a8070" />

## 🔍 Why This Matters

- Low-light photography – improves clarity and detail retention.
- Medical imaging – enhances diagnostic quality while preserving structure.
- Autonomous vehicles – improves perception in adverse conditions.

## Before and After Comparison

<img width="425" height="223" alt="image" src="https://github.com/user-attachments/assets/5d81a08d-a331-4106-aaa0-ad18fe7b6806" />

<img width="847" height="336" alt="image" src="https://github.com/user-attachments/assets/f10be05d-8748-4a8a-864f-581fd019cd03" />

## 🤝 Contributing
Contributions are welcome! Please open an issue or submit a pull request.

## 📚 Citation
If you use this work, please cite:


@inproceedings{raghav2025perceptual,
  title={Enhancing Perceptual Quality of Images using Deep Residual U-Net and PatchGAN Discriminator},
  author={Raghav, Satvik and Narkedimilli, S. and Ayitapu, P. and Karthikeya, R. and Lalitha, S.},
  booktitle={3rd Int. Conf. on New Trends in Computing Sciences (ICTCS)},
  year={2025}
}

## 📬 Contact
For queries: satvikraghav007@gmail.com



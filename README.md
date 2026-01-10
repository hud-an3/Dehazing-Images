

# Image Dehazing Using Deep Learning

## 📌 Overview

This project focuses on **single-image dehazing** using deep learning techniques. The goal is to enhance image visibility by removing haze while preserving structural and color information. The model is trained and evaluated on multiple benchmark dehazing datasets to ensure robustness and generalization across indoor and outdoor scenes.

The implementation uses a **CNN-based architecture with residual learning**, enabling effective feature extraction and restoration of clear images from hazy inputs.

---

## 📂 Datasets Used

The model is trained and evaluated using the following widely used dehazing datasets:

* **I-HAZE** – Indoor hazy scenes with corresponding ground truth
* **NH-HAZE** – Non-homogeneous haze dataset
* **NYU-V2** – Indoor RGB-D dataset adapted for synthetic haze generation
* **O-HAZE** – Outdoor real hazy images with ground truth
* **RESIDE** – Large-scale benchmark dataset for image dehazing

These datasets help the model generalize across **indoor, outdoor, homogeneous, and non-homogeneous haze conditions**.

---

## 🧠 Model Architecture

* Convolutional Neural Network (CNN)
* Residual blocks for stable training
* Instance normalization
* ReLU activation
* End-to-end image-to-image learning

The network learns a **residual haze component**, which is subtracted from the input to generate the dehazed output.

---

## 🛠️ Tech Stack

### **Programming & Frameworks**

* **Python**
* **PyTorch**
* **Torchvision**

### **Image Processing**

* **PIL**
* **OpenCV**
* **NumPy**

### **Training & Evaluation**

* **LPIPS** (Perceptual similarity)
* **PSNR**
* **SSIM**

### **Visualization**

* **Matplotlib**

---

## 📊 Results

The model demonstrates:

* Improved visibility
* Reduced haze artifacts
* Better perceptual quality across datasets

Quantitative evaluation is performed using **PSNR, SSIM, and LPIPS**.



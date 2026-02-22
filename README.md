# 🔍 Crack Detection System using Computer Vision

A robust Computer Vision solution designed to identify structural cracks in real-time via webcam and through batch image processing. This project is built to assist in automated infrastructure health monitoring.

---

## 📑 Project Overview

Manual inspection of structures is time-consuming and prone to human error. This project leverages **Image Processing** and **Deep Learning** to automate the detection of cracks in concrete, pavement, and metallic surfaces.

### Core Components:
1.  **Real-Time Detection (`scripts/crack_detection_webcam.py`):** Uses a live webcam feed to detect and highlight cracks on the fly.
2.  **Batch Processing (`notebooks/crack_detection_images.ipynb`):** A comprehensive Jupyter Notebook for analyzing single images, batches, or entire datasets with detailed performance metrics.

---

## 🏗 System Architecture & Flow

The model follows a sequential pipeline from pre-processing to final segmentation/classification.



### Process Flow:
1.  **Input:** Image acquisition (Webcam/Disk).
2.  **Pre-processing:** Grayscale conversion, Noise reduction (Gaussian Blur), and Normalization.
3.  **Feature Extraction:** Detection of edges and textures characteristic of cracks.
4.  **Inference:** Model prediction.
5.  **Output:** Visual bounding boxes or masks overlayed on the original frame.



---

## 🛠 Tech Stack

* **Language:** Python 3.x
* **Libraries:** OpenCV, TensorFlow/Keras (or PyTorch), NumPy, Matplotlib
* **Environment:** Jupyter Notebook / VS Code

---

## 🚀 Getting Started

### 1. Prerequisites
Ensure you have Python installed. It is recommended to use a virtual environment:
```powershell
python -m venv venv
.\venv\Scripts\activate

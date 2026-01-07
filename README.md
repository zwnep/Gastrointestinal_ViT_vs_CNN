# Gastrointestinal_ViT_vs_CNN
This is a deep learning project that aims to compare the performance of Convolutional Neural Networks (CNN) and Vision Transformer (ViT) architectures for the detection of diseases of the stomach and intestinal (gastrointestinal) system.


# Gastrointestinal Disease Detection: CNN vs. ViT

This project aims to detect and classify gastrointestinal tract diseases using Deep Learning techniques. It focuses on comparing the performance of traditional **Convolutional Neural Networks (CNN)** against modern **Vision Transformers (ViT)** on medical imaging data.

## 📌 Project Overview
Gastrointestinal bleeding and other conditions like polyps or ulcerative colitis require accurate diagnosis. This repository implements a machine learning pipeline to classify endoscopic images into four distinct categories, evaluating whether Transformer-based architectures offer advantages over standard CNNs in this domain.

## 📂 Dataset
The dataset consists of endoscopic images categorized into **4 classes**:
* **0_normal**: Healthy gastrointestinal tissue.
* **1_ulcerative_colitis**: Images indicating ulcerative colitis.
* **2_polyps**: Presence of polyps.
* **3_esophagitis**: Inflammation of the esophagus.

## ⚙️ Features
* **Data Preprocessing**: Automated loading, resizing (72x72px), and normalization of images.
* **Exploratory Data Analysis (EDA)**: Visualization of class distributions across training, validation, and test sets to ensure data integrity.
* **Model Comparison**: Infrastructure to train and compare CNN and ViT architectures (as referenced in the notebook).
* **Visualization**: Sample image grids for qualitative assessment of the data.

## 🛠️ Technologies Used
* **Language**: Python 3
* **Deep Learning Framework**: TensorFlow, Keras
* **Computer Vision**: OpenCV, PIL (Pillow)
* **Data Analysis**: NumPy, Pandas
* **Visualization**: Matplotlib, Seaborn, VisualKeras

## 🚀 Getting Started

### Prerequisites
Ensure you have the following libraries installed:
```bash
pip install tensorflow pandas numpy matplotlib seaborn opencv-python visualkeras tensorflow-addons

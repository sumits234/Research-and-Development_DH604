<div align="center">

# 🩸 Blood Cell Segmentation & Classification
### Deep Learning for Multi-Class Blood Cell Classification + Mask Segmentation (ResNet50 + U-Net)

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)
[![Deep Learning](https://img.shields.io/badge/Deep%20Learning-U--Net%20%7C%20ResNet50-green.svg)]()
[![Computer Vision](https://img.shields.io/badge/Domain-Medical%20Imaging-orange.svg)]()
[![Framework](https://img.shields.io/badge/Framework-PyTorch%20%7C%20TensorFlow-purple.svg)]()

🔗 **GitHub Repo:** https://github.com/sumits234/Research-and-Development_DH604

</div>

---

## 📌 Project Overview
This project focuses on **blood cell image analysis** using deep learning for:
- **Segmentation** → predicting pixel-wise masks for blood cells
- **Classification** → predicting blood cell type (multi-class)

The system uses a **multi-task architecture** combining:
- **ResNet50 encoder** (feature extraction)
- **U-Net decoder** (segmentation mask generation)

---

## 🚀 Key Features
- ✅ **Multi-task Learning**: joint **classification + segmentation**
- ✅ **U-Net Segmentation**: binary / multi-class mask prediction
- ✅ **ResNet50 Backbone**: strong feature extractor for microscopy images
- ✅ **Customizable Training**: image size, batch size, epochs configurable
- ✅ **Scalable Pipeline**: supports dataset expansion using generated masks

---

## 🧠 Model Architecture
```txt
Input Image
   ↓
ResNet50 Encoder  →  Classification Head (Cell Class)
   ↓
U-Net Decoder     →  Segmentation Mask (Pixel-wise)

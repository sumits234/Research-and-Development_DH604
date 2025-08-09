# 🩸 Blood Cell Segmentation & Classification

Deep learning project for **multi-class blood cell classification** and **image segmentation** using **ResNet50** and **U-Net** architectures.

---

## 🚀 Features
- **Multi-task Model** → ResNet50 encoder + U-Net decoder for joint classification & segmentation.  
- **Segmentation** → Binary/multi-class mask prediction via U-Net.  
- **Customizable** → Easily adjust image size, batch size & training epochs.

---

## 📂 Dataset Structure
```
data/
  images/   # Input blood cell images
  masks/    # Corresponding segmentation masks
```

---

## 🛠 Installation
```bash
pip install tensorflow opencv-python scikit-image scikit-learn matplotlib numpy
```

---

## ▶️ Usage
1. Upload dataset to your local machine or Google Drive.  
2. Update dataset & model paths in the notebook.  
3. Run all cells in **Google Colab** .  
4. Trained `.h5` model files will be saved for inference.

---

## 📊 Output
- **Cell Type Prediction** → Multi-class classification results.  
- **Segmentation Mask** → Overlay mask on the original cell image.

---


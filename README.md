## Blood Cell Segmentation & Classification
Deep learning project for multi-class blood cell classification and segmentation from microscopic images.

# Features
Multi-task model: ResNet50 encoder + U-Net decoder for joint classification & segmentation.

Segmentation: Standalone U-Net for binary/multi-class masks.

Adjustable image size, batch size, and epochs.

Dataset Structure
bash
Copy
Edit
data/
  images/   # Input cell images
  masks/    # Matching segmentation masks
Installation
bash
Copy
Edit
pip install tensorflow opencv-python scikit-image scikit-learn matplotlib numpy
Usage
Upload dataset to Google Drive or local data/ folder.

Update dataset/model paths in the notebook.

Run all cells in Google Colab or Jupyter Notebook.

Trained models (.h5) are saved for later inference.

Output
Cell type prediction (classification).

Segmentation mask overlay on the input image.

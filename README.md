# Brain Tumor Detection using CNN 🧠📊

This project implements a Convolutional Neural Network (CNN) to detect brain tumors from MRI images. The model classifies the MRI scans into **Tumor** and **No Tumor** classes. It uses Keras and TensorFlow for model building and training, and provides visualization of training metrics for performance evaluation.

## 🧪 Project Features

- Image preprocessing and augmentation
- CNN-based binary image classification
- Training and validation accuracy/loss visualization
- Performance metrics: Accuracy, Loss
- Model training and saving

## 📁 Dataset

The dataset consists of brain MRI images, divided into two categories:
- `yes`: Images with brain tumors
- `no`: Images without brain tumors

*(Dataset is expected to be in the `data/` directory with `train/` and `test/` subfolders.)*

## 🛠️ Requirements

Install the dependencies using:
```bash
pip install -r requirements.txt

## 🚀 How to Run

# Step 1: Clone the repo
git clone https://github.com/yourusername/brain-tumor-detection-cnn.git
cd brain-tumor-detection-cnn

# Step 2: Install requirements
pip install -r requirements.txt

# Step 3: Run the notebook
jupyter notebook Brain Tumor Detection using CNN.ipynb

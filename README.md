# 🧬 Leukemia Cell Classification using Transfer Learning

This project aims to classify different types of **leukemia cells** (ALL, AML, CLL, CML) and healthy blood cells (H) using **EfficientNetB7** and **transfer learning**. It leverages a deep learning pipeline for image classification, visualization, and evaluation.

## 📁 Dataset

The dataset consists of labeled microscopic cell images categorized into:

- ALL (Acute Lymphocytic Leukemia)
- AML (Acute Myelogenous Leukemia)
- CLL (Chronic Lymphocytic Leukemia)
- CML (Chronic Myelogenous Leukemia)
- H (Healthy)

Directory structure:

/process/ ├── train/ │ ├── ALL/ │ ├── AML/ │ ├── CLL/ │ ├── CML/ │ └── H/ └── test/ ├── ALL/ ├── AML/ ├── CLL/ ├── CML/ └── H/


## 🛠️ Features

- Image loading and preprocessing with OpenCV
- Label encoding and one-hot conversion
- Transfer learning using **EfficientNetB7**
- Model evaluation with:
  - Accuracy & loss plots
  - Confusion matrices
  - Classification report
  - ROC curve (micro-averaged)
- Callbacks like learning rate reduction and early stopping
- Easily extendable to other CNN architectures (e.g., ResNet50V2, MobileNetV2)

## 🧪 Tech Stack

- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Matplotlib, Seaborn
- Scikit-learn
- TQDM
- Streamlit (optional deployment)
- EfficientNetB7 (pretrained on ImageNet)

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/leukemia-classification.git
cd leukemia-classification
```

Metric	Value
Train Accuracy	98.4%
Test Accuracy	96.2%
AUC Score	~0.98


# Anomaly-Detection
One-Class Industrial Anomaly Detection Using Pretrained ResNet-50 and Memory Bank Patch Embeddings

# MVTec AD Anomaly Detection using PatchCore

This repository contains a Deep Learning pipeline for industrial anomaly detection using a PatchCore-inspired approach with a ResNet-50 backbone.

## 🚀 Project Overview
The project implements a state-of-the-art anomaly detection system that learns from 'normal' samples and identifies defects using multi-scale patch embeddings and a representative Memory Bank.

## 🛠️ Setup Instructions
1. **Clone the repository**:
   ```bash
   git clone <your-repo-link>
   cd <repo-name>
   ```
2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Kaggle API Setup**:
   - Place your `kaggle.json` in `~/.kaggle/` to download the MVTec AD dataset.

## 📂 Folder Structure
- `notebooks/`: Contains the main experimental Colab notebook.
- `data/`: (Local) MVTec dataset storage.
- `requirements.txt`: List of necessary Python packages.
- `README.md`: Project documentation.

## 🔍 Inference
To run inference on a single image, use the provided `run_inference` function within the notebook or script, specifying the image path and object category (e.g., 'bottle').

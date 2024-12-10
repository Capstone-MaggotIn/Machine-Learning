# 🐛 Maggot Classification Model

This repository contains a deep learning-based solution for classifying maggots into various growth stages using TensorFlow and Keras. The application aims to assist maggot farmers in identifying and categorizing maggots based on images captured through a camera.

## 🌟 Features
- **Multi-Class Classification**: Identify six maggot growth stages:
  1. `larva_tahap_1`
  2. `larva_tahap_2`
  3. `larva_tahap_3`
  4. `maggot`
  5. `prapupa`
  6. `pupa`
- **Image Augmentation**: Enhanced generalization with data augmentation.
- **Pre-Trained Model Support**: Compatible with transfer learning for higher accuracy.

## 🗂️ Dataset
The dataset consists of labeled images for each maggot growth stage.

### 📥 Download the Dataset
[![Download Dataset](https://img.shields.io/badge/Download-Dataset-blue?style=for-the-badge&logo=databricks)](link-to-dataset)

## 🚀 Getting Started
Follow the steps below to use the notebook and replicate the model training process.

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/maggot-classification.git
cd maggot-classification
``
### 2. Set Up Environment
Install the required Python packages:
```bash
pip install -r requirements.txt
``
### 3. Download the Dataset
Click the button above to download the dataset. Extract the contents and place them in the data/ directory as follows:
``bash
maggot-classification/
├── data/
│   ├── train/
│   │   ├── larva_tahap_1/
│   │   ├── larva_tahap_2/
│   │   ├── larva_tahap_3/
│   │   ├── maggot/
│   │   ├── prapupa/
│   │   ├── pupa/
│   ├── validation/
│       ├── larva_tahap_1/
│       ├── larva_tahap_2/
│       ├── larva_tahap_3/
│       ├── maggot/
│       ├── prapupa/
│       ├── pupa/
``
### 4. Run the Notebook
Open the Jupyter Notebook **maggot_classification.ipynb** Follow the steps in the notebook to:
1. Load and preprocess the dataset.
2. Train the model using your dataset.
3. Evaluate and save the trained model.

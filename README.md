# **ULTRASOUND IMAGE RECONSTRUCTION: U-NET v/s VISION TRANSFORMER**

## Overview
This project explores the use of deep learning models, specifically **U-Net** and **Vision Transformer**, for reconstructing ultrasound images. The implementation compares the effectiveness of these architectures in medical imaging applications, focusing on enhancing image quality and reconstruction accuracy.

## Features
- **Data Preparation**: Includes normalization, resizing, and augmentation techniques tailored for ultrasound images.
- **Model Architectures**:
  - **U-Net**: A convolutional neural network optimized for image segmentation and reconstruction tasks.
             ![image](https://github.com/user-attachments/assets/3acda841-11b5-4499-b1a1-3d1dbe76dfe6)
  - **Vision Transformer (ViT)**: A cutting-edge model leveraging self-attention mechanisms for image-based tasks.
              ![image](https://github.com/user-attachments/assets/748001bc-d485-457b-bf02-10f6f24dc238)
- **Training Pipeline**:
  - MAE, MSE loss functions for medical image reconstruction
  - Performance metrics: MAE, MSE, SSIM
- **Comparison & Visualization**:
  - Side-by-side analysis of reconstructed images
  - Quantitative metrics for evaluating reconstruction quality

## Requirements
To run this project, you need the following dependencies:
- Python 3.8 or later
- Jupyter Notebook
- TensorFlow or PyTorch (version compatible with Vision Transformers)
- Additional libraries: `numpy`, `matplotlib`, `opencv-python`, `scikit-learn`

## File Structure
- **`Ultrasound_Image_Reconstruction_UNet_Vs_VisionTransformer.ipynb`**: Main notebook containing all code for data processing, model implementation, training, and evaluation.
- **`models/`**: Saved weights for the trained best U-Net and Vision Transformer models.
- **`results/`**: Folder containing reconstructed images and performance metrics.

## How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/ASWINSEKHARCS/Implementation-of-Advanced-AI-Course-Project
   cd ultrasound-reconstruction
## Dataset
Due to size constraints, the dataset is not included in this repository. Use the following links to download the data:

Training Data: Zenodo Dataset ([https:/zenodo.org/records/7813791](url))
Testing Data: IEEE IUS Challenge Dataset ([https://www.creatis.insa-lyon.fr/Challenge/IEEE_IUS_2016/home](url))

## Results

- U-Net excels in capturing fine-grained details in ultrasound images.
- Vision Transformer provides competitive results, especially in scenarios requiring a global contextual understanding.
Detailed performance metrics and reconstructed image samples are available in the results/ folder.

## Developer  
**Name:** Aswin Sekhar C S  
**Student ID:** 2303813
**Email:** aswinsek007@gmail.com  
**LinkedIn Profile:** [LinkedIn Profile Link](https://www.linkedin.com/in/aswinsekhar/)  

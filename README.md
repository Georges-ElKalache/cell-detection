# Brain Cell Identification and Counting from Brain Scans

This repository contains a Jupyter Notebook that presents two methods for automatically identifying and counting brain cells from brain scans. The project focuses on classifying virus-positive cells, oligodendrocytes, and neurons using image processing and machine learning techniques.

## Overview

The notebook is divided into two main methods:

1. **Segmentation using OpenCV Contour Classification**:
   - Utilizes OpenCV for image processing, including color space conversion and contour detection.
   - Converts images to HSV color space for effective color segmentation.
   - Identifies and visualizes virus-positive cells, oligodendrocytes, and neurons.
   - Provides insights into the spatial distribution of detected cells.

2. **Convolutional Neural Network (CNN) Approach**:
   - Implements a CNN model for cell classification.
   - Includes data preprocessing, CNN model design, and training/evaluation steps.
   - Predicts cell types on new images and visualizes the results.

## Key Features

- **OpenCV-based Segmentation**:
  - Color space conversion (RGB to HSV) for better color isolation.
  - Contour detection and centroid calculation for cell identification.
  - Visualization of detected cells and their spatial distribution.

- **CNN-based Classification**:
  - Custom CNN architecture for cell type classification.
  - Data preprocessing pipeline for image resizing, normalization, and tensor conversion.
  - Training and evaluation framework for the CNN model.

## Usage
- Clone the repository:
git clone https://github.com/your-username/brain-cell-identification.git
cd brain-cell-identification

- Open the Jupyter Notebook:
jupyter notebook brain_cell_identification.ipynb
## Requirements

To run the notebook, ensure you have the following Python libraries installed:

- `numpy`
- `matplotlib`
- `pandas`
- `opencv-python`
- `Pillow`
- `torch`
- `torchvision`

You can install the required libraries using `pip`:

```bash
pip install numpy matplotlib pandas opencv-python Pillow torch torchvision

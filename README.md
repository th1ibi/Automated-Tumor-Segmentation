# Tumor Segmentation Project

## Overview
This GitHub repository contains the source code and data for a tumor segmentation project. The aim of this project is to develop a deep learning model for accurately segmenting tumors in medical images.

## Getting Started
To begin with this project, ensure you have the following dependencies installed:
- TensorFlow 
- Keras
- NumPy
- OpenCV
- scikit-image
- scikit-learn
- scipy
- matplotlib


```bash
pip install tensorflow keras numpy opencv-python scikit-image scikit-learn scipy matplotlib
```

## Data
The data for this project includes medical images and corresponding tumor masks.

## Experiments
The experiments are implemented in the `experiments` directory. Each experiment is a Jupyter notebook containing sections for data loading, preprocessing, model architecture, training, evaluation, and visualization.

## Model
The model utilized in this project is based on the U-Net architecture, specifically designed for biomedical image segmentation. The U-Net comprises a contracting path for context extraction and an expanding path for precise localization.

## Results
Results of the experiments, including Dice coefficient, Jaccard index, precision, recall, and F1 score, are stored in the `results` directory.

## Citation
If you use this project or data in your research, please cite the following paper:
Ronneberger, O., Fischer, P., & Brox, T. (2015). U-Net: Convolutional networks for biomedical image segmentation. In International Conference on Medical image computing and computer-assisted intervention (pp. 234-241). Springer, Cham.
